# CLE-2000 Language Support

This extension provides syntax highlighting and language support for the CLE-2000 programming language (.x2m or .c2m files).


## Installation

To install the extension manually:

```bash
code --install-extension cle2000.vsix
```

## Producing the `.vsix` File from Source Files

To produce the `.vsix` file from the JSON files, run:

```bash
vsce package -o cle2000.vsix
```