asset-builder(Modified)
=============

> This is modified version of [asset-builder(original)](https://github.com/austinpray/asset-builder), bower is optional in this version and some packages are updated that was not updated in original repo.

![Project maintained](https://img.shields.io/badge/project-maintained-green.svg)

Assembles and orchestrates your dependencies so you can run them through your asset pipeline. Feed it a [manifest file](help/spec.md) and it will give you globs.

## Install

```bash
npm install https://github.com/vijayhardaha/asset-builder --save-dev
```

## Usage

```javascript
var manifest = require('asset-builder')('./assets/manifest.json');
```

## Help

- [Examples, troubleshooting tips](help/)
- [Manifest File Specification](help/spec.md)
- [View this module's API documentation](http://use-asset-builder.austinpray.com/api/)
- [Walk through the annotated source code](http://use-asset-builder.austinpray.com/docco/)
