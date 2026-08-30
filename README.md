# Rishu Language Support for VS Code

Supports `.rc` files with Rishu syntax highlighting, brackets, indentation, comments, and snippets.

## Development
1. Open this folder in VS Code.
2. Press `F5`.
3. In the Extension Development Host, open a `.rc` file.

## Package
```bash
npm install -g @vscode/vsce
vsce package
```
Then install the generated `.vsix` from VS Code's Extensions menu.

Current keywords: `let`, `say`, `if`, `else`.
