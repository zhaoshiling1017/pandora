![](https://user-images.githubusercontent.com/418820/33816754-3e528ad8-de76-11e7-8558-bfad8b75b4d9.png)

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/midwayjs/pandora/blob/master/LICENSE)
[![GitHub tag](https://img.shields.io/github/tag/midwayjs/pandora.svg)]()
[![Build Status](https://travis-ci.org/midwayjs/pandora.svg?branch=develop)](https://travis-ci.org/midwayjs/pandora)
[![Test Coverage](https://img.shields.io/codecov/c/github/midwayjs/pandora/master.svg)](https://codecov.io/gh/midwayjs/pandora/branch/master)
[![Package Quality](http://npm.packagequality.com/shield/pandora.svg)](http://packagequality.com/#?package=pandora)
[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/)
[![Known Vulnerabilities](https://snyk.io/test/npm/pandora/badge.svg)](https://snyk.io/test/npm/pandora)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/midwayjs/pandora/pulls)

## Installation

```bash
$ npm install pandora@latest --save
```

Node.js >= 8.0.0 required.

## Docs

* 中文文档 <http://www.midwayjs.org/pandora/zh-cn/>
* English documents <http://www.midwayjs.org/pandora/en/>

## What is Pandora.js ?

As a consequence of years of experiences on enterprise Node.js applications management, Midway team from Alibaba open-sourced Pandora.js finally. It is an application manager integrates many capabilities like monitoring, debugging, resiliency. You are more than welcome to use it, as well as build your operation infrastructure upon it.

The main concepts of Pandora.js are:

1. Manageable
  * Standard management capabilities of applications, processes and basic services (such as middleware).
  * Graceful online/offline.
  * Inter-process object proxying.
2. Measurable
  * Be able to measure different aspects of applications.
  * Support tons of metrics types, gauge, counter, meter, histogram, etc.
3. Traceable
  * Be able to trace the whole execution stack, inspect applications at runtime.
  * Support tons of 3rd party middlewares, MySQL, redis, etc. 
  * Compatible with Open-Tracing standard

The data can be achieved via RESTFul API or local file system. It is super easy to integrate it with your monitoring system.

## Features

- ✔︎ Built-in process management
- ✔︎ Dev Ops customization
- ✔︎ Provide Metrics and Standard OpenTracing Implementation
- ✔︎ Support lots of web frameworks

## How to Contribute

Please let us know how can we help. Do check out [issues](https://github.com/midwayjs/pandora/issues) for bug reports or suggestions first.

To become a contributor, please follow our [contributing guide](CONTRIBUTING.md).

## License

[MIT](LICENSE)
