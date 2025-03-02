> Form of codemirror5
>
> Configit fork of codemirror5 enables a limit for how many lines should be processed by codemirror, to prevent the browser from freezing when processing large rules in Ace Mode.
>
> Configit Changes:
> 
> * add conditional in `runMode` function in `highlight.js`, ensuring that the `maxHighlightLength` limits the number of chars per line and the total number of chars processed.
>
> ## Publishing
> 
> To publish a new release, run the following commands:
> 
> npm run build
> npm publish 
>
> This will build and publish this package to https://github.com/orgs/configit/packages/npm/package/codemirror

# CodeMirror

[![Build Status](https://github.com/codemirror/codemirror5/workflows/main/badge.svg)](https://github.com/codemirror/codemirror5/actions)
[![NPM version](https://img.shields.io/npm/v/codemirror.svg)](https://www.npmjs.org/package/codemirror)

CodeMirror is a versatile text editor implemented in JavaScript for
the browser. It is specialized for editing code, and comes with over
100 language modes and various addons that implement more advanced
editing functionality. Every language comes with fully-featured code
and syntax highlighting to help with reading and editing complex code.

A rich programming API and a CSS theming system are available for
customizing CodeMirror to fit your application, and extending it with
new functionality.

You can find more information (and the
[manual](https://codemirror.net/5/doc/manual.html)) on the [project
page](https://codemirror.net/5/). For questions and discussion, use the
[discussion forum](https://discuss.codemirror.net/).

See
[CONTRIBUTING.md](https://github.com/codemirror/CodeMirror/blob/master/CONTRIBUTING.md)
for contributing guidelines.

The CodeMirror community aims to be welcoming to everybody. We use the
[Contributor Covenant
(1.1)](http://contributor-covenant.org/version/1/1/0/) as our code of
conduct.

### Installation

Either get the [zip file](https://codemirror.net/5/codemirror.zip) with
the latest version, or make sure you have [Node](https://nodejs.org/)
installed and run:

    npm install codemirror

**NOTE**: This is the source repository for the library, and not the
distribution channel. Cloning it is not the recommended way to install
the library, and will in fact not work unless you also run the build
step.

### Quickstart

To build the project, make sure you have Node.js installed (at least version 6)
and then `npm install`. To run, just open `index.html` in your
browser (you don't need to run a webserver). Run the tests with `npm test`.
