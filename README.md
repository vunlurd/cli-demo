turbo-cli
=========

Turbo Project Demo CLI

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/turbo-cli.svg)](https://npmjs.org/package/turbo-cli)
[![Downloads/week](https://img.shields.io/npm/dw/turbo-cli.svg)](https://npmjs.org/package/turbo-cli)
[![License](https://img.shields.io/npm/l/turbo-cli.svg)](https://github.com/vunlurd/cli-demo/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g turbo-cli
$ turbo COMMAND
running command...
$ turbo (-v|--version|version)
turbo-cli/0.0.0 win32-x64 node-v16.13.0
$ turbo --help [COMMAND]
USAGE
  $ turbo COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`turbo hello`](#turbo-hello)
* [`turbo help [COMMAND]`](#turbo-help-command)

## `turbo hello`

Describe the command here

```
USAGE
  $ turbo hello

OPTIONS
  -n, --name=name  name to print

DESCRIPTION
  ...
  Extra documentation goes here
```

_See code: [src/commands/hello.js](https://github.com/vunlurd/cli-demo/blob/v0.0.0/src/commands/hello.js)_

## `turbo help [COMMAND]`

display help for turbo

```
USAGE
  $ turbo help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.5/src/commands/help.ts)_
<!-- commandsstop -->
