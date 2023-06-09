# egg-ratelimiter3

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/egg-ratelimiter3.svg?style=flat-square
[npm-url]: https://npmjs.org/package/egg-ratelimiter3
[travis-image]: https://img.shields.io/travis/zdt1013/egg-ratelimiter3.svg?style=flat-square
[travis-url]: https://travis-ci.org/zdt1013/egg-ratelimiter3
[codecov-image]: https://img.shields.io/codecov/c/github/zdt1013/egg-ratelimiter3.svg?style=flat-square
[codecov-url]: https://codecov.io/github/zdt1013/egg-ratelimiter3?branch=master
[david-image]: https://img.shields.io/david/zdt1013/egg-ratelimiter3.svg?style=flat-square
[david-url]: https://david-dm.org/zdt1013/egg-ratelimiter3
[snyk-image]: https://snyk.io/test/npm/egg-ratelimiter3/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/egg-ratelimiter3
[download-image]: https://img.shields.io/npm/dm/egg-ratelimiter3.svg?style=flat-square
[download-url]: https://npmjs.org/package/egg-ratelimiter3

<!--
Description here.
-->

## Install

```bash
$ npm i egg-ratelimiter3 --save
or
$ pnpm add egg-ratelimiter3
```

## Usage

```js
// {app_root}/config/plugin.js
exports.ratelimiter = {
  enable: true,
  package: 'egg-ratelimiter',
};
```

## Configuration

```js
// {app_root}/config/config.default.js
// must set redis config
exports.redis ={
  client:...
}
exports.ratelimiter = {

}
```

see [config/config.default.js](config/config.default.js) for more detail.

## Example

<!-- example here -->

## Questions & Suggestions

Please open an issue [here](https://github.com/zdt1013/egg-ratelimiter3/issues).

## Thanks
[rolling-rate-limiter](https://github.com/peterkhayes/rolling-rate-limiter)

## License

[MIT](LICENSE)
