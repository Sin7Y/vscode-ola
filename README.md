# Ola lang vs-code extension

This extension provides syntax highlighting for `ola` language.

## Features

### Syntax Highlighting


![syntax](https://github.com/Sin7Y/vscode-ola/blob/main/images/syntax-highlighting.png?raw=true)

### Snippets


![snippets](https://github.com/Sin7Y/vscode-ola/blob/main/images/snippets.gif?raw=true)

## Uasge

 - You can find this extension in vscode's extension marketplace and install it
 - Installation （Local Development）

### Installation （Local Development）
Once you have node and npm installed, you can build the extension like so:
From the directory of this file, run:
```
npm install -g vsce
npm install
vsce package
code --install-extension ola*.vsix
```
**Note：vsce only needs to be installed globally once**
## How to publish?

https://code.visualstudio.com/api/working-with-extensions/publishing-extension