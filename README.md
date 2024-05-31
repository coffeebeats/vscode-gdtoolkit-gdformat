# **vscode-gdtoolkit-gdformat** ![GitHub release (with filter)](https://img.shields.io/github/v/release/coffeebeats/vscode-gdtoolkit-gdformat) ![GitHub](https://img.shields.io/github/license/coffeebeats/vscode-gdtoolkit-gdformat) [![Build Status](https://img.shields.io/github/actions/workflow/status/coffeebeats/vscode-gdtoolkit-gdformat/check-commit.yml?branch=main)](https://github.com/coffeebeats/vscode-gdtoolkit-gdformat/actions?query=branch%3Amain+workflow%3Acheck)

A VS Code extension which formats GDScript files using [gdtoolkit](https://github.com/Scony/godot-gdscript-toolkit)'s [gdformat](https://github.com/Scony/godot-gdscript-toolkit/wiki/4.-Formatter) command.

> [!WARNING]
> This repository is in its early stages and isn't ready for public use yet.

## **How it works**

Simply enable the extension and configure it as the default formatter for GDScript files.

## **Getting started**

These instructions will help you install `vscode-gdtoolkit-gdformat` and format your GDScript files.

### **Installation**

TODO

## **API Reference**

### **Available Settings**

TODO

## **Development**

### Setup

The following instructions outline how to get the project set up for local development:

1. [Follow the instructions](https://go.dev/doc/install) to install Go (see [go.mod](./go.mod) for the minimum required version).
2. Clone the [coffeebeats/vscode-gdtoolkit-gdformat](https://github.com/coffeebeats/vscode-gdtoolkit-gdformat) repository.
3. Install the tools [used below](#code-submission) by following each of their specific installation instructions.

### Code submission

When submitting code for review, ensure the following requirements are met:

> ❕ **NOTE:** These instructions do not persist the tools to your development environment. When regular use is required, follow each tool's individual instructions to install permanent versions.

1. The project is correctly formatted using [prettier](https://prettier.io/docs/en/install):

    ```sh
    npx prettier . --write
    ```

2. All [eslint](https://eslint.org/docs/latest/use/getting-started#quick-start) linter warnings are addressed:

    ```sh
    npx eslint .
    ```

3. All unit tests pass and no data races are found:

    ```sh
    npm test
    ```

4. The `vscode-gdtoolkit-gdformat` extension successfully builds:

    ```sh
    npm build
    ```

## **Contributing**

All contributions are welcome! Feel free to file [bugs](https://github.com/coffeebeats/vscode-gdtoolkit-gdformat/issues/new?assignees=&labels=bug&projects=&template=bug-report.md&title=) and [feature requests](https://github.com/coffeebeats/vscode-gdtoolkit-gdformat/issues/new?assignees=&labels=enhancement&projects=&template=feature-request.md&title=) and/or open pull requests.

## **Version history**

See [CHANGELOG.md](https://github.com/coffeebeats/vscode-gdtoolkit-gdformat/blob/main/CHANGELOG.md).

## **License**

[MIT License](https://github.com/coffeebeats/vscode-gdtoolkit-gdformat/blob/main/LICENSE)
