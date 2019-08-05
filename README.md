@projecthoneycomb/cli
=====================



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@projecthoneycomb/cli.svg)](https://npmjs.org/package/@projecthoneycomb/cli)
[![Downloads/week](https://img.shields.io/npm/dw/@projecthoneycomb/cli.svg)](https://npmjs.org/package/@projecthoneycomb/cli)
[![License](https://img.shields.io/npm/l/@projecthoneycomb/cli.svg)](https://github.com/projecthoneycomb/cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @projecthoneycomb/cli
$ comb COMMAND
running command...
$ comb (-v|--version|version)
@projecthoneycomb/cli/0.0.1 darwin-x64 node-v12.6.0
$ comb --help [COMMAND]
USAGE
  $ comb COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`comb hello [FILE]`](#comb-hello-file)
* [`comb help [COMMAND]`](#comb-help-command)

## `comb hello [FILE]`

describe the command here

```
USAGE
  $ comb hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ comb hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/projecthoneycomb/cli/blob/v0.0.1/src/commands/hello.ts)_

## `comb help [COMMAND]`

display help for comb

```
USAGE
  $ comb help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.0/src/commands/help.ts)_
<!-- commandsstop -->
