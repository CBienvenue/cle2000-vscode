# CLE-2000 Language Support

This extension adds basic syntax highlighting for the CLE-2000 language (.x2m or .c2m) in VSCode.

## Installation

To install the extension manually:

```bash
    code --install-extension cle2000-x.x.x.vsix
```

where "x.x.x" is the code version.

## Produce the .vsix file from sources files

To produce the .vsix file from .json files, run

```bash
    vsce package
```