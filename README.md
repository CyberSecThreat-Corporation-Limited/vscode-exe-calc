## Description

"vscode-exe-calc" is a simple vscode extension to execute calc.exe. It demonstrated the possibility to execute reverse shell C2 tunnel or other RCE via vscode extension. An attacker may launch such kinds of "Supply-Chain Attacks" via Social Engineering or published to VSCODE Market Place.

## Usage

```shell
$ npm install -g vsce
$ cd vscode-exe-calc
$ vsce package
```

This demo extension can be manually installed via VS Code UI or CLI:

```shell
$ code --install-extension venus-0.0.1.vsix
```
