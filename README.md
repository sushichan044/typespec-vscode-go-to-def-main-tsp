# Reproduction of microsoft/typespec#issueNumber

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
