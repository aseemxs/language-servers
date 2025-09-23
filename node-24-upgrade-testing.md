# Node 24 Upgrade Testing Documentation

## Overview
Testing the Node.js version upgrade from Node 18/20 to Node 24 in the AWS Language Server ecosystem, specifically for the language-server-runtimes and language-servers repositories.

## Changes Made

### 1. Node Version Upgrade in language-server-runtimes

Applied PR changes to upgrade Node from 20 to 24:

#### Files Modified:
- **`package.json`**: Updated engine requirements
  ```json
  "engines": {
    "node": ">=24.0.0",
    "npm": ">=7.0.0 <12.0.0"
  }
  ```

- **`runtimes/package.json`**: Updated engine requirements
  ```json
  "engines": {
    "node": ">=24.0.0"
  }
  ```

- **`.github/workflows/runtimes-ci.yaml`**: Updated CI Node version
  ```yaml
  node-version: 24  # Changed from 20
  ```

- **`runtimes/runtimes/lsp/router/initializeUtils.test.ts`**: Updated import syntax
  ```typescript
  // Changed from CommonJS require to ES modules
  import * as assert from 'assert'
  import * as sinon from 'sinon'
  ```

### 2. Build Process with Node 24

#### Environment Setup:
- Installed Node 24.8.0 using nvm
- Set Node 24 as active version for build process

#### Build Sequence:
1. `npm install` - Installed dependencies with Node 24
2. `npm run compile` - Compiled TypeScript with Node 24
3. `npm run pack` (from runtimes/out/) - Generated new tgz package

#### Generated Artifact:
- **`aws-language-server-runtimes-0.3.0.tgz`** - Built with Node 24 requirements

### 3. Language-Servers Integration

#### Updated Dependencies:
- Installed the new Node 24 runtime in language-servers:
  ```bash
  cd language-servers/app/aws-lsp-codewhisperer-runtimes
  npm install /path/to/aws-language-server-runtimes-0.3.0.tgz
  ```

#### Build Verification:
- Successfully compiled language-servers with Node 24
- Successfully packaged language-servers with updated runtime
- Verified codewhisperer-runtimes compiles with Node 24 runtime

### 4. VS Code Integration Setup

#### Configuration Updates:
- Updated `amazonq/.vscode/launch.json` paths:
  ```json
  "__AMAZONQLSP_PATH": "/Users/aseemxs/Language-servers/language-servers/app/aws-lsp-codewhisperer-runtimes/out/agent-standalone.js",
  "__AMAZONQLSP_UI": "/Users/aseemxs/Language-servers/language-servers/chat-client/build/amazonq-ui.js"
  ```

- Enabled LSP experiments in VS Code settings:
  ```json
  "aws.experiments": {
    "amazonqLSP": true,
    "amazonqLSPInline": true,
    "amazonqLSPChat": true
  }
  ```

- Enabled verbose logging:
  ```json
  "amazonq.trace.server": "verbose"
  ```

## Current Testing Status

### ✅ Completed Successfully:
1. Applied all Node 24 upgrade changes from PR
2. Built language-server-runtimes with Node 24
3. Generated new tgz package with Node 24 requirements
4. Updated language-servers to use new Node 24 runtime
5. Verified compilation works with Node 24
6. Configured VS Code for debugging with updated runtime

### 🔄 Currently Testing:
**VS Code Language Server Integration**
- Cleared VS Code language server cache to force use of updated runtime
- Attempting to verify Node 24 is being used by the language server process
- Looking for Node version indicators in language server logs

### 🎯 Expected Outcomes:
1. Language server should start using Node 24.8.0 instead of cached version
2. Logs should show the updated runtime is being used
3. No compatibility issues should occur with Node 24
4. All language server features should work normally

## Repository Locations:
- **language-server-runtimes**: `/Users/aseemxs/language-server-runtimes`
- **language-servers**: `/Users/aseemxs/Language-servers/language-servers`
- **aws-toolkit-vscode**: `/Users/aseemxs/aws-toolkit-vscode`

## Key Files:
- **Runtime TGZ**: `/Users/aseemxs/language-server-runtimes/runtimes/out/aws-language-server-runtimes-0.3.0.tgz`
- **Launch Config**: `/Users/aseemxs/aws-toolkit-vscode/packages/amazonq/.vscode/launch.json`
- **Language Server Binary**: `/Users/aseemxs/Language-servers/language-servers/app/aws-lsp-codewhisperer-runtimes/out/agent-standalone.js`

## Next Steps:
1. Restart VS Code and launch "Launch LSP with Debugging"
2. Verify Node 24 is being used in the language server process
3. Test language server functionality with Node 24
4. Document any issues or successful integration
