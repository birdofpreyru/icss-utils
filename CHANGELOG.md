# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [5.0.0-rc.0] - 2020-09-21

### BREAKING CHANGE

- minimum supported `Node.js` version is `>= 10.13.0 || >= 12.13.0 || >= 14`
- minimum supported `postcss` version is `^8.0.0`
- `postcss` was moved to `peerDependencies`, you need to install `postcss` in your project before use the plugin
- you need to pass `postcss` API to using `createICSSRules` (third argument)
