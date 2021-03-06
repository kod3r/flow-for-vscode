# Flow for Visual Studio Code

This extension adds [Flow](http://flowtype.org) support for VS Code. Flow is a static type checker, designed to find type errors in JavaScript programs.

## Installation

Follow the [instructions](https://code.visualstudio.com/docs/editor/extension-gallery) for VS Code extension installation.

## Setup

* Flow is only supported on Mac and Linux, follow [flowtype.org](http://flowtype.org/docs/getting-started.html#_) to get started
* You need a `.flowconfig` in your workspace to enable the flow features
* Make sure you are able to run the `flow` command from the command line

## Features

* Syntax Coloring
* IntelliSense
* Go to Definition / Peek Definition
* Diagnostics (Errors, Warnings)

## Known Issues

* when you create a new file and add the `/* @flow */` to the beginning you need to manually change the mode from the status bar to `Flow`

## About

This plugin is built on top of [Nuclide](https://github.com/facebook/nuclide)'s Flow support, the [nuclide-flow-base](https://github.com/facebook/nuclide/tree/master/pkg/nuclide/flow-base) npm package.

## Contributing

* please refer to [CONTRIBUTING.md](CONTRIBUTING.md)

## License
[See here](LICENSE)
