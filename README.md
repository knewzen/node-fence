<p align="center">
  <img alt="node-fence" src="https://cloud.githubusercontent.com/assets/2793951/18944300/f16230ca-8624-11e6-909a-46411104d7f3.png">
</p>

<p align="center">
  <a href="https://travis-ci.org/Slynova-Org/node-fence"><img src="https://img.shields.io/travis/Slynova-Org/node-fence/master.svg?style=flat-square" alt="Build Status"></a>
  <a href="https://coveralls.io/github/Slynova-Org/node-fence?branch=master"><img src="https://img.shields.io/coveralls/Slynova-Org/node-fence/master.svg?style=flat-square" alt="Coverage Status"></a>
  <a href="https://www.npmjs.com/package/node-fence"><img src="https://img.shields.io/npm/v/node-fence.svg?style=flat-square" alt="Version"></a>
  <a href="https://www.npmjs.com/package/node-fence"><img src="https://img.shields.io/npm/dt/node-fence.svg?style=flat-square" alt="Downloads"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/npm/l/node-fence.svg?style=flat-square" alt="License"></a>
</p>

`node-fence` is a framework-agnostic package which provides powerful ACL abilities to [Node.js](https://nodejs.org).<br>
It lets you easily manage ACL with a fluent API easy to learn and to work with. :rocket:

> :pray: This package is under active development, some breaking changes may occur before the first release.

<br>
<hr>
<br>

## Getting Started

This package is available in the Node Package Repository and can be easily installed with [npm](https://docs.npmjs.com/getting-started/what-is-npm) or [yarn](https://yarnpkg.com).

```bash
$ npm i --save node-fence
# or
$ yarn add node-fence
```

When you require the package in your file, it will give you access to the `Guard` class.<br>
This class is a facade for the package and should be instantiated with your configuration.

```javascript
const Guard = require('node-fence').Guard
const guard = new Guard(config)
```

:point_right: [Read the Official Documentation](https://github.com/Slynova-Org/node-fence/wiki)

<br>
## Contribution Guidelines

Any pull requests or discussions are welcome.<br>
Note that every pull request providing new feature or correcting a bug should be created with appropriate unit tests.
