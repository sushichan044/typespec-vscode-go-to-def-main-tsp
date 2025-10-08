# Reproduction for microsoft/typespec#8688

1. Clone and open this project in VSCode
2. Install TypeSpec extension
3. open `main.tsp`
4. Try to go to definition of line 2 (`scalar/main.tsp`).
5. You will see error like below
    ```plaintext
    2025-10-08 21:21:41.697 [error] Request textDocument/definition failed.
    2025-10-08 21:21:41.697 [error]   Message: Request textDocument/definition failed with message: Cannot find module './scalar' from '/Users/sushichan044/workspace/github.com/sushichan044/typespec-vscode-go-to-def-main-tsp'
      Code: -32603 
    ```


## My testing environment

VSCode:

```
Version: 1.104.3
Commit: 385651c938df8a906869babee516bffd0ddb9829
Date: 2025-10-02T12:30:51.747Z
Electron: 37.3.1
ElectronBuildId: 12404162
Chromium: 138.0.7204.235
Node.js: 22.18.0
V8: 13.8.258.31-electron.0
OS: Darwin arm64 24.6.0
```

TypeSpec Extension:

```
Name: TypeSpec
Id: typespec.typespec-vscode
Description: TypeSpec language support for VS Code
Version: 1.4.0
Publisher: TypeSpec
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=typespec.typespec-vscode
```
