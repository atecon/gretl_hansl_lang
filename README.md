# Gretl-Hansl Syntax support for vscode

This package is supposed to become a proper extension for vscode.

## Install on your machine
Copy the folder content into the vscode extension folder. On Linux, execute the following shell command:

```
cp -rf gretl_hansl_lang $HOME/.vscode/extensions
```
Open vscode and the file `./syntax_test_hansl.inp` to see the syntax highlighting.

## Features currently implemented
- Basic grammar for the gretl-hansl syntax
- Basic snippets do exist.

## ToDos
- Write a launcher (if actually needed) for executing gretl scripts on Windows, Linux and macOS. Currently, the `tasks.json` and `launch.json` in the `./.vscode` folder only run locally on my Linux machine.
- Implement a language server (see here: https://code.visualstudio.com/api/language-extensions/language-server-extension-guide)
