# start-cli-core

[![npm](https://img.shields.io/npm/v/start-cli-core.svg?style=flat-square)](https://www.npmjs.com/package/start-cli-core)
[![linux build](https://img.shields.io/travis/start-runner/cli-core/master.svg?label=linux&style=flat-square)](https://travis-ci.org/start-runner/cli-core)
[![windows build](https://img.shields.io/appveyor/ci/start-runner/cli-core/master.svg?label=windows&style=flat-square)](https://ci.appveyor.com/project/start-runner/cli-core)
[![deps](https://img.shields.io/gemnasium/start-runner/cli-core.svg?style=flat-square)](https://gemnasium.com/start-runner/cli-core)

CLI core for [Start](https://github.com/start-runner/start).

## Install

```sh
npm install --save-dev start-cli-core
# or
yarn add --dev start-cli-core
```

## Usage

```js
#!/usr/bin/env node

import 'start-cli-core';
```

```
  Usage: index [options] <tasks runner> [arguments]

  Options:

    -h, --help              output usage information
    -f, --file, <file>      tasks file path, tasks.js by default
    -p, --preset, <preset>  tasks preset
```

See [documentation](https://github.com/start-runner/start#readme) for details.
