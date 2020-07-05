# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.1.0](https://github.com/webpack-contrib/worker-loader/compare/v1.1.1...v2.1.0) (2020-07-05)


### ⚠ BREAKING CHANGES

* minimum supported Node.js version is `10.13`
* webpack@3 is not supported

### Features

* add the `workerType` option (replaces [#178](https://github.com/webpack-contrib/worker-loader/issues/178)) ([#247](https://github.com/webpack-contrib/worker-loader/issues/247)) ([f03498d](https://github.com/webpack-contrib/worker-loader/commit/f03498d22c6a3737b724c51bdfb56627e33b57b2))


### Bug Fixes

* **package:** homepage URL typo ([#130](https://github.com/webpack-contrib/worker-loader/issues/130)) ([ceabf74](https://github.com/webpack-contrib/worker-loader/commit/ceabf74d81b9612325355b0b4e9990971eb1966b))


* support webpack 5 ([#224](https://github.com/webpack-contrib/worker-loader/issues/224)) ([4f607ed](https://github.com/webpack-contrib/worker-loader/commit/4f607edc870f19b1ec5edb728c4032245601e4ed))
* update ([#243](https://github.com/webpack-contrib/worker-loader/issues/243)) ([3500f14](https://github.com/webpack-contrib/worker-loader/commit/3500f14083b5ca2bb953b2919ec1ffc7bc373b2b))

<a name="1.1.1"></a>
## [1.1.1](https://github.com/webpack-contrib/worker-loader/compare/v1.1.0...v1.1.1) (2018-02-25)


### Bug Fixes

* **index:** add `webpack >= v4.0.0` support ([#128](https://github.com/webpack-contrib/worker-loader/issues/128)) ([d1a7a94](https://github.com/webpack-contrib/worker-loader/commit/d1a7a94))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/webpack-contrib/worker-loader/compare/v1.0.0...v1.1.0) (2017-10-24)


### Features

* add `publicPath` support (`options.publicPath`) ([#31](https://github.com/webpack-contrib/worker-loader/issues/31)) ([96c6144](https://github.com/webpack-contrib/worker-loader/commit/96c6144))



<a name="1.0.0"></a>
## [1.0.0](https://github.com/webpack-contrib/worker-loader/compare/v0.8.0...v1.0.0) (2017-09-25)


### Features

* add `options` validation (`schema-utils`) ([#78](https://github.com/webpack-contrib/worker-loader/issues/78)) ([5e2f5e6](https://github.com/webpack-contrib/worker-loader/commit/5e2f5e6))
* support loading node core modules ([#76](https://github.com/webpack-contrib/worker-loader/issues/76)) ([edcda35](https://github.com/webpack-contrib/worker-loader/commit/edcda35))


### BREAKING CHANGES

* loader-utils upgrade to > 1.0 is not backwards
compatible with previous versions
