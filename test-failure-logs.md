# Test Failure Logs - Node 24 Upgrade

## Command that failed
```bash
npm run test:coverage
```

## Error logs
Paste the complete error logs below:

```
Skip to content
Navigation Menu
aws
language-servers

Type / to search
Code
Issues
12
Pull requests
101
Actions
Projects
Wiki
Security
Insights
Back to pull request #2244
fix: update the node version to 24 #6555
Jobs
Run details
Annotations
1 error and 10 warnings
Test
failed last week in 3m 27s
error
68/100
2s
1s
5s
37s
2m 40s
Run npm run test:coverage
  npm run test:coverage
  shell: /usr/bin/bash -e {0}

> @amzn/monorepo-language-servers@1.0.0 test:coverage
> npm run compile && npm run test:coverage --workspaces --if-present


> @amzn/monorepo-language-servers@1.0.0 precompile
> npm run precompile --workspaces --if-present && npm run compile:core


> @amzn/monorepo-language-servers@1.0.0 compile:core
> npm run compile --workspace=core --if-present && npm run build --workspace=core --if-present


> @aws/lsp-core@0.0.15 compile
> tsc --build


> @amzn/monorepo-language-servers@1.0.0 compile
> tsc --build --verbose && npm run compile:core && npm run compile:servers && npm run compile:rest

9:16:13 PM - Projects in this build: 
    * client/vscode/tsconfig.json
    * chat-client/tsconfig.json
    * core/aws-lsp-core/tsconfig.json
    * server/aws-lsp-json/tsconfig.json
    * server/aws-lsp-yaml/tsconfig.json
    * server/aws-lsp-buildspec/tsconfig.json
    * server/aws-lsp-cloudformation/tsconfig.json
    * server/aws-lsp-codewhisperer/tsconfig.json
    * server/aws-lsp-identity/tsconfig.json
    * server/aws-lsp-notification/tsconfig.json
    * server/hello-world-lsp/tsconfig.json
    * server/aws-lsp-s3/tsconfig.json
    * server/aws-lsp-partiql/tsconfig.json
    * app/aws-lsp-buildspec-runtimes/tsconfig.json
    * app/aws-lsp-cloudformation-runtimes/tsconfig.json
    * app/aws-lsp-codewhisperer-runtimes/tsconfig.json
    * app/aws-lsp-identity-runtimes/tsconfig.json
    * app/aws-lsp-s3-runtimes/tsconfig.json
    * app/hello-world-lsp-runtimes/tsconfig.json
    * app/aws-lsp-json-runtimes/tsconfig.json
    * app/aws-lsp-yaml-runtimes/tsconfig.json
    * app/aws-lsp-yaml-json-webworker/tsconfig.json
    * app/aws-lsp-partiql-runtimes/tsconfig.json
    * integration-tests/q-agentic-chat-server/tsconfig.json
    * tsconfig.json

9:16:13 PM - Project 'client/vscode/tsconfig.json' is out of date because output file 'client/vscode/tsconfig.tsbuildinfo' does not exist

9:16:13 PM - Building project '/home/runner/work/language-servers/language-servers/client/vscode/tsconfig.json'...

9:16:17 PM - Project 'chat-client/tsconfig.json' is out of date because output file 'chat-client/tsconfig.tsbuildinfo' does not exist

9:16:17 PM - Building project '/home/runner/work/language-servers/language-servers/chat-client/tsconfig.json'...

9:16:19 PM - Project 'core/aws-lsp-core/tsconfig.json' is up to date because newest input 'core/aws-lsp-core/src/util/processUtils.ts' is older than output 'core/aws-lsp-core/tsconfig.tsbuildinfo'

9:16:19 PM - Project 'server/aws-lsp-json/tsconfig.json' is out of date because output file 'server/aws-lsp-json/tsconfig.tsbuildinfo' does not exist

9:16:19 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-json/tsconfig.json'...

9:16:19 PM - Project 'server/aws-lsp-yaml/tsconfig.json' is out of date because output file 'server/aws-lsp-yaml/tsconfig.tsbuildinfo' does not exist

9:16:19 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-yaml/tsconfig.json'...

9:16:19 PM - Project 'server/aws-lsp-buildspec/tsconfig.json' is out of date because output file 'server/aws-lsp-buildspec/tsconfig.tsbuildinfo' does not exist

9:16:19 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-buildspec/tsconfig.json'...

9:16:19 PM - Project 'server/aws-lsp-cloudformation/tsconfig.json' is out of date because output file 'server/aws-lsp-cloudformation/tsconfig.tsbuildinfo' does not exist

9:16:19 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-cloudformation/tsconfig.json'...

9:16:19 PM - Project 'server/aws-lsp-codewhisperer/tsconfig.json' is out of date because output file 'server/aws-lsp-codewhisperer/tsconfig.tsbuildinfo' does not exist

9:16:19 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/tsconfig.json'...

9:16:27 PM - Project 'server/aws-lsp-identity/tsconfig.json' is out of date because output file 'server/aws-lsp-identity/tsconfig.tsbuildinfo' does not exist

9:16:27 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-identity/tsconfig.json'...

9:16:27 PM - Project 'server/aws-lsp-notification/tsconfig.json' is out of date because output file 'server/aws-lsp-notification/tsconfig.tsbuildinfo' does not exist

9:16:27 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-notification/tsconfig.json'...

9:16:27 PM - Project 'server/hello-world-lsp/tsconfig.json' is out of date because output file 'server/hello-world-lsp/tsconfig.tsbuildinfo' does not exist

9:16:27 PM - Building project '/home/runner/work/language-servers/language-servers/server/hello-world-lsp/tsconfig.json'...

9:16:28 PM - Project 'server/aws-lsp-s3/tsconfig.json' is out of date because output file 'server/aws-lsp-s3/tsconfig.tsbuildinfo' does not exist

9:16:28 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-s3/tsconfig.json'...

9:16:28 PM - Project 'server/aws-lsp-partiql/tsconfig.json' is out of date because output file 'server/aws-lsp-partiql/tsconfig.tsbuildinfo' does not exist

9:16:28 PM - Building project '/home/runner/work/language-servers/language-servers/server/aws-lsp-partiql/tsconfig.json'...

9:16:30 PM - Project 'app/aws-lsp-buildspec-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-buildspec-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-buildspec-runtimes/tsconfig.json'...

9:16:30 PM - Project 'app/aws-lsp-cloudformation-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-cloudformation-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-cloudformation-runtimes/tsconfig.json'...

9:16:30 PM - Project 'app/aws-lsp-codewhisperer-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-codewhisperer-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-codewhisperer-runtimes/tsconfig.json'...

9:16:30 PM - Project 'app/aws-lsp-identity-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-identity-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-identity-runtimes/tsconfig.json'...

9:16:30 PM - Project 'app/aws-lsp-s3-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-s3-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-s3-runtimes/tsconfig.json'...

9:16:30 PM - Project 'app/hello-world-lsp-runtimes/tsconfig.json' is out of date because output file 'app/hello-world-lsp-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/hello-world-lsp-runtimes/tsconfig.json'...

9:16:30 PM - Project 'app/aws-lsp-json-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-json-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-json-runtimes/tsconfig.json'...

9:16:30 PM - Project 'app/aws-lsp-yaml-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-yaml-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-yaml-runtimes/tsconfig.json'...

9:16:30 PM - Project 'app/aws-lsp-yaml-json-webworker/tsconfig.json' is out of date because output file 'app/aws-lsp-yaml-json-webworker/dist/tsconfig.tsbuildinfo' does not exist

9:16:30 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-yaml-json-webworker/tsconfig.json'...

9:16:31 PM - Project 'app/aws-lsp-partiql-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-partiql-runtimes/tsconfig.tsbuildinfo' does not exist

9:16:31 PM - Building project '/home/runner/work/language-servers/language-servers/app/aws-lsp-partiql-runtimes/tsconfig.json'...

9:16:31 PM - Project 'integration-tests/q-agentic-chat-server/tsconfig.json' is out of date because output file 'integration-tests/q-agentic-chat-server/tsconfig.tsbuildinfo' does not exist

9:16:31 PM - Building project '/home/runner/work/language-servers/language-servers/integration-tests/q-agentic-chat-server/tsconfig.json'...


> @amzn/monorepo-language-servers@1.0.0 compile:core
> npm run compile --workspace=core --if-present && npm run build --workspace=core --if-present


> @aws/lsp-core@0.0.15 compile
> tsc --build


> @amzn/monorepo-language-servers@1.0.0 compile:servers
> npm run compile --workspace=server --if-present


> @aws/lsp-antlr4@0.1.19 compile
> tsc --build


> @aws/lsp-buildspec@0.0.1 compile
> tsc --build


> @aws/lsp-cloudformation@0.0.1 compile
> tsc --build


> @aws/lsp-codewhisperer@0.0.79 compile
> tsc --build


> @aws/lsp-codewhisperer@0.0.79 postcompile
> npm run copyServiceClient


> @aws/lsp-codewhisperer@0.0.79 copyServiceClient
> copyfiles -u 1 --error ./src/client/sigv4/*.json out && copyfiles -u 1 --error ./src/client/token/*.json out


> @aws/lsp-identity@0.0.1 compile
> tsc --build --verbose

9:16:38 PM - Projects in this build: 
    * tsconfig.json

9:16:38 PM - Project 'tsconfig.json' is up to date because newest input 'src/sso/utils.ts' is older than output 'tsconfig.tsbuildinfo'


> @aws/lsp-json@0.1.19 compile
> tsc --build


> @aws/lsp-notification@0.0.1 compile
> tsc --build --verbose

9:16:39 PM - Projects in this build: 
    * tsconfig.json

9:16:39 PM - Project 'tsconfig.json' is up to date because newest input 'src/notifications/notification.ts' is older than output 'tsconfig.tsbuildinfo'


> @aws/lsp-partiql@0.0.18 compile
> tsc --build


> @aws/lsp-partiql@0.0.18 postcompile
> npm run copy-empty-binary


> @aws/lsp-partiql@0.0.18 copy-empty-binary
> tsx build-scripts/create-empty-wasm-file.mts


> @aws/lsp-s3@0.0.1 compile
> tsc --build


> @aws/lsp-yaml@0.1.19 compile
> tsc --build


> @amzn/device-sso-auth-lsp@0.0.1 compile
> tsc --build


> @aws/hello-world-lsp@0.0.1 compile
> tsc --build


> @amzn/monorepo-language-servers@1.0.0 compile:rest
> npm run compile --workspace app --workspace client --workspace chat-client --if-present


> @aws/lsp-antlr4-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-buildspec-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-cloudformation-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-codewhisperer-runtimes@0.0.1 compile
> tsc --build && copyfiles -f src/version.json out/


> @aws/lsp-identity-runtimes@0.1.0 compile
> tsc --build


> @aws/lsp-json-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-notification-runtimes@0.1.0 compile
> tsc --build


> @aws/lsp-partiql-runtimes@0.0.1 compile
> npm run compile:tsc && npm run compile:webpack


> @aws/lsp-partiql-runtimes@0.0.1 compile:tsc
> tsc --build


> @aws/lsp-partiql-runtimes@0.0.1 compile:webpack
> webpack

assets by path *.js 6.9 MiB
  asset aws-lsp-partiql-binary.js 6.88 MiB [emitted] (name: aws-lsp-partiql-binary)
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-067dc8.js 6.05 KiB [emitted]
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-5c3a2a.js 5.86 KiB [emitted]
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-d22e4f.js 5.65 KiB [emitted]
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-f60812.js 3.31 KiB [emitted]
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-e747da.js 2.81 KiB [emitted]
assets by path *.node 220 KiB
  asset crypt32-x64.node 115 KiB [emitted] (auxiliary name: aws-lsp-partiql-binary)
  asset crypt32-ia32.node 90.5 KiB [emitted] (auxiliary name: aws-lsp-partiql-binary)
  asset registry.node 14.6 KiB [emitted] (auxiliary name: aws-lsp-partiql-binary)
asset ../out/index.d.ts 11 bytes [compared for emit]
orphan modules 1.56 MiB [orphan] 296 modules
runtime modules 2.47 KiB 9 modules
modules by path ../../node_modules/ 4.35 MiB
  cacheable modules 4.35 MiB
    javascript modules 4.35 MiB 1027 modules
    json modules 3.07 KiB 2 modules
  ../../node_modules/vscode-languageserver-types/lib/umd/ sync 160 bytes [built] [code generated]
  ../../node_modules/win-ca/lib/ sync ^\.\/crypt32\-.*$ 244 bytes [built] [code generated]
modules by path ./ 1.39 MiB
  modules by path ./node_modules/@aws/lsp-partiql/out/server/ 39 KiB 9 modules
  modules by path ./node_modules/@aws/lsp-partiql/out/antlr-generated/*.js 733 KiB 2 modules
  modules by path ./node_modules/@aws/lsp-partiql/out/tree-sitter-wasm/*.js 646 KiB 2 modules
  ./src/index.ts 344 bytes [built] [code generated]
  ./node_modules/@aws/lsp-partiql/out/index.js 362 bytes [built] [code generated]
+ 41 modules

WARNING in ../../node_modules/vscode-languageserver-types/lib/umd/main.js 3:24-31
Critical dependency: require function is used in a way in which dependencies cannot be statically extracted
 @ ../../node_modules/vscode-languageserver-protocol/lib/common/api.js 23:13-51
 @ ../../node_modules/vscode-languageserver-protocol/lib/node/main.js 24:13-37
 @ ../../node_modules/@aws/language-server-runtimes/protocol/editCompletions.js 4:41-82
 @ ../../node_modules/@aws/language-server-runtimes/runtimes/standalone.js 70:26-64
 @ ./src/index.ts 3:21-81

1 warning has detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

webpack 5.99.9 compiled with 1 warning in 7640 ms

> @aws/lsp-s3-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-yaml-json-webworker@0.0.1 compile
> tsc --build


> @aws/lsp-yaml-runtimes@0.0.1 compile
> tsc --build


> @aws/hello-world-lsp-runtimes@0.0.1 compile
> tsc --build


> awsdocuments-ls-client@0.1.0 compile
> tsc -b && npm run compile:chat-client


> awsdocuments-ls-client@0.1.0 compile:chat-client
> npm run compile --prefix ../../chat-client && shx cp -R ../../chat-client/build .


> @aws/chat-client@0.1.35 compile
> tsc --build && npm run package


> @aws/chat-client@0.1.35 package
> webpack

assets by path ../out/client/ 22.4 KiB
  assets by path ../out/client/*.ts 16.3 KiB 13 assets
  assets by path ../out/client/texts/*.ts 2.41 KiB 6 assets
  assets by path ../out/client/features/*.ts 1.96 KiB 4 assets
  assets by path ../out/client/tabs/*.ts 1.75 KiB
    asset ../out/client/tabs/tabFactory.d.ts 1.73 KiB [compared for emit]
    asset ../out/client/tabs/tabFactory.test.d.ts 11 bytes [compared for emit]
assets by path ../out/contracts/*.ts 8.11 KiB
  asset ../out/contracts/chatClientAdapter.d.ts 3.73 KiB [compared for emit]
  asset ../out/contracts/serverContracts.d.ts 3.24 KiB [compared for emit]
  asset ../out/contracts/telemetry.d.ts 1.13 KiB [compared for emit]
asset amazonq-ui.js 6.75 MiB [emitted] (name: main)
asset ../out/index.d.ts 129 bytes [compared for emit]
asset ../out/test/jsDomInjector.d.ts 45 bytes [compared for emit]
runtime modules 670 bytes 3 modules
modules by path ./src/ 160 KiB
  modules by path ./src/client/ 158 KiB 14 modules
  modules by path ./src/contracts/*.ts 1.75 KiB
    ./src/contracts/serverContracts.ts 144 bytes [built] [code generated]
    ./src/contracts/telemetry.ts 1.61 KiB [built] [code generated]
  ./src/index.ts 261 bytes [built] [code generated]
modules by path ../node_modules/ 2.45 MiB
  modules by path ../node_modules/@aws/language-server-runtimes-types/out/*.js 8.89 KiB 8 modules
  modules by path ../node_modules/@aws/chat-client-ui-types/out/*.js 2.12 KiB
    ../node_modules/@aws/chat-client-ui-types/out/index.js 839 bytes [built] [code generated]
    ../node_modules/@aws/chat-client-ui-types/out/uiContracts.js 1.3 KiB [built] [code generated]
  ../node_modules/@aws/mynah-ui/dist/main.js 2.37 MiB [built] [code generated]
  ../node_modules/vscode-languageserver-types/lib/esm/main.js 75.6 KiB [built] [code generated]
webpack 5.99.9 compiled successfully in 3896 ms

> @aws/chat-client@0.1.35 compile
> tsc --build && npm run package


> @aws/chat-client@0.1.35 package
> webpack

assets by path ../out/client/ 22.4 KiB
  assets by path ../out/client/*.ts 16.3 KiB 13 assets
  assets by path ../out/client/texts/*.ts 2.41 KiB 6 assets
  assets by path ../out/client/features/*.ts 1.96 KiB 4 assets
  assets by path ../out/client/tabs/*.ts 1.75 KiB
    asset ../out/client/tabs/tabFactory.d.ts 1.73 KiB [compared for emit]
    asset ../out/client/tabs/tabFactory.test.d.ts 11 bytes [compared for emit]
assets by path ../out/contracts/*.ts 8.11 KiB
  asset ../out/contracts/chatClientAdapter.d.ts 3.73 KiB [compared for emit]
  asset ../out/contracts/serverContracts.d.ts 3.24 KiB [compared for emit]
  asset ../out/contracts/telemetry.d.ts 1.13 KiB [compared for emit]
asset amazonq-ui.js 6.75 MiB [compared for emit] (name: main)
asset ../out/index.d.ts 129 bytes [compared for emit]
asset ../out/test/jsDomInjector.d.ts 45 bytes [compared for emit]
runtime modules 670 bytes 3 modules
modules by path ./src/ 160 KiB
  modules by path ./src/client/ 158 KiB 14 modules
  modules by path ./src/contracts/*.ts 1.75 KiB
    ./src/contracts/serverContracts.ts 144 bytes [built] [code generated]
    ./src/contracts/telemetry.ts 1.61 KiB [built] [code generated]
  ./src/index.ts 261 bytes [built] [code generated]
modules by path ../node_modules/ 2.45 MiB
  modules by path ../node_modules/@aws/language-server-runtimes-types/out/*.js 8.89 KiB 8 modules
  modules by path ../node_modules/@aws/chat-client-ui-types/out/*.js 2.12 KiB
    ../node_modules/@aws/chat-client-ui-types/out/index.js 839 bytes [built] [code generated]
    ../node_modules/@aws/chat-client-ui-types/out/uiContracts.js 1.3 KiB [built] [code generated]
  ../node_modules/@aws/mynah-ui/dist/main.js 2.37 MiB [built] [code generated]
  ../node_modules/vscode-languageserver-types/lib/esm/main.js 75.6 KiB [built] [code generated]
webpack 5.99.9 compiled successfully in 3826 ms

> @aws/chat-client@0.1.35 test:coverage
> npm run test:unit:coverage


> @aws/chat-client@0.1.35 test:unit:coverage
> c8 ts-mocha -b "./src/**/*.test.ts"



  Chat
    ✔ publishes ready event when initialized
    ✔ publishes telemetry event, when send to prompt is triggered (101ms)
    ✔ publishes telemetry event, when show error is triggered (133ms)
    ✔ publishes tab added event, when UI tab is added (201ms)
    ✔ publishes tab removed event, when UI tab is removed (299ms)
    ✔ publishes tab changed event, when UI tab is changed (801ms)
    ✔ generic command creates a chat request (3938ms)
    ✔ open tab requestId was propagated from inbound to outbound message (2784ms)
    ✔ complete chat response triggers ui events
    ✔ partial chat response triggers ui events
    ✔ partial chat response with header triggers ui events
    chatOptions
      ✔ enables history and export features support
      ✔ does not enable history and export features support if flags are falsy
      ✔ enables MCP when params.mcpServers is true and config.agenticMode is true
      ✔ does not enable MCP when params.mcpServers is true but config.agenticMode is false
      ✔ does not enable MCP when params.mcpServers is false and config.agenticMode is true
      ✔ does not enable MCP when params.mcpServers is undefined and config.agenticMode is true
    onGetSerializedChat
      ✔ getSerializedChat requestId was propagated from inbound to outbound message (3091ms)
    with client adapter
Set Chat events routing with custom client adapter
      ✔ should route inbound message to client adapter

  history
    ✔ show opens detailed list if called the first time
    ✔ show updates detailed list if called the second time
    ✔ show opens detailed list if called after close

  rules
    showLoading
      ✔ opens top bar button overlay with loading message
    show
      ✔ opens top bar button overlay when called first time
      ✔ updates existing overlay when called second time
    rule click handling
      ✔ shows custom form when create rule is clicked
      ✔ calls messager when regular rule is clicked
      ✔ does nothing when item has no id
    folder click handling
      ✔ calls messager when folder is clicked
    keyboard handling
      ✔ closes overlay when Escape is pressed
      ✔ does nothing when other keys are pressed
    close
      ✔ closes the overlay
    convertRulesListToDetailedListGroup
      ✔ converts rules folder to detailed list group
      ✔ handles empty rules array

  imageVerification
    constants
      ✔ has correct MAX_IMAGE_CONTEXT value
      ✔ has correct default options
    isSupportedImageExtension
      ✔ returns true for supported extensions
      ✔ returns true for supported extensions with dots
      ✔ returns true for uppercase extensions
      ✔ returns false for unsupported extensions
    isFileSizeValid
      ✔ returns true for valid file sizes
      ✔ returns false for oversized files
      ✔ accepts custom max size
    areImageDimensionsValid
      ✔ returns true for valid dimensions
      ✔ returns false for oversized dimensions
      ✔ accepts custom max dimension
    verifyClientImage
      ✔ validates a correct image file
      ✔ rejects unsupported file extension
      ✔ rejects oversized files
      ✔ rejects images with oversized dimensions
      ✔ handles image loading errors
    verifyClientImages
      ✔ separates valid and invalid files
      ✔ handles empty file list
      ✔ handles files without names

  McpMynahUi
    listMcpServers
      ✔ should set isMcpServersListActive to true
      ✔ should call mynahUi.openDetailedList with correct parameters
      ✔ should handle disabled servers correctly
      ✔ should handle failed servers correctly
      ✔ should handle events correctly
    mcpServerClick
      - should handle open-mcp-server action correctly
      ✔ should handle server management actions correctly
      ✔ should handle update-mcp-list action correctly
    private helper methods
      ✔ should process filter options correctly
      ✔ should create detailed list for adding MCP server correctly
      ✔ should create detailed list for viewing MCP server correctly

  MynahUI
    handleChatPrompt
      ✔ should handle normal chat prompt
      ✔ should handle clear quick action
      ✔ should handle quick actions
    openTab
      ✔ should create a new tab with welcome messages if tabId not passed and previous messages not passed (2052ms)
      ✔ should create a new tab with messages if tabId is not passed and previous messages are passed (2160ms)
      ✔ should call onOpenTab if a new tab if tabId not passed and tab not created
      ✔ should open existing tab if tabId passed and tabId not selected
      ✔ should not open existing tab if tabId passed but tabId already selected
    sendGenericCommand
      1) should create a new tab if none exits


  72 passing (24s)
  1 pending
  1 failing

  1) MynahUI
       sendGenericCommand
         should create a new tab if none exits:
     Error: Timeout of 5000ms exceeded. For async tests and hooks, ensure "done()" is called; if returning a Promise, ensure it resolves. (/home/runner/work/language-servers/language-servers/chat-client/src/client/mynahUi.test.ts)
      at processImmediate (node:internal/timers:505:21)



-----------------------|---------|----------|---------|---------|-----------------------------------
File                   | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s                 
-----------------------|---------|----------|---------|---------|-----------------------------------
All files              |   63.09 |    69.11 |   42.04 |   63.09 |                                   
 src                   |       0 |        0 |       0 |       0 |                                   
  index.ts             |       0 |        0 |       0 |       0 | 1-2                               
 src/client            |   58.15 |    66.45 |   40.75 |   58.15 |                                   
  chat.ts              |   71.37 |    54.09 |   34.88 |   71.37 | ...95,498,501,504,510,513,527-528 
  imageVerification.ts |   89.18 |    95.83 |   88.88 |   89.18 | 125-140                           
  mcpMynahUi.ts        |   85.82 |    74.66 |   60.71 |   85.82 | ...08-510,513-514,517-518,521-522 
  messager.ts          |   78.33 |    94.11 |   34.88 |   78.33 | ...82-283,286-287,294-295,298-299 
  mynahUi.ts           |   41.14 |    60.16 |   33.82 |   41.14 | ...,1745-1759,1825-1828,1834-1852 
  utils.ts             |   43.75 |    53.84 |   66.66 |   43.75 | 15-22,30-31,39-55,62-68,70-80     
  withAdapter.ts       |   58.03 |    55.55 |   28.57 |   58.03 | ...52-156,160-166,170-171,185-186 
 src/client/features   |   85.26 |    94.59 |   57.69 |   85.26 |                                   
  history.ts           |   67.71 |    93.75 |   45.45 |   67.71 | ...-74,77-79,82-83,86-100,118-126 
  rules.ts             |   96.87 |    95.23 |   66.66 |   96.87 | 97,107-108,132,149-150            
 src/client/tabs       |   64.38 |    67.74 |   43.47 |   64.38 |                                   
  tabFactory.ts        |   64.38 |    67.74 |   43.47 |   64.38 | ...23-228,235-245,249-259,263-277 
 src/client/texts      |   95.16 |      100 |       0 |   95.16 |                                   
  disclaimer.ts        |     100 |      100 |     100 |     100 |                                   
  modelSelection.ts    |   91.93 |      100 |       0 |   91.93 | 36-40                             
  paidTier.ts          |     100 |      100 |     100 |     100 |                                   
  pairProgramming.ts   |   88.28 |      100 |       0 |   88.28 | 99-111                            
 src/contracts         |   58.49 |       50 |       0 |   58.49 |                                   
  chatClientAdapter.ts |       0 |        0 |       0 |       0 | 1-105                             
  serverContracts.ts   |     100 |      100 |     100 |     100 |                                   
  telemetry.ts         |     100 |      100 |     100 |     100 |                                   
-----------------------|---------|----------|---------|---------|-----------------------------------
npm error Lifecycle script `test:unit:coverage` failed with error:
npm error code 1
npm error path /home/runner/work/language-servers/language-servers/chat-client
npm error workspace @aws/chat-client@0.1.35
npm error location /home/runner/work/language-servers/language-servers/chat-client
npm error command failed
npm error command sh -c c8 ts-mocha -b "./src/**/*.test.ts"
npm error Lifecycle script `test:coverage` failed with error:
npm error code 1
npm error path /home/runner/work/language-servers/language-servers/chat-client
npm error workspace @aws/chat-client@0.1.35
npm error location /home/runner/work/language-servers/language-servers/chat-client
npm error command failed
npm error command sh -c npm run test:unit:coverage


> @aws/lsp-core@0.0.15 test:coverage
> npm run test-unit:coverage


> @aws/lsp-core@0.0.15 test-unit:coverage
> npm run compile && c8 mocha --timeout 0 "./out/**/*.test.js"


> @aws/lsp-core@0.0.15 compile
> tsc --build

▶ Test UriCacheRepository
  ✔ cacheContent (37.561222ms)
  ✔ touchLastUpdatedTime (0.627192ms)
  ✔ getContent (0.126959ms)
  ✔ getContentETag (0.102554ms)
✔ Test UriCacheRepository (43.538455ms)
✔ Test CachedContentHandler (0.106742ms)
✔ Test FileHandler (0.083728ms)
✔ Test HttpHandler (0.097043ms)
▶ Test UriResolverBuilder
  ✔ throws when no handler is added (2.995083ms)
  ✔ throws when unhandled (0.89713ms)
  ✔ builds one handler (4.920301ms)
  ✔ delegates to next handler (0.355891ms)
  ✔ stops delegating when a handler returns (0.250612ms)
✔ Test UriResolverBuilder (10.217121ms)
▶ Test mutuallyExclusiveLanguageService
  ✔ 2 services support language, should return 1 result (1.842331ms)
  ✔ languageId is unknown, isSupported, should recognize (0.275749ms)
  ✔ languageId is known, isSupported, should recognize (0.177274ms)
  ✔ languageId is unknown, validate, should return empty diagnostic list (0.332757ms)
  ✔ languageId is known, validate, should return 1 diagnostic (0.762436ms)
  ✔ languageId is unknown, complete, should return null (0.350941ms)
  ✔ languageId is known, complete, should return 1 completion (0.537022ms)
  ✔ languageId is unknown, format, should return null (0.252155ms)
  ✔ languageId is known, format, should return 1 format (0.416956ms)
  ✔ languageId is unknown, hover, should return null (0.237598ms)
  ✔ languageId is known, hover, should return 1 hover (0.258797ms)
✔ Test mutuallyExclusiveLanguageService (5.840244ms)


  ✔ stores data
  ✔ stores data
  ✔ retrieves data
  ✔ retrieves data
  ✔ skips file requests
  ✔ requests content when there is no cache
  ✔ requests content when the cache is stale
  ✔ requests content when a different version is online
  ✔ requests content
  ✔ skips non-file requests
  ✔ requests content
  ✔ skips file requests
  Test HttpRequest class
    Test request()
      ✔ calls the impl with no options
      ✔ calls the impl with the header option

  AwsError
    ✔ Wraps general error in AwsError with given awsErrorCode
    ✔ Wraps null in an AwsError with "Unknown error"
    ✔ Passes AwsError on as-is
    ✔ Passed in cause is retained

  partialClone
    ✔ omits properties by depth
    ✔ omits properties by name
    ✔ truncates properties by maxLength

  filesystemUtilities
    getFileDistance
      ✔ distance 0
      ✔ root distance 0
      ✔ distance 0 with whitespace
      ✔ distance 1
      ✔ distance 3
      ✔ distance 4
      ✔ another distance 4
      ✔ distance 5
      ✔ distance 6
      ✔ distance 6 with whitespaces
      ✔ backslash distance 1
      ✔ backslash distnace 3

  isCodeFile
    ✔ returns true for code files
    ✔ returns false for other files

  pathUtils
    ✔ normalizeSeparator()
    ✔ normalize()
    ✔ isInDirectory()
    sanitizePath
      ✔ trims whitespace from input path
      ✔ expands tilde to user home directory
      ✔ converts relative paths to absolute paths
      ✔ leaves absolute paths unchanged

  pollingSet
    ✔ inherits basic set properties
    ✔ does not poll on initialization
    ✔ does not trigger prematurely
    ✔ stops timer once polling set is empty
    ✔ runs action once per interval

  ChildProcess
    run
      ✔ runs and captures stdout - unix
      ✔ errs when starting twice - unix
      ✔ runs scripts containing a space in the filename and folder
      ✔ reports error for missing executable
      Extra options
        ✔ can report errors
        ✔ can reject on errors if `rejectOnError` is set
        ✔ kills the process if an error is reported
        ✔ can merge with base options
        ✔ respects timeout parameter
    stop()
      ✔ detects running processes and successfully stops a running process - Unix
      ✔ can stop() previously stopped processes - Unix
      ✔ can send input - Unix

  ChildProcessTracker
    - removes stopped processes every 10 seconds
    ✔ logs a warning message when system usage exceeds threshold
    ✔ does not log for processes within threshold

  retryUtils
    retryWithBackoff
      ✔ should return result on first success
      ✔ should retry on retryable errors
      ✔ should not retry on non-retryable client errors
      ✔ should retry on server errors
      ✔ should use exponential backoff by default
      ✔ should respect custom maxRetries
      ✔ should use custom isRetryable function

  sanitizeFilename
    ✔ removes emojis
    ✔ replaces slash with underscore
    ✔ replaces space with underscore
    ✔ replaces dot with replaceString
    ✔ docstring example
    ✔ keeps dot
    ✔ keeps special chars

  undefinedIfEmpty
    ✔ return undefined if input is undefined
    ✔ return undefined if input is empty string
    ✔ return undefined if input is blank
    ✔ return str if input is not empty
    ✔ return original str without trim

  truncate
    ✔ truncate abc 123 to 3 chars
    ✔ truncate abc 123 to -3 chars
    ✔ truncate abc 123 to 1 chars
    ✔ truncate abc 123 to -1 chars
    ✔ truncate abc 123 to 0 chars
    ✔ truncate abc 123 to 99 chars
    ✔ truncate abc 123 to -99 chars

  waitUntil
    ✔ returns value after multiple function calls
    ✔ returns value after multiple function calls WITH backoff
    ✔ timeout before function returns defined value
    ✔ returns true/false values correctly
    ✔ timeout when function takes longer than timeout parameter
    ✔ timeout from slow function calls
    ✔ returns value with after multiple calls and function delay 
    ✔ returns value after setting truthy parameter to true
    ✔ timeout after setting truthy parameter to true

  waitUntil w/ retries
    ✔ should retry when retryOnFail callback returns true
    ✔ should not retry when retryOnFail callback returns false
    ✔ retries the function until it succeeds
    ✔ retryOnFail ignores truthiness
    ✔ throws the last error if the function always fails, using defaults
    ✔ honors retry delay + backoff multiplier

  workspaceUtils
    isParentFolder
      ✔ handles different cases
    isInWorkspace
      ✔ finds the file within the workspace
      ✔ handles multi-root workspaces
      ✔ handles the case where its the workspace itself
    readDirectoryRecursively
      ✔ recurses into subdirectories
      ✔ respects maxDepth parameter
      ✔ correctly identifies entry types
      ✔ respects the failOnError flag
      ✔ always fail if directory does not exist
      ✔ ignores files in the exclude entries
      ✔ ignores directories in the exclude entries
    readDirectoryWithTreeOuput
      ✔ recurses into subdirectories
      ✔ respects maxDepth parameter
      ✔ respects the failOnError flag
      ✔ always fail if directory does not exist
      ✔ ignores files in the exclude entries
      ✔ ignores directories in the exclude entries


  119 passing (291ms)
  1 pending

ℹ Error: A resource generated asynchronous activity after the test ended. This activity created the error "[object Object]" which triggered an unhandledRejection event, caught by the test runner.
ℹ Error: A resource generated asynchronous activity after the test ended. This activity created the error "[object Object]" which triggered an unhandledRejection event, caught by the test runner.
ℹ tests 16
ℹ suites 10
ℹ pass 16
ℹ fail 0
ℹ cancelled 0
ℹ skipped 0
ℹ todo 0
ℹ duration_ms 3480.566786
--------------------------------------|---------|----------|---------|---------|--------------------
File                                  | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s  
--------------------------------------|---------|----------|---------|---------|--------------------
All files                             |   67.12 |    85.42 |   72.66 |   67.12 |                    
 src                                  |       0 |        0 |       0 |       0 |                    
  index.ts                            |       0 |        0 |       0 |       0 | 1-22               
 src/base                             |       0 |        0 |       0 |       0 |                    
  index.ts                            |       0 |        0 |       0 |       0 | 1-5                
 src/content                          |   37.36 |    72.72 |    62.5 |   37.36 |                    
  contentRequestMiddleware.ts         |       0 |        0 |       0 |       0 | 1-39               
  index.ts                            |       0 |        0 |       0 |       0 | 1-8                
  uriResolver.ts                      |       0 |        0 |       0 |       0 | 1-10               
  uriResolverBuilder.ts               |     100 |      100 |     100 |     100 |                    
 src/content/cache                    |   96.49 |     87.5 |    92.3 |   96.49 |                    
  defaultUriCacheLocation.ts          |   83.33 |      100 |       0 |   83.33 | 10-11              
  uriCacheRepository.ts               |   97.48 |     87.5 |     100 |   97.48 | 130-131,137-138    
 src/content/handlers                 |    92.3 |       95 |     100 |    92.3 |                    
  cachedContentHandler.ts             |   87.91 |    92.85 |     100 |   87.91 | 54-64              
  fileHandler.ts                      |     100 |      100 |     100 |     100 |                    
  httpHandler.ts                      |     100 |      100 |     100 |     100 |                    
 src/credentials                      |       0 |        0 |       0 |       0 |                    
  credentialsProvider.ts              |       0 |        0 |       0 |       0 | 1-40               
  encryption.ts                       |       0 |        0 |       0 |       0 | 1-87               
  ideCredentialsProvider.ts           |       0 |        0 |       0 |       0 | 1-180              
  index.ts                            |       0 |        0 |       0 |       0 | 1-5                
  updateCredentialsRequest.ts         |       0 |        0 |       0 |       0 | 1-17               
 src/credentials/error                |       0 |        0 |       0 |       0 |                    
  noCredentialsError.ts               |       0 |        0 |       0 |       0 | 1-6                
 src/http                             |     100 |      100 |     100 |     100 |                    
  requesters.ts                       |     100 |      100 |     100 |     100 |                    
 src/initialization                   |       0 |        0 |       0 |       0 |                    
  awsInitializationOptions.ts         |       0 |        0 |       0 |       0 | 1-12               
 src/language-service                 |   34.03 |    88.88 |   78.57 |   34.03 |                    
  awsLanguageService.ts               |       0 |        0 |       0 |       0 | 1-16               
  emptyLanguageService.ts             |    93.1 |      100 |      80 |    93.1 | 27-28              
  mutuallyExclusiveLanguageService.ts |     100 |      100 |     100 |     100 |                    
  serverBase.ts                       |       0 |        0 |       0 |       0 | 1-108              
 src/util                             |   81.64 |    87.13 |   72.83 |   81.64 |                    
  awsError.ts                         |   85.36 |     87.5 |   42.85 |   85.36 | 31-32,35-36,39-40  
  collectionUtils.ts                  |     100 |    95.23 |     100 |     100 | 46                 
  completionItemUtils.ts              |       0 |        0 |       0 |       0 | 1-7                
  filesystem.ts                       |     100 |      100 |     100 |     100 |                    
  filetype.ts                         |     100 |      100 |     100 |     100 |                    
  gitIgnoreFilter.ts                  |       0 |        0 |       0 |       0 | 1-54               
  httpsUtils.ts                       |       0 |        0 |       0 |       0 | 1-31               
  loggingUtils.ts                     |       0 |        0 |       0 |       0 | 1-30               
  path.ts                             |   94.84 |     92.3 |   83.33 |   94.84 | 29-30,95-97        
  pollingSet.ts                       |     100 |      100 |     100 |     100 |                    
  processUtils.ts                     |   78.03 |       80 |   74.28 |   78.03 | ...483-484,505-506 
  retryUtils.ts                       |    98.7 |    89.47 |     100 |    98.7 | 49                 
  text.ts                             |     100 |      100 |     100 |     100 |                    
  textDocumentUtils.ts                |       0 |        0 |       0 |       0 | 1-14               
  timeProvider.ts                     |   66.66 |      100 |       0 |   66.66 | 4-5                
  timeoutUtils.ts                     |   89.58 |    89.65 |      75 |   89.58 | ...100-101,109-110 
  workspaceUtils.ts                   |   87.83 |    88.42 |    87.5 |   87.83 | ...192-194,197-199 
--------------------------------------|---------|----------|---------|---------|--------------------

> @aws/lsp-codewhisperer@0.0.79 test:coverage
> npm run lint && npm run test:unit:coverage


> @aws/lsp-codewhisperer@0.0.79 lint
> npm run lint:src


> @aws/lsp-codewhisperer@0.0.79 lint:src
> eslint src/ --ext .ts,.tsx


/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/agenticChatController.ts
Warning:   6:1  warning  Do not import Node.js builtin module "crypto"  import/no-nodejs-modules
Warning:   7:1  warning  Do not import Node.js builtin module "path"    import/no-nodejs-modules
Warning:   8:1  warning  Do not import Node.js builtin module "os"      import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/agenticChatResultStream.ts
Warning:   2:1  warning  Do not import Node.js builtin module "crypto"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/context/additionalContextProvider.ts
Warning:   14:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/context/agenticChatTriggerContext.ts
Warning:   32:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/context/contextCommandsProvider.ts
Warning:   1:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/context/contextUtils.ts
Warning:   2:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/chatDb/chatDb.ts
Warning:   29:1  warning  Do not import Node.js builtin module "crypto"  import/no-nodejs-modules
Warning:   30:1  warning  Do not import Node.js builtin module "path"    import/no-nodejs-modules
Warning:   37:1  warning  Do not import Node.js builtin module "fs"      import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/chatDb/chatHistoryMaintainer.ts
Warning:   6:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/chatDb/util.ts
Warning:    6:1  warning  Do not import Node.js builtin module "path"    import/no-nodejs-modules
Warning:   30:1  warning  Do not import Node.js builtin module "crypto"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/fsReplace.ts
Warning:   5:1  warning  Do not import Node.js builtin module "os"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/grepSearch.ts
Warning:   8:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   9:1  warning  Do not import Node.js builtin module "url"   import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/mcp/mcpManager.ts
Warning:   36:1  warning  Do not import Node.js builtin module "events"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/mcp/mcpOauthClient.ts
Warning:    7:1  warning  Do not import Node.js builtin module "crypto"         import/no-nodejs-modules
Warning:    8:1  warning  Do not import Node.js builtin module "path"           import/no-nodejs-modules
Warning:    9:1  warning  Do not import Node.js builtin module "child_process"  import/no-nodejs-modules
Warning:   10:1  warning  Do not import Node.js builtin module "url"            import/no-nodejs-modules
Warning:   11:1  warning  Do not import Node.js builtin module "http"           import/no-nodejs-modules
Warning:   12:1  warning  Do not import Node.js builtin module "os"             import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/mcp/mcpUtils.ts
Warning:   45:18  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/mcp/profileStatusMonitor.ts
Warning:   10:1  warning  Do not import Node.js builtin module "fs"      import/no-nodejs-modules
Warning:   11:1  warning  Do not import Node.js builtin module "path"    import/no-nodejs-modules
Warning:   12:1  warning  Do not import Node.js builtin module "os"      import/no-nodejs-modules
Warning:   13:1  warning  Do not import Node.js builtin module "events"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/tools/toolShared.ts
Warning:   4:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/agenticChat/utils/pathValidation.ts
Warning:   1:1  warning  Do not import Node.js builtin module "fs"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/inline-completion/auto-trigger/autoTrigger.ts
Warning:   1:1  warning  Do not import Node.js builtin module "os"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/netTransform/artifactManager.ts
Warning:   3:1  warning  Do not import Node.js builtin module "crypto"  import/no-nodejs-modules
Warning:   4:1  warning  Do not import Node.js builtin module "fs"      import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/netTransform/transformHandler.ts
Warning:   3:1  warning  Do not import Node.js builtin module "fs"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/netTransform/validation.ts
Warning:   1:1  warning  Do not import Node.js builtin module "fs"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/securityScan/codeWhispererSecurityScanServer.ts
Warning:    9:1  warning  Do not import Node.js builtin module "perf_hooks"  import/no-nodejs-modules
Warning:   10:1  warning  Do not import Node.js builtin module "url"         import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/securityScan/dependencyGraph/dependencyGraph.ts
Warning:   4:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/securityScan/securityScanHandler.ts
Warning:   9:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/artifactManager.ts
Warning:   2:1  warning  Do not import Node.js builtin module "fs"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/dependency/dependencyDiscoverer.ts
Warning:   1:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   2:1  warning  Do not import Node.js builtin module "fs"    import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/dependency/dependencyHandler/DependencyWatcher.ts
Warning:   2:1  warning  Do not import Node.js builtin module "fs"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/dependency/dependencyHandler/JSTSDependencyHandler.ts
Warning:   2:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   3:1  warning  Do not import Node.js builtin module "fs"    import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/dependency/dependencyHandler/JavaDependencyHandler.ts
Warning:   2:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   3:1  warning  Do not import Node.js builtin module "fs"    import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/dependency/dependencyHandler/LanguageDependencyHandler.ts
Warning:   2:1  warning  Do not import Node.js builtin module "fs"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/dependency/dependencyHandler/PythonDependencyHandler.ts
Warning:   3:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   4:1  warning  Do not import Node.js builtin module "fs"    import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/javaManager.ts
Warning:   1:1  warning  Do not import Node.js builtin module "fs/promises"  import/no-nodejs-modules
Warning:   2:1  warning  Do not import Node.js builtin module "path"         import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/util.ts
Warning:   4:1  warning  Do not import Node.js builtin module "fs"      import/no-nodejs-modules
Warning:   5:1  warning  Do not import Node.js builtin module "crypto"  import/no-nodejs-modules
Warning:   6:1  warning  Do not import Node.js builtin module "path"    import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/language-server/workspaceContext/workspaceContextServer.ts
Warning:   8:1  warning  Do not import Node.js builtin module "crypto"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/activeUserTracker.ts
Warning:   10:1  warning  Do not import Node.js builtin module "os"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/amazonQServiceManager/testUtils.ts
Warning:   10:1  warning  Do not import Node.js builtin module "assert"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/codeWhispererService.ts
Warning:   38:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/localProjectContextController.ts
Warning:    2:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:    4:1  warning  Do not import Node.js builtin module "os"    import/no-nodejs-modules
Warning:   18:1  warning  Do not import Node.js builtin module "fs"    import/no-nodejs-modules
Warning:   19:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   21:1  warning  Do not import Node.js builtin module "url"   import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/supplementalContextUtil/codeParsingUtil.ts
Warning:   4:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/supplementalContextUtil/crossFileContextUtil.ts
Warning:   5:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   6:1  warning  Do not import Node.js builtin module "url"   import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/supplementalContextUtil/focalFileResolution.ts
Warning:   6:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   7:1  warning  Do not import Node.js builtin module "os"    import/no-nodejs-modules
Warning:   8:1  warning  Do not import Node.js builtin module "fs"    import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/supplementalContextUtil/supplementalContextUtil.ts
Warning:   14:1  warning  Do not import Node.js builtin module "os"  import/no-nodejs-modules
Warning:   17:1  warning  Do not import Node.js builtin module "fs"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/supplementalContextUtil/unitTestIntentDetection.ts
Warning:   7:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules

/home/runner/work/language-servers/language-servers/server/aws-lsp-codewhisperer/src/shared/utils.ts
Warning:   26:1  warning  Do not import Node.js builtin module "path"  import/no-nodejs-modules
Warning:   28:1  warning  Do not import Node.js builtin module "fs"    import/no-nodejs-modules

✖ 76 problems (0 errors, 76 warnings)


> @aws/lsp-codewhisperer@0.0.79 test:unit:coverage
> c8 ts-mocha --timeout 0 -b "./src/**/*.test.ts"

(node:3150) NOTE: The AWS SDK for JavaScript (v2) is in maintenance mode.
 SDK releases are limited to address critical bug fixes and security issues only.

Please migrate your code to use AWS SDK for JavaScript (v3).
For more information, check the blog post at https://a.co/cUPnyil
(Use `node --trace-warnings ...` to show where the warning was created)


  AgenticChatController
    ✔ creates a session when a tab add notifcation is received
    ✔ deletes a session by tab id when a tab remove notifcation is received
    ✔ deletes a session by tab id an end chat request is received
    ✔ onTabAdd sets active tab id in telemetryController
    ✔ onTabChange sets active tab id in telemetryController and emits metrics
    ✔ onTabRemove unsets tab id if current tab is removed and emits metrics
    ✔ onTabRemove does not unset tabId if current tab is not being removed
    ✔ calls TabBarControlled when tabBarAction request is received
    ✔ determines when an error is a user action
    onChatPrompt
      ✔ read all the response streams and return compiled results
      ✔ creates a new conversationId if missing in the session
      ✔ invokes IdleWorkspaceManager recordActivityTimestamp
      ✔ includes chat history from the database in the request input
      ✔ includes chat history from the database in the compaction request input
      ✔ skips adding user message to history when token is cancelled
      ✔ skips adding user message to history when prompt ID is no longer current
      ✔ handles tool use responses and makes multiple requests
      ✔ propagates tool execution errors to the model in toolResults
      ✔ handles multiple iterations of tool uses with proper history updates
      ✔ returns help message if it is a help follow up action
      ✔ read all the response streams and send progress as partial result is received
      ✔ can use 0 as progress token
      ✔ propagates model error back to client
      ✔ truncate input to 500k character 
      ✔ shows generic errorMsg on internal errors
      ✔ returns full-auth follow up action when model request returns auth error: 'credentialsProvider does not have bearer token credentials'
      ✔ returns full-auth follow up action when model request returns auth error: 'E_AMAZON_Q_PENDING_CONNECTION'
      ✔ returns use-supported-auth follow up action when model request returns auth error: 'E_AMAZON_Q_PENDING_PROFILE'
      ✔ returns a ResponseError if response streams returns an error event
      ✔ returns a ResponseError if response streams return an invalid state event
      Prompt ID
        ✔ sets prompt ID at the beginning of onChatPrompt
      #extractDocumentContext
        ✔ parses relevant document and includes as requestInput if @workspace context is included
        ✔ leaves cursorState as undefined if cursorState is not passed
        ✔ leaves document as undefined if relative file path is undefined
        ✔ parses editor state context and includes as requestInput if both cursor state and text document are found
        ✔ includes both additional context and active file in context transparency list
    truncateRequest
      ✔ should truncate user input message if exceeds limit
      ✔ should not modify user input message if within limit
      ✔ should truncate relevant documents if combined length exceeds remaining budget
      ✔ should truncate current editor if combined length exceeds remaining budget
      ✔ should return remaining budget for history
      ✔ should truncate images when they exceed budget
      ✔ should handle images without bytes
      ✔ should truncate relevantDocuments and images together with equal priority
      ✔ should respect additionalContext order for mixed file and image truncation
    onCreatePrompt
      ✔ should create prompt file with given name
      ✔ should create default prompt file when no name provided
    onInlineChatPrompt
      ✔ read all the response streams and return compiled results
      ✔ read all the response streams and send progress as partial result is received
      ✔ can use 0 as progress token
      ✔ returns a ResponseError if sendMessage returns an error
      ✔ returns a Response error if sendMessage returns an auth error
      ✔ returns a ResponseError if response streams return an error event
      ✔ returns a ResponseError if response streams return an invalid state event
      #extractDocumentContext
        ✔ leaves cursorState as undefined if cursorState is not passed
        ✔ leaves document as undefined if relative file path is undefined
        ✔ parses editor state context and includes as requestInput if both cursor state and text document are found
    onCodeInsertToCursorPosition
      ✔ handles regular insertion correctly
      ✔ handles tab-based indentation correctly
      ✔ handles insertion at mixed indentation levels correctly
      ✔ handles code starting with multiple blank lines correctly
      ✔ handles insertion of code with multiple leading blank lines into empty document at position 0
      ✔ handles undefined document content correctly
      ✔ handles indentation correctly when inserting after an indent
      ✔ handles indentation correctly when inserting at the end of a single line that does not have any indentation
      ✔ handles indentation correctly when inserting inside an indented block
      ✔ handles virtual spaces when cursor is in empty line with virtual indent
      ✔ handles virtual spaces with multiline code containing empty lines
      ✔ handles virtual spaces correctly when code starts with empty line
    Undo All Behavior
      fsWrite tool sequence tracking
        ✔ should track fsWrite tools and reset tracking on non-fsWrite tools
      Undo all button display
        ✔ should show undo all button when there are multiple related tool uses
      Undo all file changes
        ✔ should handle undo all changes button click
      Integration tests
        ✔ should handle the complete undo all workflow
    onPromptInputOptionChange
      ✔ should set model ID from prompt input options
    onListAvailableModels
      ListAvailableModels Cache scenarios
        ✔ should return cached models when cache is valid
        ✔ should return cached models when cache is valid but has empty models array
        ✔ should return cached models when cache is valid but cachedData is null
      ListAvailableModels API call scenarios
        ✔ should fetch models from API when cache is invalid
        ✔ should fall back to hardcoded models when API call fails
        ✔ should handle API response with no defaultModel
      Session and model selection scenarios
        ✔ should return default model when session fails to load
        ✔ should use defaultModelId from cache when session has no modelId
        ✔ should fall back to default model when session has no modelId and no defaultModelId in cache
    IAM Authentication
      ✔ creates a session with IAM service manager
      ✔ uses sendMessage instead of generateAssistantResponse with IAM service manager
      ✔ sets source to Origin.IDE when using IAM service manager
      ✔ sets source to origin from client info when using IAM service manager
      ✔ does not call onManageSubscription with IAM service manager
    processToolUses
      ✔ filters rule artifacts from additionalContext for CodeReview tool

  AgenticChatEventParser
    ✔ set error if invalidState event is received
    ✔ set error if error event is received
    ✔ processPartialEvent appends new event on top of the previous result
    ✔ processPartialEvent with messageMetadataEvent appends conversation id
    ✔ ensures body is an empty string instead of undefined when adding to history
    ✔ getResult returns the accumulated result

  agenticChatResponse
    - combines all previous results on write
    - inherits properties from the last result
    - streams the results to the chat
    - combines results properly
    - throws error if multiple stream writers are initialized
    - allows blocks to overwritten on id

  modelSelection
    modelOptions
      ✔ should contain the correct model options

  AdditionalContextProvider
    getAdditionalContext
      ✔ should return empty array when no additional context commands
      ✔ should process workspace rules and context correctly
      ✔ should handle pinned context correctly
      ✔ should handle explicit context (@-mentions) correctly
      ✔ should avoid duplicates between explicit and pinned context
      ✔ should handle Active File context correctly
      ✔ should remove Active File context when not in pinned context
      ✔ should set hasWorkspace flag when @workspace is present
      ✔ should count context types correctly
      ✔ should handle Unix path separators correctly
      ✔ should handle Windows path separators correctly
    getFileListFromContext
      ✔ should create correct file list for symbol entries
      ✔ should handle non-symbol entries with -1 line ranges
    getContextType
      ✔ should identify rule type for files in .amazonq/rules
      ✔ should identify prompt type for files in user prompts directory
      ✔ should return file type for non-prompt files
    collectWorkspaceRules
      ✔ should return empty array when no workspace folder
      ✔ should return rules files when they exist
      ✔ should update pinned code symbol IDs when they no longer match current index
      convertPinnedContextToChatMessages
        ✔ should return empty array for no pinned context
        ✔ should return empty array for empty pinned context
        ✔ should convert rule context to promptInstruction XML
        ✔ should convert file context to fileContext XML
        ✔ should convert code context to codeContext XML
        ✔ should handle mixed context types
    convertRulesToRulesFolders
      ✔ should convert workspace rules to folders structure
      ✔ should handle rules with explicit active/inactive states

  AgenticChatTriggerContext
    ✔ returns null if text document is not defined in params
    ✔ returns null if text document is not found
    ✔ passes default cursor state if no cursor is found
    ✔ includes cursor state from the parameters and text document if found
    ✔ includes workspace folders as part of editor state in chat params
    ✔ includes modelId in chat params when provided
    ✔ does not include modelId in chat params when not provided
    ✔ includes remote workspaceId if it exists and is connected
    getTextDocument*
      getTextDocumentFromUri
        ✔ returns text document if it is synced
        ✔ falls back to file system if it is not synced
        ✔ returns undefined if both sync and fs fails
      getTextDocumentFromPath
        when text document is synced
          ✔ returns text document
          ✔ loads from file system if workspace is not used
        when text document is not synced
          ✔ falls back to file system
          ✔ returns undefined if the file system is not used
          ✔ returns undefined if fs fails

  ContextCommandsProvider
    getUserPrompts
      ✔ should return empty commands list when directory does not exist
      ✔ should return prompt commands when directory exists with files
    onContextItemsUpdated
      ✔ should call processContextCommandUpdate when controller raises event

  contextUtils
    getUserPromptsDirectory
      ✔ should return the correct prompts directory path
    getNewPromptFilePath
      ✔ should use default name when promptName is empty
      ✔ should use default name when promptName is undefined
      ✔ should trim whitespace from promptName
      ✔ should truncate promptName if longer than 100 characters
      ✔ should sanitize the filename using sanitizeFilename
      ✔ should handle path traversal attempts
    mergeRelevantTextDocuments
      ✔ should return empty FileList when input array is empty
      ✔ should skip documents with missing required fields
      ✔ should merge overlapping line ranges for the same file
      ✔ should handle multiple files correctly
    mergeFileLists
      ✔ should return second FileList when first is empty
      ✔ should return first FileList when second is empty
      ✔ should merge non-overlapping files from both lists
      ✔ should merge overlapping line ranges for the same file
      ✔ should handle consecutive ranges by merging them
      ✔ should handle undefined lineRanges
    getCodeSymbolDescription
      ✔ should return empty string when no symbol exists
      ✔ should format description without line numbers
      ✔ should format description with line numbers
      ✔ should handle different workspace folder names
      ✔ should handle different symbol kinds

  errors
    FileOperationError classes
      ✔ creates error classes with correct customer messages
    createFileOperationError
      ✔ maps common file system errors
      ✔ maps fsWrite specific errors
      ✔ maps fsReplace specific errors
      ✔ returns generic FileOperationError for unknown errors
    getCustomerFacingErrorMessage
      ✔ returns customer message from FileOperationError
      ✔ creates and returns customer message from standard Error
      ✔ handles non-Error objects
    isThrottlingRelated
      ✔ should return true for AgenticChatError with RequestThrottled code
      ✔ should return true for ServiceUnavailableException
      ✔ should return false for other errors

  QAgenticChatServer
    ✔ should initialize ChatSessionManagementService with AmazonQTokenServiceManager instance
    ✔ dispose should dispose all chat session services
    ✔ calls the corresponding controller when tabAdd notification is received
    ✔ calls the corresponding controller when tabRemove notification is received
    ✔ calls the corresponding controller when endChat request is received
    ✔ calls the corresponding controller when chatPrompt request is received
    ✔ calls the corresponding controller when inlineChatPrompt request is received
    ✔ calls the corresponding controller when tabBarAction request is received

  TabBarController
    onListConversations
      ✔ should return full conversation history when no search filter is provided
      ✔ should perform debounced search when search filter is provided
      ✔ should clear previous timeout when multiple search requests are made
      ✔ should attach Delete action to each conversation item in history
      ✔ should attach Export action if client supports window.showSaveFileDialog protocol
      ✔ should attach actions to each conversation item in history when search filter is applied
      ✔ does not attach actions to empty conversation list result
    onConversationClick
      ✔ should focus existing tab when conversation is already open
      ✔ should restore tab when conversation is not already open
      ✔ should delete conversation when delete action is specified
      ✔ should not perform actions when item with `empty` historyId is clicked
    export conversation
      ✔ should write serialized chat content to the location selected by user
      ✔ should restore conversation tab and export conversation if tab was not opened
      ✔ should fail if tab was not restored during export
      ✔ should export conversation on tabBarAction call
    restoreTab
      ✔ should open new tab with conversation messages
      ✔ should do nothing when tab is null or undefined
      ✔ should limit messages to MaxRestoredHistoryMessages when count exceeds the limit
    loadChats
      ✔ should restore all open tabs from history
      ✔ should only load chats once

  ChatDatabase
    replaceWithSummary
      ✔ should create a new history with summary message
    replaceHistory
      ✔ should replace history with messages
    ensureValidMessageSequence
      ✔ should preserve valid alternating sequence
      ✔ should remove assistant messages from the beginning
      ✔ should remove user messages with tool results from the beginning
      ✔ should remove multiple user-assistant pairs with tool results from the beginning
      ✔ should add a dummy response at the end
      ✔ should handle empty message array
    validateNewMessageToolResults
      ✔ should handle empty history message array
      ✔ should handle new user message with valid tool results
      ✔ should handle new user message with missing tool results
      ✔ should handle new user message with tool results after assistant message without tool uses
      ✔ should handle new user message with invalid tool results ID
      ✔ should handle multiple tool uses and results correctly
      ✔ should handle new user message with no tool results and blank content
    calculateNewMessageCharacterCount
      ✔ should calculate character count for new message and pinned context
    getWorkspaceIdentifier
      ✔ case 1: old plugin, workspaceFilePath is not provided. Should return folder based ID
      ✔ case 2: new plugin, workspaceFilePath is provided, no existing folder based history file. Should return ws file based ID
      ✔ case 3: new plugin, workspaceFilePath is provided, folder based history file exists. Should migrate to ws file based ID
    Model Cache Management
      ✔ should cache and retrieve models
      ✔ should validate cache expiry
      ✔ should clear cached models
      ✔ should clear model cache via static method when instance exists
      ✔ should handle static clearModelCache when no instance exists

  ChatHistoryMaintainer
    trimHistoryToMaxSize
      ✔ should trim history until size is below the limit
      ✔ should handle already under limit case

  ChatDb Utilities
    messageToStreamingMessage
      ✔ should convert prompt message to userInputMessage
      ✔ should convert answer message to assistantResponseMessage
    messageToChatMessage
      ✔ should convert Message to ChatMessage
      ✔ should omit relatedContent when content array is empty
    chatMessageToMessage
      ✔ should convert userInputMessage to prompt Message
      ✔ should convert assistantResponseMessage to answer Message
    updateOrCreateConversation
      ✔ should add message to existing conversation
      ✔ should create new conversation when conversationId does not exist
      ✔ should update conversation with updatedAt timestamp
    groupTabsByDate
      ✔ should group tabs by date ranges
      ✔ should filter out empty groups
      ✔ should sort tabs by updatedAt in descending order within groups
    FileSystemAdapter
      ensureDirectory
        ✔ should create directory with recursive option
      loadDatabase
        ✔ should load database file when it exists
        ✔ should return undefined when file does not exist
        ✔ should handle errors during directory creation
      saveDatabase
        ✔ should save database file
        ✔ should handle errors during save
      deleteDatabase
        ✔ should delete database file
        ✔ should handle errors during delete
    HistoryOrdering
      ✔ should create history priority queue, oldest history message first

  Image Block Utilities
    estimateCharacterCountFromImageBlock
      ✔ should estimate character count for image with bytes
      ✔ should return 0 for image without bytes
      ✔ should return 0 for image with null bytes
      ✔ should handle small image sizes

  CodeSearch Tool
    ✔ invalidates empty query
    ✔ returns empty results when no matches found
    ✔ returns formatted results when matches found
    ✔ handles chunks without programming language
    ✔ uses default workspace folder when path not provided
    ✔ handles errors from LocalProjectContextController
    ✔ provides correct queue description
    ✔ returns correct tool specification

  ExecuteBash Tool
    ✔ pass validation for a safe command (read-only)
    ✔ fail validation if the command is empty
    ✔ set requiresAcceptance=true if the command has dangerous patterns
    ✔ set requiresAcceptance=false if it is a read-only command
    ✔ whichCommand cannot find the first arg
    ✔ validate and invokes the command
    ✔ requires acceptance if the command references an absolute file path outside the workspace
    ✔ does NOT require acceptance if the command references a relative file path inside the workspace
    ✔ does NOT require acceptance if there is no path-like token in the command
    isLikelyCredentialFile
      ✔ should identify credential files by name
      ✔ should identify credential files by extension
      ✔ should identify credential-related config files
      ✔ should not identify non-credential files
      ✔ should require acceptance for network commands like ping
      ✔ should require acceptance for network commands like dig
    isLikelyBinaryFile
      on Windows
        ✔ should identify Windows executable extensions
        ✔ should not identify non-executable extensions on Windows
      on Unix
        ✔ should identify files with execute permissions
        ✔ should not identify files without execute permissions
        ✔ should not identify non-existent files
        ✔ should not identify directories

  FileSearch Tool
    ✔ invalidates empty path
    ✔ invalidates invalid threshold pattern
    ✔ invalidates empty maxDepth
    ✔ invalidates empty queryName
    ✔ searches for files matching pattern
    ✔ searches recursively in subdirectories
    ✔ respects maxDepth parameter
    ✔ performs case-insensitive search by default
    ✔ performs case-sensitive search when specified
    ✔ ignores excluded directories
    ✔ throws error if path does not exist
    ✔ expands ~ path

  FsRead Tool
    ✔ invalidates empty path
    ✔ invalidates non-existent paths
    ✔ truncate output if too large
    ✔ reads entire file
    ✔ reads multiple files
    ✔ should require acceptance if fsPath is outside the workspace
    ✔ should not require acceptance if fsPath is inside the workspace

  FsReplace Tool
    handleReplace
      ✔ replaces a single occurrence of a string
      ✔ throws error when no matches are found
      ✔ throws error when multiple matches are found
      ✔ handles regular expression special characters correctly
      ✔ preserves whitespace and newlines during replacement
    getStrReplaceContent
      ✔ preserves CRLF line endings in file when oldStr uses LF
      ✔ preserves LF line endings in file when oldStr uses CRLF
      ✔ preserves CR line endings in file when oldStr uses LF
      ✔ handles mixed line endings in newStr by normalizing to file line ending
      ✔ handles content with no line endings
      ✔ uses OS default line ending when file has no line endings and adding new lines
      ✔ preserves line endings when only portion of line is replaced

  FsWrite Tool
    ✔ writes a empty space to updates stream
    handleCreate
      ✔ creates a new file with fileText content
      ✔ replaces existing file with fileText content
    handleAppend
      ✔ appends text to the end of a file
      ✔ adds a newline before appending if file does not end with one
      ✔ appends to an empty file
      ✔ appends multiple lines correctly
      ✔ throws error when file does not exist

  GrepSearch Tool
    ✔ fails validation if the query is empty
    ✔ uses workspace folder as default path if none provided
    ✔ processes ripgrep output correctly
    ✔ handles empty search results
    ✔ respects case sensitivity option
    ✔ applies include patterns correctly
    ✔ applies exclude patterns correctly

  ListDirectory Tool
    ✔ invalidates empty path
    ✔ invalidates negative maxDepth
    ✔ lists directory contents
    ✔ lists directory contents recursively
    ✔ lists directory contents with ignored pattern
    ✔ includes files that only start with ignored entry
    ✔ throws error if path does not exist
    ✔ expands ~ path

  ChokidarFileWatcher
    watchPaths
      ✔ should create watcher with correct paths and options
      ✔ should register event handlers
      ✔ should call callback on file add
      ✔ should call callback on file change
      ✔ should handle errors
      ✔ should close existing watcher before creating new one
    close
      ✔ should close watcher and reset to null
      ✔ should do nothing if no watcher exists

  McpEventHandler error handling
    ✔ displays config load errors in the header status
    ✔ marks servers with validation errors as FAILED
    ✔ handles server click events for fixing failed servers
    #getListMcpServersStatus
      ✔ returns admin disabled status when MCP state is false
      ✔ returns config error status when MCP state is not false but config errors exist
      ✔ returns undefined status when MCP state is not false and no config errors

  init()
    ✔ returns the same instance

  getAllTools()
    ✔ returns empty array when no servers

  callTool()
    ✔ throws when server is unknown
    ✔ throws when server is disabled
    ✔ invokes underlying client.callTool
    ✔ times out and logs error

  addServer()
    ✔ persists config and initializes
    ✔ persists and initializes an HTTP server

  removeServer()
    ✔ shuts client and cleans state
    ✔ removes server from agent config

  mutateConfigFile()
    ✔ reads, mutates, and writes config file
    ✔ creates new config file if it does not exist

  updateServer()
    ✔ re‑initializes when changing timeout
    ✔ switches from stdio to http by clearing command and setting url

  requiresApproval()
    ✔ returns true for unknown server
    ✔ returns false when tool is in allowedTools

  getAllServerConfigs()
    ✔ returns snapshot

  getServerState()
    ✔ returns runtime info

  getAllServerStates()
    ✔ returns a map with info

  getEnabledTools()
    ✔ filters out disabled tools
    ✔ filters out tools from disabled servers

  getAllToolsWithPermissions()
    ✔ reports permission value
    ✔ honours serverFilter

  isServerDisabled()
    ✔ returns true when server is disabled
    ✔ returns false when server is enabled
    ✔ returns false when disabled property is undefined

  close()
    ✔ shuts all clients and resets singleton

  listServersAndTools()
    ✔ lists names grouped by server

  updateServerPermission()
    ✔ updates tool permissions

  reinitializeMcpServers()
    ✔ closes then reloads servers

  handleError()
    ✔ logs error and emits FAILED state + toolsChanged

  concurrent server initialization
    ✔ initializes multiple servers concurrently with a limit of 5 (103ms)

  McpManager error handling
    ✔ stores and returns config load errors
    ✔ returns undefined when no errors exist
    ✔ logs error and updates server state
    ✔ clears errors when reloading configurations

  OAuthClient helpers
    ✔ computeKey() generates deterministic SHA-256 hex
    ✔ b64url() strips padding and is URL-safe

  OAuthClient getValidAccessToken()
    ✔ returns cached token when still valid

  McpTool
    ✔ invoke() throws when server is not connected
    ✔ requiresAcceptance consults manager.requiresApproval flag

  loadMcpServerConfigs
    ✔ loads valid configs and skips invalid ones
    ✔ normalizes file:// URIs
    ✔ dedupes same server name across files, keeping first
    ✔ workspace config overrides global config of the same server
    ✔ loads config that uses url only
    ✔ skips server that specifies both command and url
    ✔ skips server that has neither command nor url

  loadPersonaPermissions
    ✔ creates a default persona and returns a wildcard-enabled map

  loadAgentConfig
    ✔ creates a default agent config when none exists
    ✔ loads valid server configs from agent config

  path helpers
    ✔ getWorkspacePersonaConfigPaths()
    ✔ getGlobalPersonaConfigPath()
    ✔ getWorkspaceAgentConfigPaths()
    ✔ getGlobalAgentConfigPath()

  saveAgentConfig
    ✔ saves agent config to the specified path
    ✔ creates parent directories if they do not exist

  loadMcpServerConfigs error handling
    ✔ captures file not found errors
    ✔ captures invalid JSON errors
    ✔ captures missing mcpServers field errors
    ✔ captures invalid timeout errors
    ✔ loads valid servers while capturing errors for invalid ones

  enabledMCP
    ✔ should return true when client passes in mcp = true
    ✔ should return false when client passes in mcp = false
    ✔ should return false when client does not pass in mcp

  createNamespacedToolName
    ✔ adds server prefix when tool name conflicts
    ✔ truncates server name when combined length exceeds limit
    ✔ uses numeric suffix when tool name is too long

  normalizePathFromUri
    ✔ returns empty path unchanged
    ✔ converts file URI to filesystem path
    ✔ returns non-URI path unchanged
    ✔ handles parsing errors and logs warning
    ✔ returns original path when parsing fails without logger

  sanitizeContent
    ✔ removes Unicode Tag characters (U+E0000–U+E007F)

  getWorkspaceMcpConfigPaths
    ✔ returns correct paths for workspace MCP configs

  getGlobalMcpConfigPath
    ✔ returns correct global MCP config path

  isEmptyEnv
    ✔ returns true for undefined env
    ✔ returns true for null env
    ✔ returns true for empty object
    ✔ returns true for object with empty keys/values
    ✔ returns false for object with valid key-value pairs

  sanitizeName
    ✔ returns original name if valid
    ✔ filters invalid characters
    ✔ removes namespace delimiter
    ✔ returns hash for empty sanitized string

  convertPersonaToAgent
    ✔ converts basic persona to agent config
    ✔ handles alwaysAllow permissions

  migrateToAgentConfig
    ✔ migrates when no existing configs exist
    ✔ migrates existing MCP config to agent config

  saveServerSpecificAgentConfig
    ✔ creates new config file when it does not exist
    ✔ updates existing config file
    ✔ removes existing server tools before adding new ones
    ✔ creates parent directories if they do not exist

  ProfileStatusMonitor
    start
      ✔ should start monitoring and log info message
      ✔ should not start multiple times
    stop
      ✔ should stop monitoring and log info message
    checkInitialState
      ✔ should return true when no profile ARN is available
      ✔ should return true and log debug message on error
    getMcpState
      ✔ should return undefined initially
      ✔ should return the last MCP state after it is set
      ✔ should be accessible across different instances
    static lastMcpState
      ✔ should maintain state across multiple instances

  CodeReview
    static properties
      ✔ should have correct tool name
      ✔ should have tool description
      ✔ should have input schema
    execute
      ✔ should execute successfully with valid input (10006ms)
      ✔ should execute successfully and pass languageModelId and clientType to startCodeAnalysis (10003ms)
      ✔ should handle missing client error
      ✔ should handle missing artifacts error
      ✔ should handle upload failure
      ✔ should handle analysis start failure
      ✔ should handle scan timeout
      ✔ should handle cancellation
    validateInputAndSetup
      ✔ should validate and setup correctly for file artifacts
      ✔ should validate and setup correctly for folder artifacts
    prepareFilesAndFoldersForUpload
      ✔ should prepare files and folders for upload (55ms)
      ✔ should handle code diff generation
      ✔ should throw error when no valid files to scan
      ✔ should handle duplicate rule filenames with unique UUIDs
    collectFindings
      ✔ should collect findings for full review
      ✔ should filter findings for code diff review
      ✔ should handle pagination
    aggregateFindingsByFile
      ✔ should aggregate findings by file path
    resolveFilePath
      ✔ should resolve file path from file artifacts
      ✔ should resolve file path from folder artifacts
      ✔ should resolve file path with common suffix matching
      ✔ should return null for unresolvable paths
    checkCancellation
      ✔ should not throw when cancellation is not requested
      ✔ should throw CancellationError when cancellation is requested
    error handling
      ✔ should handle unexpected errors gracefully

  CodeReviewUtils
    shouldSkipFile
      ✔ should skip files with no extension
      ✔ should skip files with empty extension
      ✔ should not skip files with supported extensions
      ✔ should skip files with unsupported extensions
      ✔ should handle uppercase extensions
    shouldSkipDirectory
      ✔ should skip directories in the skip list
      ✔ should not skip directories not in the skip list
    getFolderPath
      ✔ should return directory path for file paths
      ✔ should return the same path for directory paths
      ✔ should handle paths with trailing slashes
    logZipSummary
      ✔ should log zip summary information
      ✔ should handle errors gracefully
    generateClientToken
      ✔ should generate a unique token
    executeGitCommand
      ✔ should execute git command and return output on success
      ✔ should handle errors and return empty string
    getGitDiff
      ✔ should get combined git diff for a path
      ✔ should return null if no diff is found
      ✔ should handle errors
    logZipStructure
      ✔ should log zip file structure
    countZipFiles
      ✔ should count files in zip correctly
      ✔ should return 0 for empty zip
    generateZipBuffer
      ✔ should call generateAsync with correct options
    saveZipToDownloads
      ✔ should save zip buffer to downloads folder
      ✔ should handle errors
    processArtifactWithDiff
      ✔ should return empty string if not a code diff scan
      ✔ should return diff with newline if code diff scan
      ✔ should handle null diff result
      ✔ should handle errors
    withErrorHandling
      ✔ should return operation result on success
      ✔ should handle errors and log them
      ✔ should handle errors without path
    isAgenticReviewEnabled
      ✔ should return true when codeReviewInChat is enabled
      ✔ should return false when codeReviewInChat is disabled
      ✔ should return false when q capabilities are undefined
      ✔ should return false when params are undefined
    convertToUnixPath
      ✔ should convert Windows path to Unix format
      ✔ should handle paths without drive letter
      ✔ should not modify Unix paths
    createErrorOutput
      ✔ should create standardized error output object
    uploadFileToPresignedUrl
      ✔ should upload file to presigned URL successfully
      ✔ should handle upload failure with non-200 status code
      ✔ should handle network errors during upload
    checkCancellation
      ✔ should not throw when cancellation is not requested
      ✔ should throw CancellationError when cancellation is requested
      ✔ should use custom message when provided
      ✔ should not throw when cancellation token is undefined
    emitMetric
      ✔ should emit a success metric with all parameters
      ✔ should emit a failure metric with required reason
      ✔ should handle metrics without metadata

  DisplayFindings
    static properties
      ✔ should have correct tool name
      ✔ should have tool description
      ✔ should have input schema
    execute
      ✔ should execute successfully with valid input
      ✔ should handle multiple findings for same file
      ✔ should handle findings for different files
      ✔ should handle empty findings array
      ✔ should handle invalid input schema
      ✔ should handle cancellation
      ✔ should handle unexpected errors gracefully
    validateInputAndSetup
      ✔ should validate and setup correctly
    mapToCodeReviewFinding
      ✔ should map DisplayFinding to CodeReviewFinding correctly
      ✔ should handle missing suggestedFixes
    aggregateFindingsByFile
      ✔ should aggregate findings by file path
      ✔ should handle findings from different files
    checkCancellation
      ✔ should not throw when cancellation is not requested
      ✔ should throw CancellationError when cancellation is requested

  DisplayFindingsUtils
    emitMetric
      ✔ should emit a success metric with metadata
      ✔ should emit a failure metric with reasonDesc
      ✔ should handle metrics without metadata

  shlex.split for Windows command parsing
    ✔ should correctly split a git commit command with quotes
    ✔ should handle AWS CLI commands with JSON payloads
    ✔ should handle multiline commands
    ✔ should handle PowerShell commands with complex quoting
    ✔ should handle commands with environment variables

  toolShared
    isPathApproved
      ✔ should return false if approvedPaths is undefined
      ✔ should return false if approvedPaths is empty
      ✔ should return true if the exact path is in approved paths
      ✔ should return true if a path is a parent folder
      ✔ should handle paths with trailing slashes
      ✔ should handle paths without trailing slashes
      - should normalize Windows-style paths
      ✔ should match normalized paths with different trailing slashes
      ✔ should work with multiple approved paths
      ✔ should respect case sensitivity appropriately
      ✔ should handle root directory as approved path
      - should handle mixed path separators
    requiresPathAcceptance
      ✔ should return requiresAcceptance=false if path is already approved
      ✔ should return requiresAcceptance=true if no workspace folders are found
      ✔ should return requiresAcceptance=false if path is in workspace
      ✔ should return requiresAcceptance=true if path is not in workspace
      ✔ should return requiresAcceptance=true if an error occurs
      ✔ should handle undefined logging gracefully
      ✔ should handle undefined approvedPaths gracefully

  commandParser
    parseBaseCommands
      ✔ should extract base command from a simple command
      ✔ should extract multiple commands separated by &&
      ✔ should extract multiple commands separated by ||
      ✔ should extract multiple commands separated by |
      ✔ should handle commands with quotes
      ✔ should return empty array for null, undefined, empty input
      ✔ should handle commands with semicolons
      ✔ should handle commands with sudo prefix
      ✔ should handle commands with time prefix
      ✔ should handle commands with path prefixes
      ✔ should handle commands with sudo and path prefixes
      ✔ should handle multiple commands with mixed separators
      ✔ should handle commands with other common prefixes
      ✔ should handle commands with function calls

  calculateModifiedLines
    ✔ should return 0 for unknown tools
    FS_WRITE
      ✔ should count lines for create command
      ✔ should count lines for append command
      ✔ should handle empty content
    FS_REPLACE
      ✔ should count replaced lines correctly (double counting)
      ✔ should count pure deletions
      ✔ should count pure insertions
      ✔ should handle multiple diffs

  Path Validation Utilities
    validatePathBasic
      ✔ should not throw error for valid path
      ✔ should throw error for empty path
      ✔ should throw error for path with only whitespace
      ✔ should throw error for undefined path
    validatePathExists
      ✔ should not throw error when path exists
      ✔ should throw error when path does not exist
      ✔ should throw error for empty path before checking existence
    validatePaths
      ✔ should not throw error for valid array of paths
      ✔ should throw error for empty array
      ✔ should throw error for undefined array
      ✔ should throw error if any path in array does not exist
      ✔ should throw error if any path in array is empty

  ChatController
    ✔ creates a session when a tab add notifcation is received
    ✔ deletes a session by tab id when a tab remove notifcation is received
    ✔ deletes a session by tab id an end chat request is received
    ✔ onTabAdd sets active tab id in telemetryController
    ✔ onTabChange sets active tab id in telemetryController and emits metrics
    ✔ onTabRemove unsets tab id if current tab is removed and emits metrics
    ✔ onTabRemove does not unset tabId if current tab is not being removed
    onChatPrompt
      ✔ read all the response streams and return compiled results
      ✔ returns help message if it is a help follow up action
      ✔ read all the response streams and send progress as partial result is received
      ✔ can use 0 as progress token
      ✔ returns a ResponseError if sendMessage returns an error
      ✔ returns full-auth follow up action when sendMessage throws credentialsProvider does not have bearer token credentials
      ✔ returns full-auth follow up action when sendMessage throws E_AMAZON_Q_PENDING_CONNECTION
      ✔ returns use-supported-auth follow up action when sendMessage throws E_AMAZON_Q_PENDING_PROFILE
      ✔ returns a ResponseError if response streams return an error event
      ✔ returns a ResponseError if response streams return an invalid state event (43ms)
      #extractDocumentContext
        ✔ leaves editor state as undefined if cursorState is not passed
        ✔ leaves editor state as undefined if relative file path is undefined
        ✔ parses editor state context and includes as requestInput if both cursor state and text document are found
    onInlineChatPrompt
      ✔ read all the response streams and return compiled results
      ✔ read all the response streams and send progress as partial result is received
      ✔ can use 0 as progress token
      ✔ returns a ResponseError if sendMessage returns an error
      ✔ returns a Response error if sendMessage returns an auth error
      ✔ returns a ResponseError if response streams return an error event
      ✔ returns a ResponseError if response streams return an invalid state event
      ✔ emits telemetry on successful inline chat response
      ✔ emits failure telemetry when inline chat service invocation fails
      #extractDocumentContext
        ✔ leaves editor state as undefined if cursorState is not passed
        ✔ leaves editor state as undefined if relative file path is undefined
        ✔ parses editor state context and includes as requestInput if both cursor state and text document are found
    onCodeInsertToCursorPosition
      ✔ handles regular insertion correctly
      ✔ handles tab-based indentation correctly
      ✔ handles insertion at mixed indentation levels correctly
      ✔ handles code starting with multiple blank lines correctly
      ✔ handles insertion of code with multiple leading blank lines into empty document at position 0
      ✔ handles undefined document content correctly
      ✔ handles indentation correctly when inserting after an indent
      ✔ handles indentation correctly when inserting at the end of a single line that does not have any indentation
      ✔ handles indentation correctly when inserting inside an indented block
      ✔ handles virtual spaces when cursor is in empty line with virtual indent
      ✔ handles virtual spaces with multiline code containing empty lines
      ✔ handles virtual spaces correctly when code starts with empty line

  ChatEventParser
    ✔ set error if invalidState event is received
    ✔ set error if error event is received
    ✔ processPartialEvent appends new event on top of the previous result
    ✔ processPartialEvent with messageMetadataEvent appends conversation id
    ✔ getResult returns the accumulated result

  ChatSessionManagementService
    ✔ getInstance should return the same instance if initialized
    Session interface
      ✔ getSession should create a client if not found and returns existing client if found
      ✔ creating a session with an existing id should return existing session
      ✔ deleting session should dispose the chat session service and delete from map
      ✔ disposing the chat session management should dispose all the chat session services

  Chat Session Service
    ✔ clear() in IAM client, resets conversation id and aborts outgoing request
    calling SendMessage
      ✔ throws error is AmazonQTokenServiceManager is not initialized
      ✔ should fill in conversationId in the request if exists
      ✔ abortRequest() aborts request with AbortController
      ✔ dispose() calls aborts outgoing requests
      ✔ clear() resets conversation id and aborts outgoing request
    calling GenerateAssistantResponse
      ✔ throws error is AmazonQTokenServiceManager is not initialized
      ✔ should fill in conversationId in the request if exists
      ✔ abortRequest() in IAM client, aborts request with AbortController
      ✔ dispose() in IAM client, calls aborts outgoing requests
      ✔ abortRequest() aborts request with AbortController
      ✔ dispose() calls aborts outgoing requests
      ✔ clear() resets conversation id and aborts outgoing request
    Prompt ID
      ✔ should initialize with undefined promptId
      ✔ should set and check current prompt ID
    Approved Paths
      ✔ should initialize with an empty set of approved paths
      ✔ should add a path to approved paths
      ✔ should not add empty paths
      ✔ should normalize Windows-style paths
      ✔ should handle multiple paths correctly
      ✔ should not add duplicate paths
      ✔ should treat normalized paths as the same path
    IAM client source property
      ✔ sets source to Origin.IDE when using StreamingClientServiceIAM
      ✔ calls getOriginFromClientInfo and uses returned origin in SendMessage request
    Error handling for model capacity issues
      getChatResponse error handling
        ✔ should handle HTTP 500 error with specific message when model selection is enabled
        ✔ should handle HTTP 500 error with specific message when model selection is disabled
        ✔ should handle HTTP 429 error with INSUFFICIENT_MODEL_CAPACITY when model selection is enabled
        ✔ should handle HTTP 429 error with INSUFFICIENT_MODEL_CAPACITY when model selection is disabled
      IAM client error handling
        ✔ should handle HTTP 500 error with specific message when model selection is enabled
        ✔ should handle HTTP 429 error with INSUFFICIENT_MODEL_CAPACITY when model selection is disabled

  DocumentContext
    ✔ handles other languages correctly
    documentContextExtractor.extractEditorState
      ✔ extracts editor state for range selection
      ✔ extracts editor state for collapsed position

  QChatTriggerContext - Inline Chat Extra Context
    ✔ should add extra context to document text for inline chat
    ✔ should not modify document text when extra context is empty
    ✔ should not modify document text when amazonQServiceManager is not available
    ✔ should handle whitespace-only extra context

  QChatTriggerContext
    ✔ returns null if text document is not defined in params
    ✔ returns null if text document is not found
    ✔ passes default cursor state if no cursor is found
    ✔ includes cursor state from the parameters and text document if found
    ✔ should not extract project context when workspace context is disabled

  getExtendedCodeBlockRange
    ✔ able to extend a code block range up to the character limit
    ✔ able to extend a code block range correctly if character limit is an odd number
    ✔ does not extend beyond the lower document bound
    ✔ does not extend beyond the upper document bound
    ✔ trims text if already exceeds character limit

  QChatServer
    ✔ should initialize ChatSessionManagementService with AmazonQTokenServiceManager instance
    ✔ dispose should dispose all chat session services
    ✔ calls the corresponding controller when tabAdd notification is received
    ✔ calls the corresponding controller when tabRemove notification is received
    ✔ calls the corresponding controller when endChat request is received
    ✔ calls the corresponding controller when chatPrompt request is received
    ✔ calls the corresponding controller when inlineChatPrompt request is received

  TelemetryController
    ✔ able to set and get activeTabId
    ✔ able to set and get conversationId for a tab id
    ✔ able to remove conversation id by tab id from the map
    ✔ handles enter focus client telemetry
    ✔ handles exit focus client telemetry
    ✔ does not handle unknown client telemetry
    ✔ does not emit metrics if conversation id is not present
    ✔ emits metrics only if conversation id for active tab is present
    enqueueCodeDiffEntry
      ✔ should enqueue a code diff entry with single line insertion
      ✔ should enqueue a code diff entry with multi-line insertion
      ✔ should handle empty lines in multi-line code insertion
      ✔ should not enqueue a code diff entry if code is falsy
      ✔ should not enqueue a code diff entry if cursorPosition is falsy
      ✔ should not enqueue when required parameters are missing

  relevantTextDocuments
    ✔ converts empty array to empty array
    ✔ combines chunks from same file and sorts by startLine
    ✔ handles chunks without startLine
    ✔ handles unknown programming language
    ✔ filters out empty content
    ✔ truncates relative file path if too long
    ✔ handles multiple files

  QConfigurationServerToken
    ✔ calls all list methods when aws.q is requested
    ✔ only calls listAvailableCustomizations when aws.q.customizations is requested
    ✔ only calls listAvailableProfiles when aws.q.developerProfiles is requested
    ✔ uses listAllAvailableCustomizationsWithMetadata when feature flag is enabled
    ✔ uses listAvailableCustomizations when feature flag is disabled
    ✔ uses listAvailableCustomizations when developer profiles are disabled
    ✔ uses listAllAvailableCustomizationsWithMetadata for customizations section when feature flag is enabled

  ServerConfigurationProvider
    ✔ calls corresponding API when listAvailableCustomizations is invoked
    ✔ does not use listAvailableProfiles handler when developer profiles is disabled
    ✔ uses listAvailableProfiles handler when developer profiles is enabled
    ✔ records error code when listAvailableProfiles throws throttling error
    listAvailableCustomizationsForProfileAndRegion
      ✔ fetches customizations for specified region and profile
      ✔ throws an error when the API call fails
    listAllAvailableCustomizationsWithMetadata
      ✔ fetches customizations for each profile and adds metadata
      ✔ add profile information and isDefault flag to true even for a profile with 0 customizations
      ✔ uses provided profiles instead of fetching them
      ✔ continues processing if fetching customizations for one profile fails - expected to return the default even for case where fetch fails
      ✔ handles cancellation token

  Auto Trigger
    Get Trigger Type
      ✔ returns SpecialCharacters trigger after brackets with newline
      ✔ returns SpecialCharacters trigger after parenthesis
      ✔ returns Classifier trigger after regular typing
      ✔ returns Enter trigger after newline with some indentation
      ✔ returns Classifier trigger for empty file
    getAutoTriggerType
      ✔ should return undefined for multi-line changes
      ✔ should return undefined for empty changes
      ✔ should return "Enter" for newline changes
      ✔ should return undefined for tab changes
      ✔ should return "SpecialCharacters" for special character changes
      ✔ should return "Classifier" for single character changes
      ✔ should return undefined for single line reformat
      ✔ should return undefined for multi-character non-special changes
      ✔ should return undefined for multi-line input
    Right Context should trigger validation
      ✔ should not trigger when there is immediate right context in VSCode
      ✔ should not trigger when right context starts with space
      ✔ should trigger when right context is just space

  editPredictionAutoTrigger
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
[EditPredictionAutoTriggerTest] Testing no recent edit scenario
[EditPredictionAutoTriggerTest] Result: { shouldTrigger: false }
    ✔ should not trigger when there is no recent edit
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
    ✔ should not trigger when there is no non-empty suffix
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
    ✔ should trigger when cursor is after keyword
    using test scenarios from constants
      java language scenarios
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when after if keyword
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when inside empty block
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when after assignment operator
      python language scenarios
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when after if keyword
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when inside empty block
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when after assignment operator
      javascript language scenarios
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when after if keyword
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when inside empty block
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
        ✔ should trigger when after assignment operator
    edit tracking scenarios
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
      ✔ should detect edit: Recent edit in the same line
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
      ✔ should not detect edit: No recent edit in the line
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
      ✔ should not detect edit: Edit is too old
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
      ✔ should not detect edit: Edit in a different document
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
      ✔ should correctly detect edits with the simplified implementation
    combined trigger conditions
[EditPredictionAutoTriggerTest] Setting up test environment
[EditPredictionAutoTriggerTest] Test environment setup complete
      ✔ should trigger when multiple conditions are true

  EditPredictionConfigManager
    ✔ getInstance should return the same instance
    ✔ getConfig should return default config initially
    ✔ getConfig should return a copy of the config
    ✔ updateConfig should update the config
    ✔ resetToDefaults should reset the config to defaults
    ✔ updateConfig should not affect other instances

  LanguageDetector
    LanguageDetectorFactory
      ✔ should return a Java detector for Java language
      ✔ should return a Python detector for Python language
      ✔ should return a JavaScript detector for JavaScript language
      ✔ should return a JavaScript detector for TypeScript language
      ✔ should return a generic detector for unsupported languages
      ✔ should cache detectors for repeated calls with the same language
      ✔ should be case-insensitive for language names
    BaseLanguageDetector
      ✔ should detect keywords correctly
      ✔ should detect operators and delimiters correctly
      ✔ should detect line beginning correctly
    JavaLanguageDetector
      ✔ should have all Java keywords
      ✔ should have all Java operators and delimiters
    PythonLanguageDetector
      ✔ should have all Python keywords
      ✔ should have all Python operators and delimiters
    JavaScriptLanguageDetector
      ✔ should have all JavaScript keywords
      ✔ should have all JavaScript operators and delimiters

  codeDiffTracker
    ✔ shutdown should flush the queue
    ✔ queue should be flushed after time elapsed threshold is reached
    ✔ queue does not exceed the size
    ✔ shutdown should catch exceptions in report handler

  CodePercentage
    ✔ does not send telemetry without edits
    ✔ emits metrics every 5 minutes while editing
    ✔ emits no metrics without invocations
    ✔ emits separate metrics for different languages
    ✔ emits metrics with customizationArn value
    countTotalTokens
      ✔ counts CodeWhisperer suggestions above threshold when fromCodeWhisperer = true
      ✔ counts single character input when not from CodeWhisperer
      ✔ counts single character input when not from CodeWhisperer
      ✔ counts new line with indentation as 1 character input
      ✔ counts auto closing pair of characters input as 2
      ✔ ignores large inputs when fromCodeWhisperer = false
      ✔ accumulates multiple inputs correctly
      ✔ handles whitespace-only input correctly

  CodeWhispererServer NEP Integration
    NEP Tracker Initialization
      ✔ should initialize all NEP trackers when server is created
    NEP Integration Points
      ✔ should verify editPredictionAutoTrigger is imported and available
      ✔ should verify tracker classes are available
    Server Factory Function
      ✔ should create a server function when called with service manager factory
      ✔ should handle server creation with minimal dependencies

  CodeWhisperer Server
    Recommendations
[EDIT_TRACKER] Initializing RecentEditTracker with config: maxFiles=25, maxStorageSizeKb=10000KB, debounceIntervalMs=2000ms
[REJECTED_EDIT_TRACKER] Initializing with config: maxEntries=50, similarityThreshold=1
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should return recommendations
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should correctly get left and right context
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should truncate left and right context
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should correctly get filename
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should return recommendations when using a different languageId casing
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Unable to load from file:///closed.cs: TypeError: workspace.fs.readFile is not a function
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
textDocument [file:///closed.cs] not found
      ✔ should not return recommendations for a closed file
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should include extra context in recommendation request when extraContext is configured
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
textDocument [file:///hopper.fm] with languageId [flow-matic] not supported
      ✔ should not return recommendations for an unsupported file type
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should return recommendations based on known extension
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
Invoking SendTelemetryEvent:UserTriggerDecisionEvent with:
            "requestId": cwspr-request-id
            "suggestionState": DISCARD
            "acceptedCharacterCount": 0
            "addedCharacterCount": 0
            "deletedCharacterCount": 0
            "streakLength": 0
            "firstCompletionDisplayLatency: 0
            "suggestionType": COMPLETIONS
      ✔ should not show recommendation when the recommendation is equal to right context
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should only show the part of the recommendation that does not overlap with the right context in multiline
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should convert windows newlines to UNIX newlines in request file contents
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should only show the part of the recommendation that does not overlap with the right context
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should show full recommendation when the right context does not match recommendation 
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
Recommendation failure: UNEXPECTED EXCEPTION
      ✔ should return empty recommendations list on failed request
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ returns next token from service
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: true
      ✔ handles partialResultToken in request
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
[INLINE_COMPLETION] Service ready - auth: iam, partial token: true
      ✔ should truncate left and right context in paginated requests
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
      ✔ throws ResponseError with expected message if connection is expired
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
Recommendation failure: Error: The bearer token included in the request is invalid.
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
      ✔ throws ResponseError if error is AmazonQError
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
Recommendation failure: AmazonQError: test
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ invokes IdleWorkspaceManager recordActivityTimestamp
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
      Supplemental Context
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
        ✔ should send supplemental context when using token authentication
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
      Opting out of sending data to CodeWhisperer
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
        ✔ should send opt-out header when the setting is disabled
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=true
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to true
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
        ✔ should not send opt-out header when the setting is enabled after startup
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
        ✔ should send opt-out header if no settings are specificed
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
    Recommendations With References
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should return all recommendations if no settings are specificed
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should not include import statements if no settings are specified
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should include import statements if enabled
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Error in getConfiguration(aws.q): Error: GetConfiguration failed
Error in getConfiguration(aws.codeWhisperer): Error: GetConfiguration failed
Calling getConfiguration(aws.codeWhisperer)
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should filter recommendations with references if GetConfiguration is not handled by the client
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=true
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should return all recommendations if settings are true
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should filter recommendations with references if no code references are allowed by settings
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=true
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should filter recommendations with references if code references are disabled after startup
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=true
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should filter recommendations with references if code references are enabled after startup
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=true
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
Invoking SendTelemetryEvent:UserTriggerDecisionEvent with:
            "requestId": cwspr-request-id
            "suggestionState": DISCARD
            "acceptedCharacterCount": 0
            "addedCharacterCount": 0
            "deletedCharacterCount": 0
            "streakLength": 0
            "firstCompletionDisplayLatency: 0
            "suggestionType": COMPLETIONS
      ✔ should not show references when the right context is equal to suggestion
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=true
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should show references and update range when there is partial overlap on right context
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=true
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
      ✔ should discard reference if it references trimmed content after right-context merge
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
      With session management
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: iam, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, iam)
Invoking SendTelemetryEvent:UserTriggerDecisionEvent with:
            "requestId": cwspr-request-id
            "suggestionState": DISCARD
            "acceptedCharacterCount": 0
            "addedCharacterCount": 0
            "deletedCharacterCount": 0
            "streakLength": 0
            "firstCompletionDisplayLatency: 0
            "suggestionType": COMPLETIONS
        ✔ should close session if code references are disabled and all suggestions had references
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
Amazon Q Inline Suggestion server has been shut down
    With auto-triggers
      ✔ should return recommendations even on a below-threshold auto-trigger position when special characters are present
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should return recommendations on an above-threshold auto-trigger position
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ shoud not return recommendations on a below-threshold auto-trigger position
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
    Log Inline Completion Session Results
      ✔ should deactivate current session when session result for current session is sent
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should not close current session when session result for different session is sent
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should store session result data
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should store session result data with only completion state provided
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
    Telemetry
      ✔ should emit Success ServiceInvocation telemetry on successful response
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should emit Success ServiceInvocation telemetry on successful response with completionType block when first suggestion has new lines
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should emit Failure ServiceInvocation telemetry on failed response
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should emit error with UnknownError reason if error name is not present
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should emit Failure ServiceInvocation telemetry with request metadata on failed response with AWSError error type
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should emit Perceived Latency metric when session result is received
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should not emit Perceived Latency metric when firstCompletionDisplayLatency is absent
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      Connection metadata credentialStartUrl field
        ✔ should attach credentialStartUrl field if available in credentialsProvider
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
        ✔ should send empty credentialStartUrl field if not available in credentialsProvider
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      Emit UserModification event with CodeDiffTracker
        ✔ should enqueue a code diff entry when session results are returned with accepted completion
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
        ✔ should emit telemetryService.emitUserModificationEvent on schedule by CodeDiffTracker
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
    Recommendations session management
      ✔ should cache new session on new request when no session exists
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      - should discard inflight session on new request when cached session is in REQUESTING state on subsequent requests
      ✔ should block inflight session on new request when cached session is in REQUESTING state on subsequent requests
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      - should record all sessions that were created in session log
      ✔ should close new session on new request when service returns empty list
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should discard inflight session if merge right recommendations resulted in list of empty strings
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
    IAM Error Handling
Amazon Q Inline Suggestion server has been initialised
BaseAmazonQServiceManager functionality initialized
Client initialization params: {}
[SERVER] Initialized telemetry-dependent components: CodePercentageTracker, CodeDiffTracker, periodicLogging=false
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
Attached new listener and notified of current config.
Calling getConfiguration(aws.q)
Read configuration customizationArn=undefined
Read configuration optOutTelemetryPreference=OPTIN
Calling getConfiguration(aws.codeWhisperer)
Read сonfiguration includeSuggestionsWithCodeReferences=false
Read configuration shareCodeWhispererContentWithAWS=false
Using customization=undefined
Update shareCodeWhispererContentWithAWS setting on cachedCodewhispererService to false
Notifying did change configuration listeners
Updating configuration of inline complete server.
CodePercentageTracker customizationArn updated to undefined
TelemetryService OptOutPreference updated to OPTIN
[INLINE_COMPLETION] Service ready - auth: token, partial token: false
[INLINE_COMPLETION] API call - generateSuggestions (new session, token)
Recommendation failure: Error: not authorized
      ✔ should handle IAM access denied errors
    getLanguageIdFromUri
      ✔ should return python for notebook cell URIs
      ✔ should return abap for files with ABAP extensions
      ✔ should return empty string for non-ABAP files
      ✔ should return empty string for invalid URIs
      ✔ should log errors when provided with a logging object
      ✔ should handle URIs without extensions
    Dynamic Service Manager Selection
      ✔ should use Token service manager when not using IAM auth
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed
      ✔ should use IAM service manager when using IAM auth
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
[REJECTED_EDIT_TRACKER] Cleared all rejected edits
[REJECTED_EDIT_TRACKER] Disposed

  Merge Right Utils
    ✔ get prefix suffix overlap works as expected
    ✔ get prefix prefix overlap index works as expected
    ✔ should return empty suggestion when right context equals line content 
    ✔ should return empty suggestion when right context equals file content
    ✔ should not handle the case where right context fully matches suggestion but starts with a newline 
    ✔ should return truncated suggestion when right context matches end of the suggestion
    ✔ should trim right-context tabs and whitespaces until first newline
    ✔ should handle different line endings
    ✔ should handle windows line endings for files

  mergeEditSuggestionsWithFileContext
    ✔ should return non-empty suggestion if user input matches prefix of the suggestion
    ✔ should return non-empty suggestion if user input contains extra white space prefix
    ✔ should return empty suggestion if user input contains a deletion
    ✔ should return empty suggestion if user input contains a line break
    ✔ should return non-empty suggestion if user input matches a part of the suggestion

  CodeWhispererSession
    constructor()
      ✔ should create a new session with the correct initial values
    activate()
      ✔ should set session state to ACTIVE if not already CLOSED
      ✔ should not change session state if already CLOSED
      ✔ should not change session state if session in DISCARD state
    close()
      ✔ should set session state to CLOSED
      ✔ should record closeTime
      ✔ should not update closeTime for CLOSED session
      ✔ should set suggestions states to Discard for stored suggestions without state
      ✔ should not rewrite suggestions states to Discard for stored suggestions states
    discard()
      ✔ should set session state to DISCARD
      ✔ should record closeTime
      ✔ should not update closeTime for DISCARD session
      ✔ should override suggestions states to Discard for stored suggestions
    setClientResultData()
      ✔ should set results of session from client with all relevant data available
      ✔ should set results of session from client with only completion states available
      ✔ should set correct suggestion states based on client-side results state data with 1 Accepted suggestion
      ✔ should set correct suggestion states based on client-side results state data with 0 Accepted suggestions
      ✔ should ignore setting suggestion states for not cached suggestion ids
    getAggregatedUserTriggerDecision()
      ✔ should return Accept trigger decision
      ✔ should return Reject trigger decision
      ✔ should return Discard trigger decision
      ✔ should return Empty trigger decision
      ✔ should return Empty trigger decision for empty list of suggestions
      ✔ should return Discard trigger decision when all suggestions state is Filter
      ✔ should return undefined if session is not CLOSED
      ✔ should return Discard after session is closed with not complete session results
      ✔ should return Discard when session is in DISCARD state

  SessionManager
    createSession()
      ✔ should create a new session and set it as the current session
      ✔ should not deactivate previous session when creating a new session
      ✔ should set previous active session trigger decision from discarded REQUESTING session
      ✔ should not set previous active session trigger decision to new session object if it is not closed
    discard()
      ✔ should set session to DISCARD state
    getPreviousSession()
      ✔ should return the last session in the sessions log
      ✔ should record not-closed and not-active sessions in the sessions log
      ✔ should return undefined if the sessions log is empty
    getSessionById()
      ✔ should return the session with the associated ID
      ✔ should return undefined if no session has the associated ID
    getSuggestionState()
      ✔ should return the state of suggestion with the associated ID
      ✔ should return the undefined if no suggestion has the associated ID

  RecentEditTracker
    processEdit
      ✔ should store snapshot in memory
      ✔ should not add new snapshot within debounce interval
      ✔ should add new snapshot after debounce interval
      ✔ should not process non-file URIs
      ✔ should delete snapshot after maxAgeMs
    enforceMemoryLimits
      ✔ should remove oldest snapshots when storage size exceeds limit
    getFileSnapshots
      ✔ should return empty array for non-existent file
      ✔ should return snapshots for existing file
    getTrackedFiles
      ✔ should return empty array when no files are tracked
      ✔ should return array of tracked file paths
    getTotalSnapshotCount
      ✔ should return 0 when no snapshots exist
      ✔ should return total count of snapshots across all files
    getSnapshotContent
      ✔ should retrieve snapshot content
    document handling methods
      ✔ should track document on open
      ✔ should untrack document on close
      ✔ should process edit on document change
    generateEditBasedContext
      ✔ should return empty context when no active document
      ✔ should return empty context when no snapshots for active document
      - should generate context from snapshots
    dispose
      ✔ should clear all collections and reset storage size
    hasRecentEditInLine
      ✔ should return false when no snapshots exist for the document
      ✔ should return false when snapshots exist but are older than the threshold
      ✔ should return true when line has been edited within the threshold
      ✔ should return true when different line was edited in lineRange
      ✔ should return false when different line was edited beyond lineRange
      ✔ should respect custom time threshold

  CursorTracker
    ✔ trackPosition should store cursor position with timestamp
    ✔ getLastPositionTimestamp should return undefined for unknown position
    ✔ getLastPositionTimestamp should return timestamp for tracked position
    ✔ hasPositionChanged should return true for unknown position
    ✔ hasPositionChanged should return false for position that has not changed within duration
    ✔ hasPositionChanged should return true for position that has changed after duration
    ✔ clearHistory should remove all tracked positions for a document
    ✔ getTrackedDocuments should return all tracked document URIs
    ✔ should limit history size to MAX_HISTORY_SIZE
    ✔ should remove cursor positions after they exceed the maximum age
    ✔ should remove document from tracking when all positions are aged out

  RejectedEditTracker Integration
    Edit Rejection Flow
      ✔ should record rejected edits when user rejects an edit prediction
      ✔ should filter out similar edits in future suggestions
      ✔ should only filter edits for the correct document
      ✔ should handle multiple rejected edits

  RejectedEditTracker
    recordRejectedEdit
      ✔ should add rejected edit to the beginning of the array
      ✔ should enforce max entries limit
    isSimilarToRejected
      ✔ should return false when no rejected edits exist
      ✔ should return false when document URI does not match
      ✔ should return true for identical content
      ✔ should return true for similar content above threshold
      ✔ should return false for content below similarity threshold
      ✔ should normalize content before comparison
      ✔ should handle different line endings
      ✔ should handle common indentation
    normalizeEditContent
      ✔ should remove diff line numbers
      ✔ should normalize line endings
      ✔ should remove leading and trailing empty lines
      ✔ should remove common indentation
      ✔ should handle mixed indentation correctly
    calculateSimilarity
      ✔ should return 1.0 for identical strings
      ✔ should return 0.0 when one string is empty
      ✔ should calculate similarity based on Levenshtein distance
    clear
      ✔ should remove all rejected edits
    getCount
      ✔ should return the number of rejected edits
    dispose
      ✔ should clear all rejected edits
    getInstance
      ✔ should return the same instance when called multiple times
      ✔ should use provided config

  StreakTracker
    getInstance
      ✔ should return the same instance (singleton)
      ✔ should create new instance after reset
    getAndUpdateStreakLength
      ✔ should return -1 for undefined input
      ✔ should return -1 and increment streak on acceptance
      ✔ should return -1 for rejection with zero streak
      ✔ should return previous streak on rejection after acceptances
      ✔ should handle acceptance after rejection
    cross-instance consistency
      ✔ should maintain state across getInstance calls

  Telemetry
    User Trigger Decision telemetry
      ✔ should report user trigger decision only once for a session
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
      Case 1. Session is processed by server without sending results
        ✔ should send Empty user desicion when Codewhisperer returned list of empty suggestions and close session
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should send Empty User Decision when Codewhisperer returned empty list of suggestions
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should send Discard User Decision when all suggestions are filtered out by includeSuggestionsWithCodeReferences setting filter
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should send Discard User Decision when all suggestions are discarded after right context merge
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
      Case 2. Session returns recommendation to client and is closed by LogInlineCompletionSessionResults notification
        ✔ should emit User Decision event for active completion session when session results are received
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should emit User Decision event with correct typeaheadLength value when session results are received
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should not emit User Decision event after second trigger is received
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should not emit User Decision event when session results received for session that does not exist
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should emit Accept User Decision event for current active completion session when session results are received with accepted suggestion
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should emit Reject User Decision event for current active completion session when session results are received without accepted suggestion
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should send Discard User Decision when all suggestions have Discard state
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should set codewhispererTimeSinceLastDocumentChange as difference between 2 any document changes
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
      Case 3. Active session is closed by subsequent trigger
        ✔ should close ACTIVE session and emit Discard user trigger decision event on Manual trigger
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should close ACTIVE session and emit Discard user trigger decision event on Auto trigger
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should attach previous session trigger decision
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
        ✔ should set correct values for past trigger result fields
[EDIT_TRACKER] Disposing RecentEditTracker...
[EDIT_TRACKER] Final state: 0 files, 0 snapshots, 0KB used
[EDIT_TRACKER] RecentEditTracker disposed
      Case 4. Inflight session is closed by subsequent completion request
        - should emit Discard user trigger decision event when REQUESTING session is closed before becoming ACTIVE

  ArtifactManager - createTransformationPreferencesContent
    Full DatabaseSettings scenario
      ✔ should generate transformation preferences with complete DatabaseSettings
      ✔ should preserve all tool configurations from DatabaseSettings
    DmsArn only scenario
      ✔ should generate transformation preferences with minimal DMS tool configuration
      ✔ should include metadata with valid timestamp
    No database modernization scenario
      ✔ should generate transformation preferences without DatabaseModernization when neither DmsArn nor DatabaseSettings provided
      ✔ should generate empty transformation settings when no transformations are enabled
    JSON structure validation
      ✔ should generate JSON structure matching expected format for full configuration
      ✔ should generate valid JSON for minimal DmsArn-only configuration
      ✔ should generate valid JSON for no database modernization scenario
      ✔ should serialize and deserialize without data loss
    Edge cases and error handling
      ✔ should handle null DatabaseSettings gracefully
      ✔ should handle empty DatabaseSettings Tools array
      ✔ should handle undefined properties in DatabaseSettings gracefully

  ArtifactManager - processPrivatePackages
    ✔ should do nothing when PackageReferences is undefined
    ✔ should process private package when all conditions are met
    ✔ should not process when package is not private
    ✔ should not process when package ID is not in reference path
    ✔ should mark as third party package but not copy when paths are null

  Test Converter
    Test get CW StartTransformResponse
      ✔ should return the correct StarTransformResponse object

  Test Transform handler 
    test upload artifact
      ✔ call upload method correctly with stream
      ✔ handles upload failure correctly
    Test transform create presign url and upload
      ✔ returns upload id correctly with streaming
      ✔ should throw error if uploadArtifactToS3Async fails
    Test cancel transform job
      ✔ should cancel transform
      ✔ should throw error if cancellation fails
    StreamingClient
      ✔ should create a new streaming client
    createStreamingClient
      ✔ should create a new streaming client with correct configurations
    Test get transformJob
      ✔ should get transform
    Test get transformJob for failed case
      ✔ should get transform for failed case
    Test get transform plan
      ✔ should get transform plan
    Test extract all tntries to a path
      ✔ should create directories and extract files successfully
      ✔ should handle ENOENT errors gracefully
      ✔ should throw non-ENOENT errors
      ✔ should handle nested directory structures
      ✔ should handle empty entry list
      ✔ should handle files without directories
      ✔ should handle mixed content with files and directories
      ✔ should handle invalid entry paths

  getTransformationErrorCode
    ✔ should return NONE when transformationJob is undefined
    ✔ should return NONE when status is not a failure state
    ✔ should return QUOTA_EXCEEDED when status is FAILED and reason contains "would exceed your remaining quota"
    ✔ should return UNKNOWN_ERROR when status is FAILED but reason does not match any patterns
    ✔ should return UNKNOWN_ERROR when status is FAILED and reason is undefined
    ✔ should return UNKNOWN_ERROR when status is STOPPED
    ✔ should return UNKNOWN_ERROR when status is REJECTED

  Test validation functionality
    ✔ should return true when selectedProjectPath is a valid csproj
    ✔ should return false when selectedProjectPath is not a valid csproj
    ✔ should return true when selectedProjectPath is a valid sln
    ✔ should return false when selectedProjectPath is not a valid sln

  Test CsharpDependencyGraph
    Test getPayloadSizeLimitInBytes
      ✔ should return correct payload size
    Test getProjectName
      ✔ should return current folder name for given file path outside workspace folder
      ✔ should return correct project name for given forlder path within workspace folder
    Test getProjectPath
      ✔ should not find workspace folder path for given path
      ✔ should return project name for within project file
    Test getReadableSizeLimit
      ✔ should return size 1 MB
    Test exceedsSizeLimit
      ✔ should not exceed size limit
      ✔ should exceed size limit
    Test createNamespaceFilenameMapper
      ✔ should create the map with namespace to filepath mapping
      ✔ should create empty map
    Test searchDependency
      ✔ should return source file only for no dependencies
      ✔ should return source file with its dependecies' file path
      ✔ should return source file with its dependecies' until it reaches to payload size limit
    Test traverseDir
      ✔ should return without traversing due to payload size limit reached
      ✔ should traverse through files until it reaches payload size limit
      ✔ should traverse through all files
    Test getDependencies
      ✔ should return file paths for given imports
      ✔ should return empty list
    Test readImports
      ✔ should return list of imports 
      ✔ should return empty list
    Test generateTruncation
---------------------------------------|---------|----------|---------|---------|-------------------
File                                   | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
---------------------------------------|---------|----------|---------|---------|-------------------
All files                              |   60.65 |    73.33 |   58.51 |   60.65 |                   
 src                                   |       0 |        0 |       0 |       0 |                   
  index.ts                             |       0 |        0 |       0 |       0 | 1-7               
 src/client/sigv4                      |     100 |      100 |     100 |     100 |                   
  codewhisperer.ts                     |     100 |      100 |     100 |     100 |                   
 src/client/streamingClient            |     100 |      100 |   66.66 |     100 |                   
  codewhispererStreamingClient.ts      |     100 |      100 |   66.66 |     100 |                   
 src/client/token                      |   93.87 |       50 |   66.66 |   93.87 |                   
  codewhisperer.ts                     |   93.87 |       50 |   66.66 |   93.87 | 44-46             
 src/language-server                   |       0 |        0 |       0 |       0 |                   
  types.ts                             |       0 |        0 |       0 |       0 | 1-22              
 src/language-server/agenticChat       |   59.24 |    68.94 |   65.21 |   59.24 |                   
  agenticChatController.ts             |    52.1 |    60.32 |   51.78 |    52.1 | ...4688,4702-4703 
  agenticChatEventParser.ts            |   95.25 |       76 |     100 |   95.25 | ...46-147,149-154 
  agenticChatResultStream.ts           |   65.18 |    82.85 |      75 |   65.18 | ...26-227,238-239 
  errors.ts                            |   95.48 |     91.3 |     100 |   95.48 | ...54,60-62,73-75 
  qAgenticChatServer.ts                |   70.18 |    91.66 |      40 |   70.18 | ...45,249,253,257 
  tabBarController.ts                  |   90.05 |    87.27 |    92.3 |   90.05 | ...76-289,345-351 
  textFormatting.ts                    |   73.33 |       80 |   66.66 |   73.33 | 17-20,27-30       
 ...guage-server/agenticChat/constants |   99.37 |      100 |       0 |   99.37 |                   
  constants.ts                         |    98.9 |      100 |       0 |    98.9 | 20                
  modelSelection.ts                    |     100 |      100 |     100 |     100 |                   
  toolConstants.ts                     |     100 |      100 |     100 |     100 |                   
 ...anguage-server/agenticChat/context |   83.94 |    78.04 |   81.63 |   83.94 |                   
  additionalContextProvider.ts         |   76.99 |    76.87 |      70 |   76.99 | ...90,752-761,807 
  agenticChatTriggerContext.ts         |   88.65 |    71.42 |     100 |   88.65 | ...99-505,516-518 
  contextCommandsProvider.ts           |      85 |    66.66 |   77.77 |      85 | ...87-200,208-215 
  contextUtils.ts                      |   96.13 |    97.77 |   85.71 |   96.13 | 95-104            
 src/language-server/agenticChat/tools |   50.14 |    70.13 |      71 |   50.14 |                   
  codeSearch.ts                        |    90.2 |    60.52 |     100 |    90.2 | ...,93-96,118-119 
  executeBash.ts                       |   64.94 |       55 |   66.66 |   64.94 | ...90-831,834-872 
  fileSearch.ts                        |   62.19 |    85.71 |   55.55 |   62.19 | ...08-159,162-164 
  fsRead.ts                            |   69.67 |    93.33 |   88.88 |   69.67 | 75-76,87-121      
  fsReplace.ts                         |   55.75 |    86.66 |    62.5 |   55.75 | ...35-136,138-139 
  fsWrite.ts                           |   59.19 |      100 |      70 |   59.19 | ...,98-99,119-162 
  grepSearch.ts                        |   68.26 |    71.05 |      75 |   68.26 | ...14-215,260-311 
  listDirectory.ts                     |   49.21 |    78.57 |    62.5 |   49.21 | ...9,73-75,91-127 
  lspApplyWorkspaceEdit.ts             |       0 |        0 |       0 |       0 | 1-163             
  lspGetDocuments.ts                   |       0 |        0 |       0 |       0 | 1-52              
  lspReadDocumentContents.ts           |       0 |        0 |       0 |       0 | 1-134             
  toolServer.ts                        |       0 |        0 |       0 |       0 | 1-437             
  toolShared.ts                        |   95.03 |    92.85 |     100 |   95.03 | 85-89,94-95       
 ...ge-server/agenticChat/tools/chatDb |   79.45 |    77.58 |   78.49 |   79.45 |                   
  chatDb.ts                            |   72.73 |    73.24 |   71.92 |   72.73 | ...1024,1093-1094 
  chatHistoryMaintainer.ts             |   83.74 |    78.04 |   85.71 |   83.74 | ...37-338,348-350 
  util.ts                              |    91.9 |    85.54 |    90.9 |    91.9 | ...51,453,476-478 
 ...guage-server/agenticChat/tools/mcp |   60.58 |    60.48 |   55.95 |   60.58 |                   
  chokidarFileWatcher.ts               |     100 |     90.9 |     100 |     100 | 40                
  mcpEventHandler.ts                   |   38.33 |    52.43 |   33.33 |   38.33 | ...1512,1521-1523 
  mcpManager.ts                        |   73.69 |    60.55 |   78.04 |   73.69 | ...1429,1436-1440 
  mcpOauthClient.ts                    |   34.29 |    57.89 |   44.44 |   34.29 | ...61-463,475-483 
  mcpTool.ts                           |   78.33 |    66.66 |   57.14 |   78.33 | 19-24,27-28,31-35 
  mcpTypes.ts                          |    61.8 |       50 |       0 |    61.8 | ...81-183,187-190 
  mcpUtils.ts                          |   79.05 |     61.3 |      95 |   79.05 | ...1118,1155-1183 
  profileStatusMonitor.ts              |   76.07 |    69.23 |    92.3 |   76.07 | ...47-148,157-158 
 ...er/agenticChat/tools/qCodeAnalysis |   94.94 |     84.4 |   94.91 |   94.94 |                   
  codeReview.ts                        |   89.44 |    75.86 |   91.66 |   89.44 | ...-931,1000-1001 
  codeReviewConstants.ts               |     100 |      100 |     100 |     100 |                   
  codeReviewErrors.ts                  |     100 |      100 |     100 |     100 |                   
  codeReviewSchemas.ts                 |     100 |      100 |     100 |     100 |                   
  codeReviewTypes.ts                   |     100 |      100 |     100 |     100 |                   
  codeReviewUtils.ts                   |   98.21 |    97.14 |   95.45 |   98.21 | 186-188,318-322   
  displayFindings.ts                   |   98.79 |    81.81 |     100 |   98.79 | 148-149           
  displayFindingsConstants.ts          |     100 |      100 |     100 |     100 |                   
  displayFindingsSchemas.ts            |     100 |      100 |     100 |     100 |                   
  displayFindingsTypes.ts              |     100 |      100 |     100 |     100 |                   
  displayFindingsUtils.ts              |     100 |      100 |     100 |     100 |                   
 src/language-server/agenticChat/utils |   97.98 |    83.33 |     100 |   97.98 |                   
  commandParser.ts                     |   95.91 |     82.6 |     100 |   95.91 | 58-59,72-73       
  fileModificationMetrics.ts           |     100 |       75 |     100 |     100 | 15,29,40-42       
  pathValidation.ts                    |     100 |      100 |     100 |     100 |                   
 src/language-server/chat              |   83.55 |    80.32 |   82.14 |   83.55 |                   
  chatController.ts                    |    76.4 |    69.14 |   57.14 |    76.4 | ...83-588,683-728 
  chatEventParser.ts                   |   98.25 |       85 |     100 |   98.25 | 62-64             
  chatSessionManagementService.ts      |     100 |      100 |     100 |     100 |                   
  chatSessionService.ts                |   80.62 |    84.37 |   88.46 |   80.62 | ...79-285,306-310 
  constants.ts                         |     100 |      100 |     100 |     100 |                   
  qChatServer.ts                       |   84.21 |      100 |     100 |   84.21 | ...10,114,118,122 
  quickActions.ts                      |     100 |      100 |     100 |     100 |                   
  utils.ts                             |   90.21 |     82.6 |     100 |   90.21 | 60-61,63-64,85-89 
 ...e-server/chat/agents/docGeneration |       0 |        0 |       0 |       0 |                   
  constants.ts                         |       0 |        0 |       0 |       0 | 1-162             
  errors.ts                            |       0 |        0 |       0 |       0 | 1-64              
 ...language-server/chat/agents/shared |       0 |        0 |       0 |       0 |                   
  i18n.ts                              |       0 |        0 |       0 |       0 | 1-3               
  types.ts                             |       0 |        0 |       0 |       0 | 1-63              
 src/language-server/chat/contexts     |   92.81 |    68.62 |     100 |   92.81 |                   
  documentContext.ts                   |   93.42 |    55.55 |     100 |   93.42 | 45-47,60-61       
  triggerContext.ts                    |   89.32 |    69.69 |     100 |   89.32 | ...69,171,173-174 
  utils.ts                             |     100 |    77.77 |     100 |     100 | 70-77             
 src/language-server/chat/telemetry    |   72.25 |    66.66 |   75.75 |   72.25 |                   
  chatTelemetryController.ts           |   67.86 |    64.51 |      75 |   67.86 | ...09-610,619-638 
  clientTelemetry.ts                   |     100 |      100 |     100 |     100 |                   
 src/language-server/chat/tools        |     100 |    85.71 |     100 |     100 |                   
  relevantTextDocuments.ts             |     100 |    85.71 |     100 |     100 | 44-46             
 src/language-server/configuration     |   91.61 |    78.72 |     100 |   91.61 |                   
  qConfigurationServer.ts              |   91.61 |    78.72 |     100 |   91.61 | ...01-302,326-327 
 src/language-server/inline-completion |   70.38 |    79.14 |   77.94 |   70.38 |                   
  codeDiffTracker.ts                   |   98.35 |    93.75 |     100 |   98.35 | 111-112,168       
  codePercentage.ts                    |   97.04 |      100 |   93.33 |   97.04 | 141-145           
  codeWhispererServer.ts               |   86.62 |    73.88 |   91.66 |   86.62 | ...80-890,935-936 
  constants.ts                         |     100 |      100 |     100 |     100 |                   
  diffUtils.ts                         |   50.15 |    70.58 |   28.57 |   50.15 | ...81-299,304-323 
  documentChangedListener.ts           |   89.47 |      100 |      75 |   89.47 | 7-8               
  editCompletionHandler.ts             |   19.81 |       40 |   28.57 |   19.81 | ...27-417,420-443 
  mergeRightUtils.ts                   |    90.9 |     82.6 |     100 |    90.9 | ...,66-67,107-112 
  telemetry.ts                         |   84.31 |    77.41 |   83.33 |   84.31 | ...53-154,165-166 
  trigger.ts                           |    22.8 |      100 |       0 |    22.8 | 14-57             
 ...ver/inline-completion/auto-trigger |   96.54 |    87.61 |     100 |   96.54 |                   
  autoTrigger.ts                       |      91 |    84.14 |     100 |      91 | ...55,268,270,272 
  editPredictionAutoTrigger.ts         |     100 |      100 |     100 |     100 |                   
  editPredictionConfig.ts              |     100 |      100 |     100 |     100 |                   
  languageDetector.ts                  |   99.47 |       95 |     100 |   99.47 | 68-69             
 ...e-server/inline-completion/session |   95.14 |    95.23 |   93.33 |   95.14 |                   
  sessionManager.ts                    |   95.14 |    95.23 |   93.33 |   95.14 | ...72-283,316-317 
 ...e-server/inline-completion/tracker |    90.8 |    87.05 |   98.21 |    90.8 |                   
  codeEditTracker.ts                   |   84.57 |    73.01 |   95.83 |   84.57 | ...98-601,611-612 
  cursorTracker.ts                     |   99.14 |    96.77 |     100 |   99.14 | 203-204           
  rejectedEditTracker.ts               |     100 |      100 |     100 |     100 |                   
  streakTracker.ts                     |     100 |      100 |     100 |     100 |                   
 ...anguage-server/localProjectContext |       0 |        0 |       0 |       0 |                   
  localProjectContextServer.ts         |       0 |        0 |       0 |       0 | 1-193             
 src/language-server/netTransform      |   36.44 |    86.15 |   28.81 |   36.44 |                   
  artifactManager.ts                   |   37.82 |      100 |   15.38 |   37.82 | ...91-408,411-422 
  converter.ts                         |   42.85 |      100 |   33.33 |   42.85 | 17-19,21-61       
  metrics.ts                           |       0 |        0 |       0 |       0 | 1-322             
  models.ts                            |     100 |      100 |     100 |     100 |                   
  netTransformServer.ts                |       0 |        0 |       0 |       0 | 1-213             
  transformHandler.ts                  |   44.98 |    76.66 |   42.85 |   44.98 | ...69-473,476-488 
  validation.ts                        |    52.8 |      100 |   42.85 |    52.8 | ...61,64-71,73-83 
 ...uage-server/netTransform/resources |     100 |      100 |     100 |     100 |                   
  SupportedProjects.ts                 |     100 |      100 |     100 |     100 |                   
 ...language-server/netTransform/tests |     100 |      100 |     100 |     100 |                   
  mockData.ts                          |     100 |      100 |     100 |     100 |                   
 src/language-server/paidTier          |      50 |      100 |       0 |      50 |                   
  paidTier.ts                          |      50 |      100 |       0 |      50 | 11-20             
 src/language-server/securityScan      |    7.63 |        0 |       0 |    7.63 |                   
  codeWhispererSecurityScanServer.ts   |       0 |        0 |       0 |       0 | 1-276             
  constants.ts                         |     100 |      100 |     100 |     100 |                   
  securityScanDiagnosticsProvider.ts   |       0 |        0 |       0 |       0 | 1-141             
  securityScanHandler.ts               |   22.02 |        0 |       0 |   22.02 | ...72-219,224-226 
  types.ts                             |       0 |        0 |       0 |       0 | 1-71              
 ...erver/securityScan/dependencyGraph |   77.23 |    86.88 |   72.41 |   77.23 |                   
  commonUtil.ts                        |     100 |      100 |     100 |     100 |                   
  constants.ts                         |     100 |      100 |     100 |     100 |                   
  csharpDependencyGraph.ts             |   87.64 |    89.47 |     100 |   87.64 | 35,50,56-72,89-90 
  dependencyGraph.ts                   |   79.08 |       85 |   58.82 |   79.08 | ...17-221,227-228 
  dependencyGraphFactory.ts            |       0 |        0 |       0 |       0 | 1-31              
 src/language-server/workspaceContext  |   17.46 |       50 |    6.29 |   17.46 |                   
  IdleWorkspaceManager.ts              |   76.19 |    42.85 |      60 |   76.19 | 22-27,29-30,34-35 
  artifactManager.ts                   |   17.42 |        0 |       0 |   17.42 | ...53-713,716-722 
  client.ts                            |   16.04 |        0 |       0 |   16.04 | ...59-163,166-186 
  fileUploadJobManager.ts              |   19.51 |       50 |       0 |   19.51 | ...31-157,160-163 
  javaManager.ts                       |   20.43 |      100 |       0 |   20.43 | ...09-914,917-919 
  util.ts                              |   45.54 |       60 |   27.27 |   45.54 | ...70,73-74,77-78 
  workspaceContextServer.ts            |    5.95 |      100 |       0 |    5.95 | 32-35,38-554      
  workspaceFolderManager.ts            |   15.39 |    66.66 |    5.55 |   15.39 | ...68-796,799-824 
 ...server/workspaceContext/dependency |   22.39 |    33.33 |       5 |   22.39 |                   
  dependencyDiscoverer.ts              |    17.2 |        0 |       0 |    17.2 | ...01-207,210-214 
  dependencyEventBundler.ts            |   32.43 |       50 |   11.11 |   32.43 | ...92-102,105-110 
 ...ntext/dependency/dependencyHandler |   27.58 |        0 |       0 |   27.58 |                   
  DependencyWatcher.ts                 |   27.53 |      100 |       0 |   27.53 | ...57,60-61,64-68 
  JSTSDependencyHandler.ts             |   23.75 |        0 |       0 |   23.75 | ...22-232,235-239 
  JavaDependencyHandler.ts             |   28.04 |        0 |       0 |   28.04 | ...71-181,184-188 
  LanguageDependencyHandler.ts         |   33.06 |        0 |       0 |   33.06 | ...62-363,366-371 
  LanguageDependencyHandlerFactory.ts  |   25.86 |      100 |       0 |   25.86 | 15-57             
  PythonDependencyHandler.ts           |   23.79 |        0 |       0 |   23.79 | ...70-281,284-289 
 src/shared                            |    61.8 |    60.79 |   45.66 |    61.8 |                   
  activeUserTracker.ts                 |   74.86 |    52.38 |     100 |   74.86 | ...50-152,172-186 
  amazonQServer.ts                     |   27.53 |      100 |     100 |   27.53 | 17-66             
  codeWhispererService.ts              |   46.96 |      100 |   18.75 |   46.96 | ...56-792,800-840 
  constants.ts                         |     100 |      100 |     100 |     100 |                   
  imageVerification.ts                 |   38.79 |      100 |       0 |   38.79 | ...0,56-91,94-116 
  languageDetection.ts                 |   90.49 |    70.83 |   71.42 |   90.49 | ...92-304,319-326 
  localProjectContextController.ts     |   28.47 |       80 |   22.72 |   28.47 | ...92-448,451-452 
  proxy-server.ts                      |       0 |        0 |       0 |       0 | 1-29              
  streamingClientService.ts            |   84.43 |       70 |      60 |   84.43 | ...49-159,178-186 
  telemetryUtils.ts                    |   80.86 |    34.61 |   83.33 |   80.86 | ...,78,80,113-115 
  testUtils.ts                         |   97.06 |      100 |      80 |   97.06 | 311-320           
  userWrittenCodeTracker.ts            |   34.41 |       50 |    6.66 |   34.41 | ...35-144,147-153 
  utils.ts                             |   62.42 |    56.73 |   78.94 |   62.42 | ...91-608,638-640 
 src/shared/amazonQServiceManager      |   73.44 |    61.53 |   69.07 |   73.44 |                   
  AmazonQIAMServiceManager.ts          |   81.18 |     87.5 |   58.33 |   81.18 | ...82-83,86-90,99 
  AmazonQTokenServiceManager.ts        |   53.61 |    57.44 |   65.71 |   53.61 | ...66,669-670,674 
  BaseAmazonQServiceManager.ts         |   93.65 |    73.33 |    90.9 |   93.65 | ...70-171,179-182 
  configurationUtils.ts                |   92.94 |    51.61 |   88.88 |   92.94 | ...20-122,226-227 
  errors.ts                            |   77.65 |      100 |      50 |   77.65 | ...65,70-72,91-93 
  qDeveloperProfiles.ts                |   86.63 |    52.94 |     100 |   86.63 | ...61,167,215-217 
  testUtils.ts                         |   78.57 |    71.42 |   69.23 |   78.57 | ...57,161,165-166 
 src/shared/models                     |   32.95 |       50 |       0 |   32.95 |                   
  constants.ts                         |     100 |      100 |     100 |     100 |                   
  model.ts                             |       0 |        0 |       0 |       0 | 1-59              
 src/shared/supplementalContextUtil    |   25.58 |      100 |    6.52 |   25.58 |                   
  codeParsingUtil.ts                   |   51.47 |      100 |       0 |   51.47 | 35-54,56-68       
  crossFileContextUtil.ts              |   22.49 |      100 |       0 |   22.49 | ...10-483,485-489 
  focalFileResolution.ts               |   24.31 |      100 |   16.66 |   24.31 | ...05-428,431-439 
  rankBm25.ts                          |   30.71 |      100 |       0 |   30.71 | ...19-129,131-140 
  supplementalContextUtil.ts           |   19.26 |      100 |       0 |   19.26 | ...85-221,223-244 
  unitTestIntentDetection.ts           |   33.33 |      100 |   14.28 |   33.33 | ...85-124,127-146 
 src/shared/telemetry                  |   86.65 |    79.54 |    60.6 |   86.65 |                   
  metric.ts                            |     100 |    88.88 |     100 |     100 | 35                
  telemetryService.ts                  |   76.14 |    77.33 |      50 |   76.14 | ...46-649,656-678 
  types.ts                             |     100 |      100 |     100 |     100 |                   
---------------------------------------|---------|----------|---------|---------|-------------------

> @aws/lsp-identity@0.0.1 test:coverage
> npm run package && npm run test-unit:coverage


> @aws/lsp-identity@0.0.1 package
> npm run compile && npm run copy


> @aws/lsp-identity@0.0.1 compile
> tsc --build --verbose

9:18:41 PM - Projects in this build: 
    * tsconfig.json

9:18:41 PM - Project 'tsconfig.json' is up to date because newest input 'src/sso/utils.ts' is older than output 'tsconfig.tsbuildinfo'


> @aws/lsp-identity@0.0.1 copy
> copyfiles --error --flat ./src/sso/authorizationCodePkce/resources/* ./out/sso/authorizationCodePkce/resources/


> @aws/lsp-identity@0.0.1 test-unit:coverage
> npm run compile && c8 mocha "./out/**/*.test.js"


> @aws/lsp-identity@0.0.1 compile
> tsc --build --verbose

9:18:42 PM - Projects in this build: 
    * tsconfig.json

9:18:42 PM - Project 'tsconfig.json' is up to date because newest input 'src/sso/utils.ts' is older than output 'tsconfig.tsbuildinfo'



  DuckTyper
    ✔ false on no value provided
    ✔ handles no rules as expected
    ✔ true on containing requireProperty
    ✔ false on not containing requireProperty
    ✔ true on containing optionalProperty
    ✔ true on not containing optionalProperty
    ✔ false on containing disallowProperty
    ✔ true on not containing disallowProperty
    ✔ false on extra properties with onlyDefined
    ✔ works on multiple rules and complex objects

  IdentityService
    getSsoToken
      ✔ Can login with AWS Builder ID.
      ✔ Can login with IAM Identity Center.
      ✔ Can login with different auth flows.
      ✔ Throws when auth flow is invalid.
      ✔ Can login with cache error if loginOnInvalidToken is true.
      ✔ Returns existing SSO token.
      ✔ Throws when no SSO token cached and loginOnInvalidToken is false.
      ✔ Throws when SSO retrieval throws and loginOnInvalidToken is false.
    invalidateSsoToken
      ✔ removeToken removes on valid SSO session name
      ✔ removeToken throws on invalid SSO session name

  ProfileService
    ✔ listProfiles return profiles and sso-sessions
    ✔ listProfiles returns empty arrays when no profiles or sso-sessions
    ✔ updateProfile updates existing profiles and sso-sessions
    ✔ updateProfile creates new profiles and sso-sessions
    ✔ updateProfile throws on no profile
    ✔ updateProfile throws on non-SSO token profile
    ✔ updateProfile throws on no profile name
    ✔ updateProfile throws on no settings
    ✔ updateProfile throws on no sso-session
    ✔ updateProfile throws on no sso-session on profile
    ✔ updateProfile throws when profile cannot be created
    ✔ updateProfile throws on no sso-session name
    ✔ updateProfile throws on no sso-session settings
    ✔ updateProfile throws on no sso-session region
    ✔ updateProfile throws on no sso-session start URL
    ✔ updateProfile throws on sso-session different than name referenced on profile
    ✔ updateProfile throws when sso-session cannot be created
    ✔ updateProfile throws when cannot update shared sso-session

  profileService.DuckTypers
    ✔ profileDuckTypers.eval returns true on valid profiles
    ✔ profileDuckTypers returns false on invalid profiles
    ✔ ssoSessionDuckTyper.eval returns true on valid sso-sessions
    ✔ ssoSessionDuckTyper returns false on invalid sso-sessions

  profileService.functions
    ✔ normalizeParsedIniData changes all key names to lowercase

  SharedConfigProfileStore
    ✔ loads SSO token profiles and sso-sessions, but not services
    ✔ No changes if no profiles nor ssoSessions are provided
    ✔ Removes setting on save if [undefined] is provided.
    ✔ Removes setting on save if [null] is provided.
    ✔ Removes setting on save if [] is provided.
    ✔ Removes setting on save if [   ] is provided.
    ✔ Removes setting on save if [ 
 ] is provided.
    ✔ Throw on save if object is provided for a setting value.
    ✔ Removes profiles and ssoSessions if [undefined] is provided.
    ✔ Removes profiles and ssoSessions if [null] is provided.
    ✔ Removes profiles and ssoSessions if [[object Object]] is provided.
    ✔ Saves if profiles and ssoSessions are provided

  SsoTokenAutoRefresher
    ✔ watch does nothing if SSO token is not loaded from cache.
    ✔ watch does nothing if SSO token is expired.
    ✔ watch schedules refresh in refresh window prior to expiration.
    ✔ watch schedules refresh retry in retry window after last attempt.
    ✔ unwatch does nothing if ssoSessionName is not watched.

  sharedConfig.normalizeParsedIniData
    ✔ Setting names are converted to lowercase

  sharedConfig.saveKnownFiles
    ✔ Invalid lines are commented
    ✔ Adds new settings
    ✔ Updates changed settings
    ✔ Removes deleted settings
    ✔ Stores secret settings in credentials only
    ✔ Adds new sections
    ✔ Renames (effectively add/delete) sections
    ✔ Removes deleted sections
    ✔ Converts setting names to lowercase

  sharedConfig.saveSharedConfigFile
    ✔ New and original file match on unchanged parsedKnownFiles
    ✔ Invalid lines are commented
    ✔ Adds new settings
    ✔ Updates changed settings
    ✔ Removes deleted settings
    ✔ Adds new sections
    ✔ Renames (effectively add/delete) sections
    ✔ Removes deleted sections
    ✔ Comments are preserved
    ✔ Can create new when ~/.aws does not exist
    ✔ Can create new when ~/.aws exists, but file does not exist

  sharedConfig.SectionHeader
    ✔ fromParsedSectionName
    ✔ toParsedSectionName
    toIniSectionName
      ✔ credentials file profile sections are not prefixed with "profile"
      ✔ config file sections are prefixed
      ✔ default profile is not prefixed with "profile" in either file

  sharedConfig.Setting
    ✔ toIniSettingLine

  sharedConfig.unmergeConfigFiles
    ✔ Removes sections deleted from parseKnownFiles from both files
    ✔ Settings deleted from parseKnownFiles sections are removed from sections in both files
    ✔ Secrets are written to credentials file only and removed from config if they exist
    ✔ New non-secret settings are written to config only
    ✔ Existing non-secret settings in credentials are updated there and in config if exists

  authorizationCodePkceFlow
    ✔ Generates a valid authorize URL.
    ✔ Returns a valid SSO token.

  AuthorizationServer
    ✔ Creates a valid CSRF token
    ✔ Creates a valid redirect URI
    ✔ Returns a valid resource request.
    ✔ Returns a 404 on invalid resource request.
    ✔ Returns an authorization code on valid authorization request.
    ✔ Throws an error on an invalid authorization request [error=kaboom].
(node:3289) PromiseRejectionHandledWarning: Promise rejection was handled asynchronously (rejection id: 37)
(Use `node --trace-warnings ...` to show where the warning was created)
    ✔ Throws an error on an invalid authorization request [code=].
(node:3289) PromiseRejectionHandledWarning: Promise rejection was handled asynchronously (rejection id: 38)
    ✔ Throws an error on an invalid authorization request [state=].
(node:3289) PromiseRejectionHandledWarning: Promise rejection was handled asynchronously (rejection id: 39)
    ✔ Throws an error on an invalid authorization request [state=not_it].
(node:3289) PromiseRejectionHandledWarning: Promise rejection was handled asynchronously (rejection id: 40)

  FileSystemSsoCache
    ✔ getSsoClientRegistration returns valid registration
    ✔ getSsoClientRegistration returns undefined when file does not exist
    ✔ getSsoClientRegistration returns undefined on invalid registration
    ✔ setSsoClientRegistration writes new valid registration
    ✔ setSsoClientRegistration writes new valid registration when ~/.aws does not exist
    ✔ setSsoClientRegistration writes updated existing registration
    ✔ setSsoClientRegistration returns without error on invalid registration
    ✔ removeSsoToken deletes a valid token
    ✔ removeSsoToken does nothing on invalid/non-existent token
    ✔ removeToken throws on invalid SSO session name
    ✔ getSsoToken returns valid token
    ✔ getSsoToken returns undefined when file does not exist
    ✔ getSsoToken returns undefined on invalid token
    ✔ setSsoToken writes new valid token
    ✔ setSsoToken writes new valid token when ~/.aws does not exist
    ✔ setSsoToken writes updated existing token
    ✔ setSsoToken returns without error on invalid token

  RefreshingSsoCache
    getSsoClientRegistration
      ✔ Creates a new SSO client registration.
      ✔ Updates an expired SSO client registration.
    getSsoToken
      ✔ Returns nothing on no cached SSO token.
      ✔ Returns refreshed token on expired SSO token.
      ✔ Returns existing SSO token before refresh window (5 minutes before expiration).
      ✔ Returns existing SSO token when refresh attempted recently (within 30 seconds).
      ✔ Throw error when no refreshToken.
      ✔ Returns new SSO token upon refresh.

  deviceCodeFlow
    ✔ Generates a valid authorize URL.
    ✔ Returns a valid SSO token.
    ✔ Cancels if user code is not acknowledged.
    ✔ Cancels if client cancels auth via token.
    ✔ Throws client's error from ShowMessageRequest
    ✔ Throws error if authorization expires
    ✔ Returns a valid SSO Token after waiting for user via AuthorizationPendingException

  utils
    throwOnInvalidClientName
      ✔ Does nothing on valid client names.
      ✔ Throws on invalid client name [undefined].
      ✔ Throws on invalid client name [null].
      ✔ Throws on invalid client name [].
      ✔ Throws on invalid client name [  ].
      ✔ Throws on invalid client name [ 
 ].
    throwOnInvalidClientRegistration
      ✔ Does nothing on valid client registrations.
      ✔ Throws on invalid client registrations [null].
      ✔ Throws on invalid client registrations [{"clientId":null,"clientSecret":"my-client-secret","expiresAt":"2025-09-16T21:18:43.381Z","issuedAt":"2025-09-16T21:18:43.381Z","scopes":["sso:account:access"]}].
      ✔ Throws on invalid client registrations [{"clientId":"my-client-id","clientSecret":null,"expiresAt":"2025-09-16T21:18:43.381Z","issuedAt":"2025-09-16T21:18:43.381Z","scopes":["sso:account:access"]}].
      ✔ Throws on invalid client registrations [{"clientId":"my-client-id","clientSecret":"my-client-secret","expiresAt":null,"issuedAt":"2025-09-16T21:18:43.381Z","scopes":["sso:account:access"]}].
      ✔ Throws on invalid client registrations [{"clientId":"my-client-id","clientSecret":"my-client-secret","expiresAt":"2025-09-16T21:18:43.381Z","issuedAt":"2025-09-16T21:18:43.381Z","scopes":null}].
    throwOnInvalidSsoSession
      ✔ Does nothing on valid SSO sessions.
      ✔ Throws on invalid SSO sessions [null].
      ✔ Throws on invalid SSO sessions [{"settings":{"sso_region":"us-east-1","sso_registration_scopes":["sso:account:access"],"sso_start_url":"https://nowhere"}}].
      ✔ Throws on invalid SSO sessions [{"name":"my-sso-session"}].
      ✔ Throws on invalid SSO sessions [{"name":"my-sso-session","settings":{"sso_registration_scopes":["sso:account:access"],"sso_start_url":"https://nowhere"}}].
      ✔ Throws on invalid SSO sessions [{"name":"my-sso-session","settings":{"sso_region":"us-east-1","sso_registration_scopes":["sso:account:access"]}}].
      ✔ Throws on invalid SSO sessions [{"name":"my-sso-session","settings":{"sso_region":"us-east-1"}}].
      ✔ Throws on invalid SSO sessions [{"name":"my-sso-session","settings":{"sso_region":"us-east-1","sso_registration_scopes":[]}}].
    UpdateSsoTokenFromCreateToken
      ✔ Creates a new SSO token from the create token response.
      ✔ Updates an existing SSO token from the create token response.
      ✔ Throws on invalid create token response [null].
      ✔ Throws on invalid create token response [{"accessToken":"","expiresIn":60}].
      ✔ Throws on invalid create token response [{"accessToken":"my-access-token","expiresIn":null}].


  160 passing (241ms)

-------------------------------|---------|----------|---------|---------|---------------------------
File                           | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s         
-------------------------------|---------|----------|---------|---------|---------------------------
All files                      |   87.35 |    88.64 |   95.19 |   87.35 |                           
 src                           |   96.82 |       90 |   85.71 |   96.82 |                           
  duckTyper.ts                 |   98.38 |    94.73 |     100 |   98.38 | 56                        
  index.ts                     |       0 |        0 |       0 |       0 | 1                         
 src/language-server           |    63.8 |       84 |   83.33 |    63.8 |                           
  identityServer.ts            |       0 |        0 |       0 |       0 | 1-129                     
  identityService.ts           |    92.8 |    83.33 |     100 |    92.8 | ...22-226,235-237,241-243 
  ssoTokenAutoRefresher.ts     |    71.9 |     92.3 |      75 |    71.9 | 73-76,91-120              
 src/language-server/profiles  |    94.4 |    85.71 |     100 |    94.4 |                           
  profileService.ts            |   96.44 |    89.74 |     100 |   96.44 | ...23,152,162-163,168-169 
  sharedConfigProfileStore.ts  |   92.52 |    82.22 |     100 |   92.52 | ...74-175,198-199,206-207 
 src/sharedConfig              |   97.45 |    92.79 |     100 |   97.45 |                           
  index.ts                     |     100 |      100 |     100 |     100 |                           
  saveKnownFiles.ts            |   96.36 |    88.88 |     100 |   96.36 | 51-52                     
  saveSharedConfigFile.ts      |   96.49 |    88.46 |     100 |   96.49 | ...42-143,153-154,202-203 
  types.ts                     |     100 |      100 |     100 |     100 |                           
  unmergeConfigFiles.ts        |   98.11 |    94.11 |     100 |   98.11 | 90-91                     
 src/sso                       |   87.21 |    96.87 |   83.33 |   87.21 |                           
  constants.ts                 |     100 |      100 |     100 |     100 |                           
  index.ts                     |     100 |      100 |     100 |     100 |                           
  utils.ts                     |   86.61 |    96.87 |   83.33 |   86.61 | 20-36                     
 src/sso/authorizationCodePkce |    92.8 |    76.47 |     100 |    92.8 |                           
  authorizationCodePkceFlow.ts |     100 |    66.66 |     100 |     100 | 61                        
  authorizationServer.ts       |   90.37 |    77.41 |     100 |   90.37 | ...35-137,140-142,175-176 
  index.ts                     |     100 |      100 |     100 |     100 |                           
 src/sso/cache                 |   90.21 |    95.45 |   94.11 |   90.21 |                           
  fileSystemSsoCache.ts        |   93.45 |       96 |     100 |   93.45 | 31-32,59,69-72            
  index.ts                     |     100 |      100 |     100 |     100 |                           
  refreshingSsoCache.ts        |   85.64 |    94.73 |   83.33 |   85.64 | ...,95-99,154-156,171-183 
  ssoCache.ts                  |     100 |      100 |     100 |     100 |                           
 src/sso/deviceCode            |   94.37 |    83.33 |     100 |   94.37 |                           
  deviceCodeFlow.ts            |   94.37 |    83.33 |     100 |   94.37 | ...07-108,114-115,140-141 
-------------------------------|---------|----------|---------|---------|---------------------------

> @aws/lsp-json@0.1.19 test:coverage
> c8 ts-mocha -b "./src/**/*.test.ts"



  Json Server
    ✔ should validate when change document
    ✔ should validate when open document
    ✔ should complete
    ✔ should hover
    ✔ should format


  5 passing (27ms)

-------------------------|---------|----------|---------|---------|---------------------------------
File                     | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s               
-------------------------|---------|----------|---------|---------|---------------------------------
All files                |   70.33 |    64.28 |      35 |   70.33 |                                 
 src                     |       0 |        0 |       0 |       0 |                                 
  index.ts               |       0 |        0 |       0 |       0 | 1-2                             
 src/language-server     |   82.71 |    69.23 |      70 |   82.71 |                                 
  jsonServer.ts          |   76.28 |    69.23 |      70 |   76.28 | ...0-82,116-118,141-143,146-155 
  testUtils.ts           |     100 |      100 |     100 |     100 |                                 
 src/language-service    |   40.47 |      100 |       0 |   40.47 |                                 
  jsonLanguageService.ts |   40.47 |      100 |       0 |   40.47 | ...4-57,60-61,64-71,74-79,81-84 
-------------------------|---------|----------|---------|---------|---------------------------------

> @aws/lsp-notification@0.0.1 test:coverage
> npm run test-unit:coverage


> @aws/lsp-notification@0.0.1 test-unit:coverage
> npm run compile && c8 mocha "./out/**/*.test.js"


> @aws/lsp-notification@0.0.1 compile
> tsc --build --verbose

9:18:45 PM - Projects in this build: 
    * tsconfig.json

9:18:45 PM - Project 'tsconfig.json' is up to date because newest input 'src/notifications/notification.ts' is older than output 'tsconfig.tsbuildinfo'



  
    ✔ 

  
    ✔ 

  
    ✔ 

  
    ✔ 

  
    ✔ 


  5 passing (12ms)

------------------------------|---------|----------|---------|---------|-------------------
File                          | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
------------------------------|---------|----------|---------|---------|-------------------
All files                     |       0 |        0 |       0 |       0 |                   
 src                          |       0 |        0 |       0 |       0 |                   
  index.ts                    |       0 |        0 |       0 |       0 | 1                 
 src/language-server          |       0 |        0 |       0 |       0 |                   
  notificationServer.ts       |       0 |        0 |       0 |       0 | 1-104             
  notificationService.ts      |       0 |        0 |       0 |       0 | 1-23              
 src/notifications            |       0 |        0 |       0 |       0 |                   
  fetcher.ts                  |       0 |        0 |       0 |       0 | 1-3               
  notification.ts             |       0 |        0 |       0 |       0 | 1                 
 src/notifications/metadata   |       0 |        0 |       0 |       0 |                   
  filesystemMetadataStore.ts  |       0 |        0 |       0 |       0 | 1-3               
  metadataFilteringFetcher.ts |       0 |        0 |       0 |       0 | 1-9               
  metadataStore.ts            |       0 |        0 |       0 |       0 | 1                 
 src/notifications/toolkits   |       0 |        0 |       0 |       0 |                   
  criteriaFilteringFetcher.ts |       0 |        0 |       0 |       0 | 1-9               
  s3Fetcher.ts                |       0 |        0 |       0 |       0 | 1-7               
------------------------------|---------|----------|---------|---------|-------------------

> @aws/hello-world-lsp@0.0.1 test:coverage
> c8 ts-mocha -b "./src/**/*.test.ts"



  Hello World Server
    Custom Commands
      ✔ should get executed when registered
      ✔ should get not be executed when not registered


  2 passing (9ms)

-----------------------|---------|----------|---------|---------|------------------------------
File                   | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s            
-----------------------|---------|----------|---------|---------|------------------------------
All files              |   45.66 |     87.5 |      50 |   45.66 |                              
 src                   |       0 |        0 |       0 |       0 |                              
  index.ts             |       0 |        0 |       0 |       0 | 1                            
 src/language-server   |   45.93 |      100 |   57.14 |   45.93 |                              
  helloWorldServer.ts  |   44.84 |      100 |      60 |   44.84 | 40-61,76-117,124-126,130-153 
  helloWorldService.ts |   71.42 |      100 |      50 |   71.42 | 5-6                          
-----------------------|---------|----------|---------|---------|------------------------------
Error: Process completed with exit code 1.
0s
0s
0s
0s
fix: update the node version to 24 · aws/language-servers@3538360```

## Analysis
- Issue: Node.js upgrade from 18/20 to 24
- Failing tests related to: mock-fs library causing "Maximum call stack size exceeded" on Windows
- Root cause: mock-fs v5.2.0 incompatible with Node.js 24 on Windows (path handling issue)
- Mac works fine, Windows fails - platform-specific bug in mock-fs

## Fix Applied
- Upgraded mock-fs from v5.2.0 to v5.5.0 in core/aws-lsp-core/package.json
- Tests pass on Mac with Node 24 + mock-fs v5.5.0
- Need Windows CI to verify fix 

## Windows Error Logs
Paste the Windows test logs below:

```
Skip to content
Navigation Menu
aws
language-servers

Type / to search
Code
Issues
12
Pull requests
99
Actions
Projects
Wiki
Security
Insights
Back to pull request #2244
fix: update the node version to 24 #6555
Jobs
Run details
Test (Windows)
failed 2 weeks ago in 6m 47s
binding
1/100
1s
7s
14s
2m 7s
4m 14s
Run npm run test

> @amzn/monorepo-language-servers@1.0.0 test
> npm run compile && npm run test --workspaces --if-present


> @amzn/monorepo-language-servers@1.0.0 precompile
> npm run precompile --workspaces --if-present && npm run compile:core


> @amzn/monorepo-language-servers@1.0.0 compile:core
> npm run compile --workspace=core --if-present && npm run build --workspace=core --if-present


> @aws/lsp-core@0.0.15 compile
> tsc --build


> @amzn/monorepo-language-servers@1.0.0 compile
> tsc --build --verbose && npm run compile:core && npm run compile:servers && npm run compile:rest

8:24:55 PM - Projects in this build: 
    * client/vscode/tsconfig.json
    * chat-client/tsconfig.json
    * core/aws-lsp-core/tsconfig.json
    * server/aws-lsp-json/tsconfig.json
    * server/aws-lsp-yaml/tsconfig.json
    * server/aws-lsp-buildspec/tsconfig.json
    * server/aws-lsp-cloudformation/tsconfig.json
    * server/aws-lsp-codewhisperer/tsconfig.json
    * server/aws-lsp-identity/tsconfig.json
    * server/aws-lsp-notification/tsconfig.json
    * server/hello-world-lsp/tsconfig.json
    * server/aws-lsp-s3/tsconfig.json
    * server/aws-lsp-partiql/tsconfig.json
    * app/aws-lsp-buildspec-runtimes/tsconfig.json
    * app/aws-lsp-cloudformation-runtimes/tsconfig.json
    * app/aws-lsp-codewhisperer-runtimes/tsconfig.json
    * app/aws-lsp-identity-runtimes/tsconfig.json
    * app/aws-lsp-s3-runtimes/tsconfig.json
    * app/hello-world-lsp-runtimes/tsconfig.json
    * app/aws-lsp-json-runtimes/tsconfig.json
    * app/aws-lsp-yaml-runtimes/tsconfig.json
    * app/aws-lsp-yaml-json-webworker/tsconfig.json
    * app/aws-lsp-partiql-runtimes/tsconfig.json
    * integration-tests/q-agentic-chat-server/tsconfig.json
    * tsconfig.json

8:24:55 PM - Project 'client/vscode/tsconfig.json' is out of date because output file 'client/vscode/tsconfig.tsbuildinfo' does not exist

8:24:55 PM - Building project 'D:/a/language-servers/language-servers/client/vscode/tsconfig.json'...

8:24:59 PM - Project 'chat-client/tsconfig.json' is out of date because output file 'chat-client/tsconfig.tsbuildinfo' does not exist

8:24:59 PM - Building project 'D:/a/language-servers/language-servers/chat-client/tsconfig.json'...

8:25:01 PM - Project 'core/aws-lsp-core/tsconfig.json' is up to date because newest input 'core/aws-lsp-core/src/index.ts' is older than output 'core/aws-lsp-core/tsconfig.tsbuildinfo'

8:25:01 PM - Project 'server/aws-lsp-json/tsconfig.json' is out of date because output file 'server/aws-lsp-json/tsconfig.tsbuildinfo' does not exist

8:25:01 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-json/tsconfig.json'...

8:25:01 PM - Project 'server/aws-lsp-yaml/tsconfig.json' is out of date because output file 'server/aws-lsp-yaml/tsconfig.tsbuildinfo' does not exist

8:25:01 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-yaml/tsconfig.json'...

8:25:01 PM - Project 'server/aws-lsp-buildspec/tsconfig.json' is out of date because output file 'server/aws-lsp-buildspec/tsconfig.tsbuildinfo' does not exist

8:25:01 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-buildspec/tsconfig.json'...

8:25:01 PM - Project 'server/aws-lsp-cloudformation/tsconfig.json' is out of date because output file 'server/aws-lsp-cloudformation/tsconfig.tsbuildinfo' does not exist

8:25:01 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-cloudformation/tsconfig.json'...

8:25:01 PM - Project 'server/aws-lsp-codewhisperer/tsconfig.json' is out of date because output file 'server/aws-lsp-codewhisperer/tsconfig.tsbuildinfo' does not exist

8:25:01 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-codewhisperer/tsconfig.json'...

8:25:08 PM - Project 'server/aws-lsp-identity/tsconfig.json' is out of date because output file 'server/aws-lsp-identity/tsconfig.tsbuildinfo' does not exist

8:25:08 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-identity/tsconfig.json'...

8:25:09 PM - Project 'server/aws-lsp-notification/tsconfig.json' is out of date because output file 'server/aws-lsp-notification/tsconfig.tsbuildinfo' does not exist

8:25:09 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-notification/tsconfig.json'...

8:25:09 PM - Project 'server/hello-world-lsp/tsconfig.json' is out of date because output file 'server/hello-world-lsp/tsconfig.tsbuildinfo' does not exist

8:25:09 PM - Building project 'D:/a/language-servers/language-servers/server/hello-world-lsp/tsconfig.json'...

8:25:09 PM - Project 'server/aws-lsp-s3/tsconfig.json' is out of date because output file 'server/aws-lsp-s3/tsconfig.tsbuildinfo' does not exist

8:25:09 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-s3/tsconfig.json'...

8:25:10 PM - Project 'server/aws-lsp-partiql/tsconfig.json' is out of date because output file 'server/aws-lsp-partiql/tsconfig.tsbuildinfo' does not exist

8:25:10 PM - Building project 'D:/a/language-servers/language-servers/server/aws-lsp-partiql/tsconfig.json'...

8:25:12 PM - Project 'app/aws-lsp-buildspec-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-buildspec-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:12 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-buildspec-runtimes/tsconfig.json'...

8:25:12 PM - Project 'app/aws-lsp-cloudformation-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-cloudformation-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:12 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-cloudformation-runtimes/tsconfig.json'...

8:25:12 PM - Project 'app/aws-lsp-codewhisperer-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-codewhisperer-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:12 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-codewhisperer-runtimes/tsconfig.json'...

8:25:12 PM - Project 'app/aws-lsp-identity-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-identity-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:12 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-identity-runtimes/tsconfig.json'...

8:25:12 PM - Project 'app/aws-lsp-s3-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-s3-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:12 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-s3-runtimes/tsconfig.json'...

8:25:12 PM - Project 'app/hello-world-lsp-runtimes/tsconfig.json' is out of date because output file 'app/hello-world-lsp-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:12 PM - Building project 'D:/a/language-servers/language-servers/app/hello-world-lsp-runtimes/tsconfig.json'...

8:25:12 PM - Project 'app/aws-lsp-json-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-json-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:12 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-json-runtimes/tsconfig.json'...

8:25:12 PM - Project 'app/aws-lsp-yaml-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-yaml-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:12 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-yaml-runtimes/tsconfig.json'...

8:25:13 PM - Project 'app/aws-lsp-yaml-json-webworker/tsconfig.json' is out of date because output file 'app/aws-lsp-yaml-json-webworker/dist/tsconfig.tsbuildinfo' does not exist

8:25:13 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-yaml-json-webworker/tsconfig.json'...

8:25:13 PM - Project 'app/aws-lsp-partiql-runtimes/tsconfig.json' is out of date because output file 'app/aws-lsp-partiql-runtimes/tsconfig.tsbuildinfo' does not exist

8:25:13 PM - Building project 'D:/a/language-servers/language-servers/app/aws-lsp-partiql-runtimes/tsconfig.json'...

8:25:13 PM - Project 'integration-tests/q-agentic-chat-server/tsconfig.json' is out of date because output file 'integration-tests/q-agentic-chat-server/tsconfig.tsbuildinfo' does not exist

8:25:13 PM - Building project 'D:/a/language-servers/language-servers/integration-tests/q-agentic-chat-server/tsconfig.json'...


> @amzn/monorepo-language-servers@1.0.0 compile:core
> npm run compile --workspace=core --if-present && npm run build --workspace=core --if-present


> @aws/lsp-core@0.0.15 compile
> tsc --build


> @amzn/monorepo-language-servers@1.0.0 compile:servers
> npm run compile --workspace=server --if-present


> @aws/lsp-antlr4@0.1.19 compile
> tsc --build


> @aws/lsp-buildspec@0.0.1 compile
> tsc --build


> @aws/lsp-cloudformation@0.0.1 compile
> tsc --build


> @aws/lsp-codewhisperer@0.0.79 compile
> tsc --build


> @aws/lsp-codewhisperer@0.0.79 postcompile
> npm run copyServiceClient


> @aws/lsp-codewhisperer@0.0.79 copyServiceClient
> copyfiles -u 1 --error ./src/client/sigv4/*.json out && copyfiles -u 1 --error ./src/client/token/*.json out


> @aws/lsp-identity@0.0.1 compile
> tsc --build --verbose

8:25:22 PM - Projects in this build: 
    * tsconfig.json

8:25:22 PM - Project 'tsconfig.json' is up to date because newest input 'src/duckTyper.test.ts' is older than output 'tsconfig.tsbuildinfo'


> @aws/lsp-json@0.1.19 compile
> tsc --build


> @aws/lsp-notification@0.0.1 compile
> tsc --build --verbose

8:25:22 PM - Projects in this build: 
    * tsconfig.json

8:25:22 PM - Project 'tsconfig.json' is up to date because newest input 'src/index.ts' is older than output 'tsconfig.tsbuildinfo'


> @aws/lsp-partiql@0.0.18 compile
> tsc --build


> @aws/lsp-partiql@0.0.18 postcompile
> npm run copy-empty-binary


> @aws/lsp-partiql@0.0.18 copy-empty-binary
> tsx build-scripts/create-empty-wasm-file.mts


> @aws/lsp-s3@0.0.1 compile
> tsc --build


> @aws/lsp-yaml@0.1.19 compile
> tsc --build


> @amzn/device-sso-auth-lsp@0.0.1 compile
> tsc --build


> @aws/hello-world-lsp@0.0.1 compile
> tsc --build


> @amzn/monorepo-language-servers@1.0.0 compile:rest
> npm run compile --workspace app --workspace client --workspace chat-client --if-present


> @aws/lsp-antlr4-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-buildspec-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-cloudformation-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-codewhisperer-runtimes@0.0.1 compile
> tsc --build && copyfiles -f src/version.json out/


> @aws/lsp-identity-runtimes@0.1.0 compile
> tsc --build


> @aws/lsp-json-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-notification-runtimes@0.1.0 compile
> tsc --build


> @aws/lsp-partiql-runtimes@0.0.1 compile
> npm run compile:tsc && npm run compile:webpack


> @aws/lsp-partiql-runtimes@0.0.1 compile:tsc
> tsc --build


> @aws/lsp-partiql-runtimes@0.0.1 compile:webpack
> webpack

assets by path *.js 6.9 MiB
  asset aws-lsp-partiql-binary.js 6.88 MiB [emitted] (name: aws-lsp-partiql-binary)
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-067dc8.js 6.05 KiB [emitted]
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-5c3a2a.js 5.86 KiB [emitted]
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-d22e4f.js 5.65 KiB [emitted]
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-f60812.js 3.31 KiB [emitted]
  asset node_modules_opentelemetry_resources_build_esm_detectors_platform_node_machine-id_getMachineI-e747da.js 2.81 KiB [emitted]
assets by path *.node 409 KiB
  asset registry.node 204 KiB [emitted] (auxiliary name: aws-lsp-partiql-binary)
  asset crypt32-x64.node 115 KiB [emitted] (auxiliary name: aws-lsp-partiql-binary)
  asset crypt32-ia32.node 90.5 KiB [emitted] (auxiliary name: aws-lsp-partiql-binary)
asset ../out/index.d.ts 11 bytes [compared for emit]
orphan modules 1.56 MiB [orphan] 296 modules
runtime modules 2.47 KiB 9 modules
modules by path ../../node_modules/ 4.35 MiB
  cacheable modules 4.35 MiB
    javascript modules 4.35 MiB 1027 modules
    json modules 3.07 KiB 2 modules
  ../../node_modules/vscode-languageserver-types/lib/umd/ sync 160 bytes [built] [code generated]
  ../../node_modules/win-ca/lib/ sync ^\.\/crypt32\-.*$ 244 bytes [built] [code generated]
modules by path ./ 1.39 MiB
  modules by path ./node_modules/@aws/lsp-partiql/out/server/ 39 KiB 9 modules
  modules by path ./node_modules/@aws/lsp-partiql/out/antlr-generated/*.js 733 KiB 2 modules
  modules by path ./node_modules/@aws/lsp-partiql/out/tree-sitter-wasm/*.js 646 KiB 2 modules
  ./src/index.ts 344 bytes [built] [code generated]
  ./node_modules/@aws/lsp-partiql/out/index.js 362 bytes [built] [code generated]
+ 41 modules

WARNING in ../../node_modules/vscode-languageserver-types/lib/umd/main.js 3:24-31
Critical dependency: require function is used in a way in which dependencies cannot be statically extracted
 @ ../../node_modules/vscode-languageserver-protocol/lib/common/api.js 23:13-51
 @ ../../node_modules/vscode-languageserver-protocol/lib/node/main.js 24:13-37
 @ ../../node_modules/@aws/language-server-runtimes/protocol/editCompletions.js 4:41-82
 @ ../../node_modules/@aws/language-server-runtimes/runtimes/standalone.js 70:26-64
 @ ./src/index.ts 3:21-81

1 warning has detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

webpack 5.99.9 compiled with 1 warning in 7209 ms

> @aws/lsp-s3-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-yaml-json-webworker@0.0.1 compile
> tsc --build


> @aws/lsp-yaml-runtimes@0.0.1 compile
> tsc --build


> @aws/hello-world-lsp-runtimes@0.0.1 compile
> tsc --build


> awsdocuments-ls-client@0.1.0 compile
> tsc -b && npm run compile:chat-client


> awsdocuments-ls-client@0.1.0 compile:chat-client
> npm run compile --prefix ../../chat-client && shx cp -R ../../chat-client/build .


> @aws/chat-client@0.1.35 compile
> tsc --build && npm run package


> @aws/chat-client@0.1.35 package
> webpack

assets by path ../out/client/ 22.4 KiB
  assets by path ../out/client/*.ts 16.3 KiB 13 assets
  assets by path ../out/client/texts/*.ts 2.41 KiB 6 assets
  assets by path ../out/client/features/*.ts 1.96 KiB 4 assets
  assets by path ../out/client/tabs/*.ts 1.75 KiB
    asset ../out/client/tabs/tabFactory.d.ts 1.73 KiB [compared for emit]
    asset ../out/client/tabs/tabFactory.test.d.ts 11 bytes [compared for emit]
assets by path ../out/contracts/*.ts 8.11 KiB
  asset ../out/contracts/chatClientAdapter.d.ts 3.73 KiB [compared for emit]
  asset ../out/contracts/serverContracts.d.ts 3.24 KiB [compared for emit]
  asset ../out/contracts/telemetry.d.ts 1.13 KiB [compared for emit]
asset amazonq-ui.js 6.76 MiB [emitted] (name: main)
asset ../out/index.d.ts 129 bytes [compared for emit]
asset ../out/test/jsDomInjector.d.ts 45 bytes [compared for emit]
runtime modules 670 bytes 3 modules
modules by path ./src/ 160 KiB
  modules by path ./src/client/ 158 KiB 14 modules
  modules by path ./src/contracts/*.ts 1.75 KiB
    ./src/contracts/serverContracts.ts 144 bytes [built] [code generated]
    ./src/contracts/telemetry.ts 1.61 KiB [built] [code generated]
  ./src/index.ts 261 bytes [built] [code generated]
modules by path ../node_modules/ 2.45 MiB
  modules by path ../node_modules/@aws/language-server-runtimes-types/out/*.js 8.89 KiB 8 modules
  modules by path ../node_modules/@aws/chat-client-ui-types/out/*.js 2.12 KiB
    ../node_modules/@aws/chat-client-ui-types/out/index.js 839 bytes [built] [code generated]
    ../node_modules/@aws/chat-client-ui-types/out/uiContracts.js 1.3 KiB [built] [code generated]
  ../node_modules/@aws/mynah-ui/dist/main.js 2.37 MiB [built] [code generated]
  ../node_modules/vscode-languageserver-types/lib/esm/main.js 75.6 KiB [built] [code generated]
webpack 5.99.9 compiled successfully in 3984 ms

> @aws/chat-client@0.1.35 compile
> tsc --build && npm run package


> @aws/chat-client@0.1.35 package
> webpack

assets by path ../out/client/ 22.4 KiB
  assets by path ../out/client/*.ts 16.3 KiB 13 assets
  assets by path ../out/client/texts/*.ts 2.41 KiB 6 assets
  assets by path ../out/client/features/*.ts 1.96 KiB 4 assets
  assets by path ../out/client/tabs/*.ts 1.75 KiB
    asset ../out/client/tabs/tabFactory.d.ts 1.73 KiB [compared for emit]
    asset ../out/client/tabs/tabFactory.test.d.ts 11 bytes [compared for emit]
assets by path ../out/contracts/*.ts 8.11 KiB
  asset ../out/contracts/chatClientAdapter.d.ts 3.73 KiB [compared for emit]
  asset ../out/contracts/serverContracts.d.ts 3.24 KiB [compared for emit]
  asset ../out/contracts/telemetry.d.ts 1.13 KiB [compared for emit]
asset amazonq-ui.js 6.76 MiB [compared for emit] (name: main)
asset ../out/index.d.ts 129 bytes [compared for emit]
asset ../out/test/jsDomInjector.d.ts 45 bytes [compared for emit]
runtime modules 670 bytes 3 modules
modules by path ./src/ 160 KiB
  modules by path ./src/client/ 158 KiB 14 modules
  modules by path ./src/contracts/*.ts 1.75 KiB
    ./src/contracts/serverContracts.ts 144 bytes [built] [code generated]
    ./src/contracts/telemetry.ts 1.61 KiB [built] [code generated]
  ./src/index.ts 261 bytes [built] [code generated]
modules by path ../node_modules/ 2.45 MiB
  modules by path ../node_modules/@aws/language-server-runtimes-types/out/*.js 8.89 KiB 8 modules
  modules by path ../node_modules/@aws/chat-client-ui-types/out/*.js 2.12 KiB
    ../node_modules/@aws/chat-client-ui-types/out/index.js 839 bytes [built] [code generated]
    ../node_modules/@aws/chat-client-ui-types/out/uiContracts.js 1.3 KiB [built] [code generated]
  ../node_modules/@aws/mynah-ui/dist/main.js 2.37 MiB [built] [code generated]
  ../node_modules/vscode-languageserver-types/lib/esm/main.js 75.6 KiB [built] [code generated]
webpack 5.99.9 compiled successfully in 3939 ms

> @aws/lsp-antlr4-runtimes@0.0.1 test
> npm run test-integ


> @aws/lsp-antlr4-runtimes@0.0.1 test-integ
> npm run package && mocha --timeout 5000 "./out/**/*Integ.test.js" --retries 2


> @aws/lsp-antlr4-runtimes@0.0.1 package
> npm run compile && npm run webpack


> @aws/lsp-antlr4-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-antlr4-runtimes@0.0.1 webpack
> webpack

assets by status 19.1 MiB [emitted]
  assets by path *.js 18.7 MiB
    asset aws-lsp-antlr4-standalone-with-customization.js 9.33 MiB [emitted] (name: aws-lsp-antlr4-standalone-with-customization)
    + 6 assets
  assets by path *.node 409 KiB
    asset registry.node 204 KiB [emitted] (auxiliary name: aws-lsp-antlr4-standalone, aws-lsp-antlr4-standalone-with-customization)
    + 2 assets
assets by status 449 KiB [compared for emit]
  assets by path ../out/antlr-generated/*.ts 449 KiB
    asset ../out/antlr-generated/PostgreSQLParser.d.ts 425 KiB [compared for emit]
    + 3 assets
  assets by path ../out/*.ts 22 bytes
    asset ../out/serverWithCustomization.d.ts 11 bytes [compared for emit]
    asset ../out/serverWithoutCustomization.d.ts 11 bytes [compared for emit]
  asset ../out/tests/antlr4ServerInteg.test.d.ts 11 bytes [compared for emit]
orphan modules 1.56 MiB [orphan] 296 modules
runtime modules 4.97 KiB 18 modules
modules by path ../../node_modules/ 4.28 MiB
  cacheable modules 4.28 MiB 1028 modules
  + 2 modules
modules by path ./src/ 3.82 MiB
  modules by path ./src/antlr-generated/*.ts 3.82 MiB 4 modules
  modules by path ./src/*.ts 1.6 KiB 2 modules
modules by path ../../core/aws-lsp-core/out/ 3.66 KiB 5 modules
modules by path ../../server/aws-lsp-antlr4/out/ 11.5 KiB
  modules by path ../../server/aws-lsp-antlr4/out/language-service/ 7.37 KiB 2 modules
  ../../server/aws-lsp-antlr4/out/index.js 571 bytes [built] [code generated]
  ../../server/aws-lsp-antlr4/out/language-server/server.js 3.55 KiB [built] [code generated]
+ 41 modules

WARNING in ../../node_modules/vscode-languageserver-types/lib/umd/main.js 3:24-31
Critical dependency: require function is used in a way in which dependencies cannot be statically extracted
 @ ../../node_modules/vscode-languageserver-protocol/lib/common/api.js 23:13-51
 @ ../../node_modules/vscode-languageserver-protocol/lib/node/main.js 24:13-37
 @ ../../node_modules/@aws/language-server-runtimes/protocol/editCompletions.js 4:41-82
 @ ../../node_modules/@aws/language-server-runtimes/runtimes/standalone.js 70:26-64
 @ ./src/serverWithCustomization.ts 3:21-81

1 warning has detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

webpack 5.99.9 compiled with 1 warning in 15356 ms
✔ Test ANTLR4 Server Runtime Integration (0.5807ms)
✔ Test ANTLR4 Server Runtime Integration with customized server (0.0871ms)


(node:1192) [DEP0190] DeprecationWarning: Passing args to a child process with shell option true can lead to security vulnerabilities, as the arguments are not escaped, only concatenated.
(Use `node --trace-deprecation ...` to show where the warning was created)
  ✔ should return completion items for SQL (100ms)
  ✔ should return diagnostic items for SQL
  ✔ should handle document changes
  ✔ should handle document close
  ✔ should not return diagnostic items for SQL

  5 passing (961ms)

ℹ tests 0
ℹ suites 2
ℹ pass 0
ℹ fail 0
ℹ cancelled 0
ℹ skipped 0
ℹ todo 0
ℹ duration_ms 986.4453

> @aws/lsp-codewhisperer-runtimes@0.0.1 test
> node scripts/test-runner.js

Webworker browser runtime tests are currently enabled only for unix, with windows OS they are disabled as we currently face issues with automatically shutting down devserver and cleaning resources after tests are executed.

> @aws/lsp-json-runtimes@0.0.1 test
> npm run test-integ


> @aws/lsp-json-runtimes@0.0.1 test-integ
> npm run package && mocha --timeout 5000 "./out/**/*Integ.test.js" --retries 2


> @aws/lsp-json-runtimes@0.0.1 package
> npm run compile && npm run webpack


> @aws/lsp-json-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-json-runtimes@0.0.1 webpack
> webpack

assets by status 11 MiB [emitted]
  assets by path *.js 10.6 MiB
    asset aws-lsp-json-standalone-with-customization.js 5.31 MiB [emitted] (name: aws-lsp-json-standalone-with-customization)
    + 6 assets
  assets by path *.node 409 KiB
    asset registry.node 204 KiB [emitted] (auxiliary name: aws-lsp-json-standalone, aws-lsp-json-standalone-with-customization)
    + 2 assets
assets by status 4.63 KiB [compared for emit]
  assets by path ../out/*.ts 336 bytes
    asset ../out/common.d.ts 314 bytes [compared for emit]
    asset ../out/serverWithCustomization.d.ts 11 bytes [compared for emit]
    asset ../out/serverWithoutCustomization.d.ts 11 bytes [compared for emit]
  assets by path ../out/tests/*.ts 4.31 KiB
    asset ../out/tests/testUtilsCF.d.ts 4.29 KiB [compared for emit]
    asset ../out/tests/jsonServerCFInteg.test.d.ts 11 bytes [compared for emit]
orphan modules 1.56 MiB [orphan] 296 modules
runtime modules 4.97 KiB 18 modules
modules by path ../../node_modules/ 4.13 MiB
  cacheable modules 4.13 MiB 1055 modules
  + 2 modules
modules by path ../../core/aws-lsp-core/out/ 3.66 KiB 5 modules
modules by path ./src/*.ts 2.44 KiB
  ./src/serverWithCustomization.ts 1.29 KiB [built] [code generated]
  ./src/serverWithoutCustomization.ts 442 bytes [built] [code generated]
  ./src/common.ts 735 bytes [built] [code generated]
modules by path ../../server/aws-lsp-json/out/ 8.24 KiB
  ../../server/aws-lsp-json/out/index.js 621 bytes [built] [code generated]
  ../../server/aws-lsp-json/out/language-server/jsonServer.js 4.98 KiB [built] [code generated]
  ../../server/aws-lsp-json/out/language-service/jsonLanguageService.js 2.65 KiB [built] [code generated]
+ 41 modules

WARNING in ../../node_modules/vscode-languageserver-types/lib/umd/main.js 3:24-31
Critical dependency: require function is used in a way in which dependencies cannot be statically extracted
 @ ../../node_modules/vscode-languageserver-protocol/lib/common/api.js 23:13-51
 @ ../../node_modules/vscode-languageserver-protocol/lib/node/main.js 24:13-37
 @ ../../node_modules/vscode-languageserver/lib/common/api.js 25:13-55
 @ ../../node_modules/vscode-languageserver/lib/node/main.js 29:13-37
 @ ../../server/aws-lsp-json/out/language-server/jsonServer.js 7:32-64
 @ ./src/serverWithCustomization.ts 6:21-76

1 warning has detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

webpack 5.99.9 compiled with 1 warning in 7473 ms
✔ Test JsonServer with CloudFormation schema (0.5462ms)
✔ Test JsonServer with CloudFormation schema and a custom implementation of the JsonLanguageService (0.0837ms)


(node:7904) [DEP0190] DeprecationWarning: Passing args to a child process with shell option true can lead to security vulnerabilities, as the arguments are not escaped, only concatenated.
(Use `node --trace-deprecation ...` to show where the warning was created)
  ✔ should return completion items for CloudFormation, JSON (1536ms)
  ✔ should return hover item, JSON
  ✔ should return diagnostic items, JSON
  ✔ should return format items, JSON
  ✔ should return customized diagnostic items, JSON (1498ms)
  ✔ should return customized hover item, JSON

  6 passing (4s)

ℹ tests 0
ℹ suites 2
ℹ pass 0
ℹ fail 0
ℹ cancelled 0
ℹ skipped 0
ℹ todo 0
ℹ duration_ms 3533.1055

> @aws/lsp-yaml-runtimes@0.0.1 test
> npm run test-integ


> @aws/lsp-yaml-runtimes@0.0.1 test-integ
> npm run package && mocha --timeout 8000 "./out/**/*Integ.test.js" --retries 2


> @aws/lsp-yaml-runtimes@0.0.1 package
> npm run compile && npm run webpack


> @aws/lsp-yaml-runtimes@0.0.1 compile
> tsc --build


> @aws/lsp-yaml-runtimes@0.0.1 webpack
> webpack

assets by status 26 MiB [emitted]
  assets by path *.js 25.6 MiB
    asset aws-lsp-yaml-standalone-with-customization.js 12.8 MiB [emitted] (name: aws-lsp-yaml-standalone-with-customization)
    + 6 assets
  assets by path *.node 409 KiB
    asset registry.node 204 KiB [emitted] (auxiliary name: aws-lsp-yaml-standalone, aws-lsp-yaml-standalone-with-customization)
    + 2 assets
assets by status 4.44 KiB [compared for emit]
  assets by path ../out/*.ts 392 bytes
    asset ../out/common.d.ts 370 bytes [compared for emit]
    asset ../out/serverWithCustomization.d.ts 11 bytes [compared for emit]
    asset ../out/serverWithoutCustomization.d.ts 11 bytes [compared for emit]
  assets by path ../out/tests/*.ts 4.05 KiB
    asset ../out/tests/testUtilsCF.d.ts 4.04 KiB [compared for emit]
    asset ../out/tests/yamlServerCFInteg.test.d.ts 11 bytes [compared for emit]
orphan modules 1.56 MiB [orphan] 296 modules
runtime modules 4.97 KiB 18 modules
modules by path ../../node_modules/ 11.1 MiB
  cacheable modules 11.1 MiB 1244 modules
  + 3 modules
modules by path ../../core/aws-lsp-core/out/ 3.66 KiB 5 modules
modules by path ./src/*.ts 2.57 KiB
  ./src/serverWithCustomization.ts 1.34 KiB [built] [code generated]
  ./src/serverWithoutCustomization.ts 442 bytes [built] [code generated]
  ./src/common.ts 821 bytes [built] [code generated]
modules by path ../../server/aws-lsp-yaml/out/ 8.31 KiB
  ../../server/aws-lsp-yaml/out/index.js 621 bytes [built] [code generated]
  ../../server/aws-lsp-yaml/out/language-server/yamlServer.js 4.97 KiB [built] [code generated]
  ../../server/aws-lsp-yaml/out/language-service/yamlLanguageService.js 2.73 KiB [built] [code generated]
+ 44 modules

WARNING in ../../node_modules/vscode-languageserver-types/lib/umd/main.js 3:24-31
Critical dependency: require function is used in a way in which dependencies cannot be statically extracted
 @ ../../node_modules/vscode-languageserver-protocol/lib/common/api.js 23:13-51
 @ ../../node_modules/vscode-languageserver-protocol/lib/node/main.js 24:13-37
 @ ../../node_modules/vscode-languageserver/lib/common/api.js 25:13-55
 @ ../../node_modules/vscode-languageserver/lib/node/main.js 29:13-37
 @ ../../server/aws-lsp-yaml/out/language-server/yamlServer.js 7:32-64
 @ ./src/serverWithCustomization.ts 6:21-76

WARNING in ../../node_modules/yaml-language-server/node_modules/prettier/index.js 6610:17-61
Critical dependency: the request of a dependency is an expression
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/services/yamlFormatter.js 10:17-36
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/yamlLanguageService.js 13:24-59
 @ ../../node_modules/yaml-language-server/out/server/src/index.js 18:13-61
 @ ../../server/aws-lsp-yaml/out/language-service/yamlLanguageService.js 6:31-62
 @ ../../server/aws-lsp-yaml/out/index.js 6:28-77
 @ ./src/serverWithCustomization.ts 4:19-43

WARNING in ../../node_modules/yaml-language-server/node_modules/prettier/index.js 15936:8-15
Critical dependency: require function is used in a way in which dependencies cannot be statically extracted
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/services/yamlFormatter.js 10:17-36
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/yamlLanguageService.js 13:24-59
 @ ../../node_modules/yaml-language-server/out/server/src/index.js 18:13-61
 @ ../../server/aws-lsp-yaml/out/language-service/yamlLanguageService.js 6:31-62
 @ ../../server/aws-lsp-yaml/out/index.js 6:28-77
 @ ./src/serverWithCustomization.ts 4:19-43

WARNING in ../../node_modules/yaml-language-server/node_modules/prettier/index.js 18428:30-49
Critical dependency: the request of a dependency is an expression
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/services/yamlFormatter.js 10:17-36
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/yamlLanguageService.js 13:24-59
 @ ../../node_modules/yaml-language-server/out/server/src/index.js 18:13-61
 @ ../../server/aws-lsp-yaml/out/language-service/yamlLanguageService.js 6:31-62
 @ ../../server/aws-lsp-yaml/out/index.js 6:28-77
 @ ./src/serverWithCustomization.ts 4:19-43

WARNING in ../../node_modules/yaml-language-server/node_modules/prettier/index.js 38143:9-48
Critical dependency: the request of a dependency is an expression
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/services/yamlFormatter.js 10:17-36
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/yamlLanguageService.js 13:24-59
 @ ../../node_modules/yaml-language-server/out/server/src/index.js 18:13-61
 @ ../../server/aws-lsp-yaml/out/language-service/yamlLanguageService.js 6:31-62
 @ ../../server/aws-lsp-yaml/out/index.js 6:28-77
 @ ./src/serverWithCustomization.ts 4:19-43

WARNING in ../../node_modules/yaml-language-server/node_modules/prettier/third-party.js 83:33-50
Critical dependency: the request of a dependency is an expression
 @ ../../node_modules/yaml-language-server/node_modules/prettier/index.js 18407:21-48 38088:21-48
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/services/yamlFormatter.js 10:17-36
 @ ../../node_modules/yaml-language-server/out/server/src/languageservice/yamlLanguageService.js 13:24-59
 @ ../../node_modules/yaml-language-server/out/server/src/index.js 18:13-61
 @ ../../server/aws-lsp-yaml/out/language-service/yamlLanguageService.js 6:31-62
 @ ../../server/aws-lsp-yaml/out/index.js 6:28-77
 @ ./src/serverWithCustomization.ts 4:19-43

6 warnings have detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

webpack 5.99.9 compiled with 6 warnings in 9589 ms
✔ Test YamlServer with CloudFormation schema (0.5523ms)
✔ Test YamlServer with CloudFormation schema and a custom implementation of the YamlLanguageService (0.0904ms)


(node:3168) [DEP0190] DeprecationWarning: Passing args to a child process with shell option true can lead to security vulnerabilities, as the arguments are not escaped, only concatenated.
(Use `node --trace-deprecation ...` to show where the warning was created)
  ✔ should return hover item without header and footer, YAML (2831ms)
  ✔ should return diagnostic items, YAML (1371ms)
  ✔ should return format items, YAML (41ms)
  ✔ should return completion items for CloudFormation, YAML (4117ms)
  ✔ should return customized diagnostic items, YAML (1508ms)
  ✔ should return customized hover item, YAML (2765ms)

  6 passing (13s)

ℹ tests 0
ℹ suites 2
ℹ pass 0
ℹ fail 0
ℹ cancelled 0
ℹ skipped 0
ℹ todo 0
ℹ duration_ms 13489.768

> @aws/hello-world-lsp-runtimes@0.0.1 test
> npm run test-integ


> @aws/hello-world-lsp-runtimes@0.0.1 test-integ
> npm run package && mocha --timeout 5000 "./out/**/*Integ.test.js"


> @aws/hello-world-lsp-runtimes@0.0.1 package
> npm run compile && npm run webpack


> @aws/hello-world-lsp-runtimes@0.0.1 compile
> tsc --build


> @aws/hello-world-lsp-runtimes@0.0.1 webpack
> webpack

assets by status 5.29 MiB [emitted]
  assets by path *.js 4.89 MiB
    asset hello-world-lsp-standalone.js 4.87 MiB [emitted] (name: hello-world-lsp-standalone)
    + 5 assets
  assets by path *.node 409 KiB
    asset registry.node 204 KiB [emitted] (auxiliary name: hello-world-lsp-standalone)
    asset crypt32-x64.node 115 KiB [emitted] (auxiliary name: hello-world-lsp-standalone)
    asset crypt32-ia32.node 90.5 KiB [emitted] (auxiliary name: hello-world-lsp-standalone)
assets by status 33 bytes [compared for emit]
  assets by path ../out/*.ts 22 bytes
    asset ../out/standalone.d.ts 11 bytes [compared for emit]
    asset ../out/webworker.d.ts 11 bytes [compared for emit]
  assets by path ../out/tests/ 11 bytes
    asset ../out/tests/helloWorldServerInteg.test.d.ts 11 bytes [compared for emit]
    asset ../out/tests/testFixture/completion.d.ts 0 bytes [compared for emit]
orphan modules 1.56 MiB [orphan] 296 modules
runtime modules 2.48 KiB 9 modules
modules by path ../../node_modules/ 3.76 MiB
  cacheable modules 3.76 MiB
    javascript modules 3.76 MiB 1024 modules
    json modules 3.07 KiB
      ../../node_modules/ajv/dist/refs/json-schema-draft-07.json 2.72 KiB [built] [code generated]
      ../../node_modules/ajv/dist/refs/data.json 360 bytes [built] [code generated]
  ../../node_modules/vscode-languageserver-types/lib/umd/ sync 160 bytes [built] [code generated]
  ../../node_modules/win-ca/lib/ sync ^\.\/crypt32\-.*$ 244 bytes [built] [code generated]
modules by path ../../server/hello-world-lsp/out/ 5.52 KiB
  ../../server/hello-world-lsp/out/index.js 860 bytes [built] [code generated]
  ../../server/hello-world-lsp/out/language-server/helloWorldServer.js 4.37 KiB [built] [code generated]
  ../../server/hello-world-lsp/out/language-server/helloWorldService.js 317 bytes [built] [code generated]
+ 42 modules

WARNING in ../../node_modules/vscode-languageserver-types/lib/umd/main.js 3:24-31
Critical dependency: require function is used in a way in which dependencies cannot be statically extracted
 @ ../../node_modules/vscode-languageserver-protocol/lib/common/api.js 23:13-51
 @ ../../node_modules/vscode-languageserver-protocol/lib/node/main.js 24:13-37
 @ ../../node_modules/@aws/language-server-runtimes/protocol/editCompletions.js 4:41-82
 @ ../../node_modules/@aws/language-server-runtimes/runtimes/standalone.js 70:26-64
 @ ./src/standalone.ts 4:21-81

1 warning has detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

webpack 5.99.9 compiled with 1 warning in 12121 ms

assets by path ../out/*.ts 22 bytes
  asset ../out/standalone.d.ts 11 bytes [compared for emit]
  asset ../out/webworker.d.ts 11 bytes [compared for emit]
assets by path ../out/tests/ 11 bytes
  asset ../out/tests/helloWorldServerInteg.test.d.ts 11 bytes [compared for emit]
  asset ../out/tests/testFixture/completion.d.ts 0 bytes [compared for emit]
asset hello-world-lsp-webworker.js 1.66 MiB [emitted] (name: hello-world-lsp-webworker)
runtime modules 670 bytes 3 modules
modules by path ../../node_modules/ 1.18 MiB
  javascript modules 1.18 MiB 494 modules
  json modules 3.07 KiB
    ../../node_modules/ajv/dist/refs/json-schema-draft-07.json 2.72 KiB [built] [code generated]
    ../../node_modules/ajv/dist/refs/data.json 360 bytes [built] [code generated]
modules by path ../../server/hello-world-lsp/out/ 5.52 KiB
  ../../server/hello-world-lsp/out/index.js 860 bytes [built] [code generated]
  ../../server/hello-world-lsp/out/language-server/helloWorldServer.js 4.37 KiB [built] [code generated]
  ../../server/hello-world-lsp/out/language-server/helloWorldService.js 317 bytes [built] [code generated]
./src/webworker.ts 369 bytes [built] [code generated]
webpack 5.99.9 compiled successfully in 11256 ms
✔ Test HelloWorldServer (0.545ms)


(node:4444) [DEP0190] DeprecationWarning: Passing args to a child process with shell option true can lead to security vulnerabilities, as the arguments are not escaped, only concatenated.
(Use `node --trace-deprecation ...` to show where the warning was created)
  ✔ should return completion items

  1 passing (221ms)

ℹ tests 0
ℹ suites 1
ℹ pass 0
ℹ fail 0
ℹ cancelled 0
ℹ skipped 0
ℹ todo 0
ℹ duration_ms 238.6403

> @aws/chat-client@0.1.35 test
> npm run test:unit


> @aws/chat-client@0.1.35 test:unit
> ts-mocha -b "./src/**/*.test.ts"



  Chat
    ✔ publishes ready event when initialized
    ✔ publishes telemetry event, when send to prompt is triggered (75ms)
    ✔ publishes telemetry event, when show error is triggered (96ms)
    ✔ publishes tab added event, when UI tab is added (107ms)
    ✔ publishes tab removed event, when UI tab is removed (166ms)
    ✔ publishes tab changed event, when UI tab is changed (385ms)
    ✔ generic command creates a chat request (1646ms)
    ✔ open tab requestId was propagated from inbound to outbound message (1086ms)
    ✔ complete chat response triggers ui events
    ✔ partial chat response triggers ui events
    ✔ partial chat response with header triggers ui events
    chatOptions
      ✔ enables history and export features support
      ✔ does not enable history and export features support if flags are falsy
      ✔ enables MCP when params.mcpServers is true and config.agenticMode is true
      ✔ does not enable MCP when params.mcpServers is true but config.agenticMode is false
      ✔ does not enable MCP when params.mcpServers is false and config.agenticMode is true
      ✔ does not enable MCP when params.mcpServers is undefined and config.agenticMode is true
    onGetSerializedChat
      ✔ getSerializedChat requestId was propagated from inbound to outbound message (1271ms)
    with client adapter
Set Chat events routing with custom client adapter
      ✔ should route inbound message to client adapter

  history
    ✔ show opens detailed list if called the first time
    ✔ show updates detailed list if called the second time
    ✔ show opens detailed list if called after close

  rules
    showLoading
      ✔ opens top bar button overlay with loading message
    show
      ✔ opens top bar button overlay when called first time
      ✔ updates existing overlay when called second time
    rule click handling
      ✔ shows custom form when create rule is clicked
      ✔ calls messager when regular rule is clicked
      ✔ does nothing when item has no id
    folder click handling
      ✔ calls messager when folder is clicked
    keyboard handling
      ✔ closes overlay when Escape is pressed
      ✔ does nothing when other keys are pressed
    close
      ✔ closes the overlay
    convertRulesListToDetailedListGroup
      ✔ converts rules folder to detailed list group
      ✔ handles empty rules array

  imageVerification
    constants
      ✔ has correct MAX_IMAGE_CONTEXT value
      ✔ has correct default options
    isSupportedImageExtension
      ✔ returns true for supported extensions
      ✔ returns true for supported extensions with dots
      ✔ returns true for uppercase extensions
      ✔ returns false for unsupported extensions
    isFileSizeValid
      ✔ returns true for valid file sizes
      ✔ returns false for oversized files
      ✔ accepts custom max size
    areImageDimensionsValid
      ✔ returns true for valid dimensions
      ✔ returns false for oversized dimensions
      ✔ accepts custom max dimension
    verifyClientImage
      ✔ validates a correct image file
      ✔ rejects unsupported file extension
      ✔ rejects oversized files
      ✔ rejects images with oversized dimensions
      ✔ handles image loading errors
    verifyClientImages
      ✔ separates valid and invalid files
      ✔ handles empty file list
      ✔ handles files without names

  McpMynahUi
    listMcpServers
      ✔ should set isMcpServersListActive to true
      ✔ should call mynahUi.openDetailedList with correct parameters
      ✔ should handle disabled servers correctly
      ✔ should handle failed servers correctly
      ✔ should handle events correctly
    mcpServerClick
      - should handle open-mcp-server action correctly
      ✔ should handle server management actions correctly
      ✔ should handle update-mcp-list action correctly
    private helper methods
      ✔ should process filter options correctly
      ✔ should create detailed list for adding MCP server correctly
      ✔ should create detailed list for viewing MCP server correctly

  MynahUI
    handleChatPrompt
      ✔ should handle normal chat prompt
      ✔ should handle clear quick action
      ✔ should handle quick actions
    openTab
      ✔ should create a new tab with welcome messages if tabId not passed and previous messages not passed (837ms)
      ✔ should create a new tab with messages if tabId is not passed and previous messages are passed (855ms)
      ✔ should call onOpenTab if a new tab if tabId not passed and tab not created
      ✔ should open existing tab if tabId passed and tabId not selected
      ✔ should not open existing tab if tabId passed but tabId already selected
    sendGenericCommand
      ✔ should create a new tab if none exits (2536ms)
      ✔ should create a new tab if current tab is loading (3198ms)
      ✔ should not create a new tab if one exists already
      ✔ should call handleChatPrompt when sendGenericCommand is called
    onTabBarButtonClick
      ✔ should list conversations when Chat History button is clicked
      ✔ should export conversation when Export button is clicked
    conversationClicked result
      ✔ should list conversations if successfully deleted conversation
      ✔ should not list conversarions if conversartion click processing failed
    handlePromptInputChange
      ✔ should add pairProgrammingModeOn message when switching from off to on
      ✔ should add pairProgrammingModeOff message when switching from on to off
      ✔ should not add any message when pair programming mode is not changed
      ✔ should update all promptInputOptions with new values
      ✔ should add model selection notification when model is changed
    getSerializedChat
      ✔ should return serialized chat content for supported formats
      ✔ should show an error if requested format is not supported
    listAvailableModels
      ✔ should update promptInputOptions with available models
    sendPinnedContext
      ✔ should update UI with pinned context items
      ✔ should show full title when no pinned context items exist
      ✔ should handle active editor context item
      ✔ should remove active editor when no textDocument is provided
    stringOverrides
      ✔ should apply string overrides to config texts

  withAdapter
Set Chat events routing with custom client adapter
    ✔ should instantiate and inject mynahUIRef to Adapter

  tabFactory
    getDefaultTabData
      ✔ returns default tab data if no updates
      ✔ enabling history adds history tab bar button to default tab bar buttons
      ✔ enabling history sets history tab bar button
      ✔ enabling export sets export tab bar button
    createTab
      ✔ should include model selection when agentic mode and model selection are enabled
      ✔ should not include model selection when only agentic mode is enabled
      ✔ should not include any prompt input options when neither agentic mode nor model selection are enabled
      ✔ should not include any prompt input options when only model selection is enabled but agentic mode is not

  modelSelection
    getModelSelectionChatItem
      ✔ should return a chat item with the correct model name
    modelUnavailableBanner
      ✔ should have the correct properties
    modelThrottledBanner
      ✔ should have the correct properties

  pairProgramming
    programmerModeCard
      ✔ has correct properties
    pairProgrammingPromptInput
      ✔ has correct properties
    pairProgrammingModeOn
      ✔ has correct properties
    pairProgrammingModeOff
      ✔ has correct properties
    testRerouteCard
      ✔ has correct properties
    docRerouteCard
      ✔ has correct properties
    devRerouteCard
      ✔ has correct properties
    createRerouteCard
      ✔ returns testRerouteCard for /test command
      ✔ returns docRerouteCard for /doc command
      ✔ returns devRerouteCard for /dev command
      ✔ returns devRerouteCard for unknown command
      ✔ returns devRerouteCard for empty string

  utils
    toMynahIcon
      ✔ returns valid MynahIcon when icon exists
      ✔ returns undefined for invalid icon
      ✔ returns undefined for undefined input
    toMynahButtons
      ✔ converts buttons with valid icons
      ✔ returns undefined for undefined input
      ✔ handles empty array
    toMynahHeader
      ✔ converts header with all properties
      ✔ handles header without status
      ✔ returns undefined for undefined header
      ✔ handles header with invalid icons
    toMynahFileList
      ✔ converts file list with all properties
      ✔ uses default root folder title when not provided
      ✔ returns undefined for undefined input
      ✔ handles file paths with different structures
      ✔ handles multiple line ranges
    toDetailsWithoutIcon
      ✔ removes icons from details
      ✔ handles undefined input
      ✔ handles empty object
    toMynahContextCommand
      ✔ converts feature context with string value
      ✔ returns empty object for undefined feature
      ✔ returns empty object for feature without string value
      ✔ returns empty object for feature with empty string value

  withAdapter
Set Chat events routing with custom client adapter
    ✔ should throw error if custom event handler is not defined
    Standard Events routing on tabId as first argument
      onTabAdd
Set Chat events routing with custom client adapter
        ✔ should delegate onTabAdd to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onTabAdd to original handler for unsupported tabs
      onTabChange
Set Chat events routing with custom client adapter
        ✔ should delegate onTabChange to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onTabChange to original handler for unsupported tabs
      onTabRemove
Set Chat events routing with custom client adapter
        ✔ should delegate onTabRemove to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onTabRemove to original handler for unsupported tabs
      onStopChatResponse
Set Chat events routing with custom client adapter
        ✔ should delegate onStopChatResponse to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onStopChatResponse to original handler for unsupported tabs
      onLinkClick
Set Chat events routing with custom client adapter
        ✔ should delegate onLinkClick to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onLinkClick to original handler for unsupported tabs
      onSourceLinkClick
Set Chat events routing with custom client adapter
        ✔ should delegate onSourceLinkClick to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onSourceLinkClick to original handler for unsupported tabs
      onInfoLinkClick
Set Chat events routing with custom client adapter
        ✔ should delegate onInfoLinkClick to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onInfoLinkClick to original handler for unsupported tabs
      onCodeInsertToCursorPosition
Set Chat events routing with custom client adapter
        ✔ should delegate onCodeInsertToCursorPosition to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onCodeInsertToCursorPosition to original handler for unsupported tabs
      onCopyCodeToClipboard
Set Chat events routing with custom client adapter
        ✔ should delegate onCopyCodeToClipboard to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onCopyCodeToClipboard to original handler for unsupported tabs
      onCodeBlockActionClicked
Set Chat events routing with custom client adapter
        ✔ should delegate onCodeBlockActionClicked to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onCodeBlockActionClicked to original handler for unsupported tabs
      onFileClick
Set Chat events routing with custom client adapter
        ✔ should delegate onFileClick to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onFileClick to original handler for unsupported tabs
      onFileActionClick
Set Chat events routing with custom client adapter
        ✔ should delegate onFileActionClick to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onFileActionClick to original handler for unsupported tabs
      onVote
Set Chat events routing with custom client adapter
        ✔ should delegate onVote to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onVote to original handler for unsupported tabs
      onSendFeedback
Set Chat events routing with custom client adapter
        ✔ should delegate onSendFeedback to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onSendFeedback to original handler for unsupported tabs
      onFollowUpClicked
Set Chat events routing with custom client adapter
        ✔ should delegate onFollowUpClicked to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onFollowUpClicked to original handler for unsupported tabs
      onCustomFormAction
Set Chat events routing with custom client adapter
        ✔ should delegate onCustomFormAction to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onCustomFormAction to original handler for unsupported tabs
      onQuickCommandGroupActionClick
Set Chat events routing with custom client adapter
        ✔ should delegate onQuickCommandGroupActionClick to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onQuickCommandGroupActionClick to original handler for unsupported tabs
      onChatItemEngagement
Set Chat events routing with custom client adapter
        ✔ should delegate onChatItemEngagement to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onChatItemEngagement to original handler for unsupported tabs
      onShowMoreWebResultsClick
Set Chat events routing with custom client adapter
        ✔ should delegate onShowMoreWebResultsClick to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onShowMoreWebResultsClick to original handler for unsupported tabs
      onChatPromptProgressActionButtonClicked
Set Chat events routing with custom client adapter
        ✔ should delegate onChatPromptProgressActionButtonClicked to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onChatPromptProgressActionButtonClicked to original handler for unsupported tabs
      onTabbedContentTabChange
Set Chat events routing with custom client adapter
        ✔ should delegate onTabbedContentTabChange to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onTabbedContentTabChange to original handler for unsupported tabs
    Special Routing Logic
Set Chat events routing with custom client adapter
      ✔ should delegate onBeforeTabRemove to custom handler for supported tabs
Set Chat events routing with custom client adapter
      ✔ should call route onTabBarButtonClick only to default handler
Set Chat events routing with custom client adapter
      ✔ should call both custom and original onReady handlers
Set Chat events routing with custom client adapter
      ✔ should call both custom and original onResetStore handlers
Set Chat events routing with custom client adapter
      ✔ should call both custom and original onFocusStateChanged handlers
      onChatPrompt
Set Chat events routing with custom client adapter
        ✔ should delegate onChatPrompt to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate quick action commands to adapter handler
Set Chat events routing with custom client adapter
        ✔ should delegate onChatPrompt to original handler for unsupported tabs and commands
      onInBodyButtonClicked
Set Chat events routing with custom client adapter
        ✔ should delegate onInBodyButtonClicked to original handler for disclaimerAcknowledge action
Set Chat events routing with custom client adapter
        ✔ should delegate onInBodyButtonClicked to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onInBodyButtonClicked to original handler for unsupported tab
      onFormTextualItemKeyPress
Set Chat events routing with custom client adapter
        ✔ should delegate onFormTextualItemKeyPress to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onFormTextualItemKeyPress to original handler for unsupported tabs
      onFormModifierEnterPress
Set Chat events routing with custom client adapter
        ✔ should delegate onFormModifierEnterPress to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onFormModifierEnterPress to original handler for unsupported tabs
      onContextSelected
Set Chat events routing with custom client adapter
        ✔ should delegate onContextSelected to custom handler for supported tabs
Set Chat events routing with custom client adapter
        ✔ should delegate onContextSelected to original handler for unsupported tabs
      onFormLinkClick
Set Chat events routing with custom client adapter
        ✔ should delegate onFormLinkClick to custom handler if it exists
Set Chat events routing with custom client adapter
Set Chat events routing with custom client adapter
        ✔ should delegate onFormLinkClick to original handler if adapter handler does not exist


  201 passing (14s)
  1 pending


> @aws/lsp-core@0.0.15 test
> npm run test-unit


> @aws/lsp-core@0.0.15 test-unit
> mocha --timeout 0 "./out/**/*.test.js"

▶ Test UriCacheRepository
  ✔ cacheContent (39.115ms)
  ✔ touchLastUpdatedTime (0.3411ms)
  ✔ getContent (0.0732ms)
  ✔ getContentETag (0.0993ms)
✔ Test UriCacheRepository (43.9466ms)
✔ Test CachedContentHandler (0.066ms)
✔ Test FileHandler (0.0935ms)
✔ Test HttpHandler (0.0521ms)
▶ Test UriResolverBuilder
  ✔ throws when no handler is added (1.7822ms)
  ✔ throws when unhandled (0.6325ms)
  ✔ builds one handler (0.3093ms)
  ✔ delegates to next handler (0.2231ms)
  ✔ stops delegating when a handler returns (0.2558ms)
✔ Test UriResolverBuilder (3.7731ms)
▶ Test mutuallyExclusiveLanguageService
  ✔ 2 services support language, should return 1 result (1.375ms)
  ✔ languageId is unknown, isSupported, should recognize (0.2194ms)
  ✔ languageId is known, isSupported, should recognize (0.2398ms)
  ✔ languageId is unknown, validate, should return empty diagnostic list (0.3728ms)
  ✔ languageId is known, validate, should return 1 diagnostic (0.7561ms)
  ✔ languageId is unknown, complete, should return null (0.4327ms)
  ✔ languageId is known, complete, should return 1 completion (0.4429ms)
  ✔ languageId is unknown, format, should return null (0.2278ms)
  ✔ languageId is known, format, should return 1 format (0.3394ms)
  ✔ languageId is unknown, hover, should return null (0.2221ms)
  ✔ languageId is known, hover, should return 1 hover (0.231ms)
✔ Test mutuallyExclusiveLanguageService (5.2489ms)


  1) stores data
  2) stores data
  3) retrieves data
  4) retrieves data
  ✔ skips file requests
  5) requests content when there is no cache
  6) requests content when the cache is stale
  7) requests content when a different version is online
  ✔ requests content
  ✔ skips non-file requests
  ✔ requests content
  ✔ skips file requests
  Test HttpRequest class
    Test request()
      ✔ calls the impl with no options
      ✔ calls the impl with the header option

  AwsError
    ✔ Wraps general error in AwsError with given awsErrorCode
    ✔ Wraps null in an AwsError with "Unknown error"
    ✔ Passes AwsError on as-is
    ✔ Passed in cause is retained

  partialClone
    ✔ omits properties by depth
    ✔ omits properties by name
    ✔ truncates properties by maxLength

  filesystemUtilities
    getFileDistance
      ✔ distance 0
      ✔ root distance 0
      ✔ distance 0 with whitespace
      ✔ distance 1
      ✔ distance 3
      ✔ distance 4
      ✔ another distance 4
      ✔ distance 5
      ✔ distance 6
      ✔ distance 6 with whitespaces
      ✔ backslash distance 1
      ✔ backslash distnace 3

  isCodeFile
    ✔ returns true for code files
    ✔ returns false for other files

  pathUtils
    ✔ normalizeSeparator()
    ✔ normalize()
    ✔ isInDirectory()
    sanitizePath
      ✔ trims whitespace from input path
      ✔ expands tilde to user home directory
      ✔ converts relative paths to absolute paths
      ✔ leaves absolute paths unchanged

  pollingSet
    ✔ inherits basic set properties
    ✔ does not poll on initialization
    ✔ does not trigger prematurely
    ✔ stops timer once polling set is empty
    ✔ runs action once per interval

  ChildProcess
    run
      ✔ starts and captures stdout - windows
      ✔ runs cmd files containing a space in the filename and folder
      ✔ errs when starting twice - windows
      ✔ runs scripts containing a space in the filename and folder
      ✔ reports error for missing executable
      Extra options
        ✔ can report errors
        ✔ can reject on errors if `rejectOnError` is set
        ✔ kills the process if an error is reported
        ✔ can merge with base options
        ✔ respects timeout parameter
    stop()
      ✔ detects running processes and successfully stops a running process - Windows (118ms)
      ✔ can stop() previously stopped processes - Windows (108ms)

  ChildProcessTracker
    - removes stopped processes every 10 seconds
    ✔ logs a warning message when system usage exceeds threshold
    ✔ does not log for processes within threshold

  retryUtils
    retryWithBackoff
      ✔ should return result on first success
      ✔ should retry on retryable errors
      ✔ should not retry on non-retryable client errors
      ✔ should retry on server errors
      ✔ should use exponential backoff by default
      ✔ should respect custom maxRetries
      ✔ should use custom isRetryable function

  sanitizeFilename
    ✔ removes emojis
    ✔ replaces slash with underscore
    ✔ replaces space with underscore
    ✔ replaces dot with replaceString
    ✔ docstring example
    ✔ keeps dot
    ✔ keeps special chars

  undefinedIfEmpty
    ✔ return undefined if input is undefined
    ✔ return undefined if input is empty string
    ✔ return undefined if input is blank
    ✔ return str if input is not empty
    ✔ return original str without trim

  truncate
    ✔ truncate abc 123 to 3 chars
    ✔ truncate abc 123 to -3 chars
    ✔ truncate abc 123 to 1 chars
    ✔ truncate abc 123 to -1 chars
    ✔ truncate abc 123 to 0 chars
    ✔ truncate abc 123 to 99 chars
    ✔ truncate abc 123 to -99 chars

  waitUntil
    ✔ returns value after multiple function calls
    ✔ returns value after multiple function calls WITH backoff
    ✔ timeout before function returns defined value
    ✔ returns true/false values correctly
    ✔ timeout when function takes longer than timeout parameter
    ✔ timeout from slow function calls
    ✔ returns value with after multiple calls and function delay 
    ✔ returns value after setting truthy parameter to true
    ✔ timeout after setting truthy parameter to true

  waitUntil w/ retries
    ✔ should retry when retryOnFail callback returns true
    ✔ should not retry when retryOnFail callback returns false
    ✔ retries the function until it succeeds
    ✔ retryOnFail ignores truthiness
    ✔ throws the last error if the function always fails, using defaults
    ✔ honors retry delay + backoff multiplier

  workspaceUtils
    isParentFolder
      ✔ handles different cases
    isInWorkspace
      ✔ finds the file within the workspace
      ✔ handles multi-root workspaces
      ✔ handles the case where its the workspace itself
    readDirectoryRecursively
      ✔ recurses into subdirectories
      ✔ respects maxDepth parameter
      ✔ correctly identifies entry types
      ✔ always fail if directory does not exist
      ✔ ignores files in the exclude entries
      ✔ ignores directories in the exclude entries
    readDirectoryWithTreeOuput
      ✔ recurses into subdirectories
      ✔ respects maxDepth parameter
      ✔ always fail if directory does not exist
      ✔ ignores files in the exclude entries
      ✔ ignores directories in the exclude entries


  110 passing (918ms)
  1 pending
  7 failing

  1) stores data:
     RangeError: Maximum call stack size exceeded
      at Object.resolve (node:path:190:10)
      at getPathParts (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\filesystem.js:22:44)
      at FileSystem.getItem (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\filesystem.js:103:17)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:907:33)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:912:18)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:912:18)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:912:18)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:912:18)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:912:18)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:912:18)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:912:18)
      at Binding.<anonymous> (D:\a\language-servers\language-servers\node_modules\mock-fs\lib\binding.js:912:18)
```

## Solution
- [ ] Reproduce issue locally
- [ ] Compare Linux vs Windows logs
- [ ] Search for 'binding' in logs
- [ ] Identify root cause
- [ ] Apply minimal fix
- [ ] Verify tests pass
