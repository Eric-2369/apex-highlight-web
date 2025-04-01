# apex-highlight-web

**Apex Syntax Highlighter (Web)** is a lightweight, web-compatible Visual Studio Code extension that provides syntax highlighting for the Apex programming language and SOQL (Salesforce Object Query Language). This extension is powered by [TextMate grammars](https://macromates.com/manual/en/language_grammars), making it ideal for environments like [vscode.dev](https://vscode.dev) and [github.dev](https://github.dev), where traditional language servers cannot run.

## Features

- Syntax highlighting for **Apex (.cls, .trigger, .apex)** files
- Syntax highlighting for **SOQL (.soql)** files
- Fast and lightweight — no language server required
- Fully compatible with web-based VS Code environments

## Why Use This?

Unlike Salesforce’s official Apex extension, which relies on a Java-based language server, this extension uses a declarative TextMate grammar. This allows it to run entirely in the browser, making it perfect for use in web-based editors and constrained environments.

## Installation

You can install this extension from:

- [Open VSX Registry](https://open-vsx.org/extension/Eric2369/apex-highlight-web)
- [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=Eric2369.apex-highlight-web)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve grammar support or add new features.

## License

This project is licensed under the GNU General Public License v3.0 (GPLv3).
Portions of this project are based on the [Salesforce apex-tmLanguage](https://github.com/forcedotcom/apex-tmLanguage) project, which is licensed under the BSD 3-Clause License. These portions are reused and redistributed under the terms of the BSD 3-Clause License. The original license and copyright notice are preserved.
