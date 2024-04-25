# @odczynflnpm/eaque-nisi-eligendi [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Meet%20this%20awesome%20library&url=https://github.com/odczynflnpm/eaque-nisi-eligendi&via=nicolasvanhoren&hashtags=javascript,asyncawait,async,libraries,programming)

![logo](https://github.com/odczynflnpm/eaque-nisi-eligendi/raw/master/img/facebook_cover_photo_2_680.png)

[![GitHub Repo stars](https://img.shields.io/github/stars/nicolas-van/@odczynflnpm/eaque-nisi-eligendi?style=social)](https://github.com/odczynflnpm/eaque-nisi-eligendi/stargazers) [![Website](https://img.shields.io/website.svg?url=http%3A%2F%2Fnicolas-van.github.io%2F@odczynflnpm/eaque-nisi-eligendi)](https://nicolas-van.github.io/@odczynflnpm/eaque-nisi-eligendi)
[![Node.js CI](https://github.com/odczynflnpm/eaque-nisi-eligendi/workflows/Node.js%20CI/badge.svg)](https://github.com/odczynflnpm/eaque-nisi-eligendi/actions) [![npm](https://img.shields.io/npm/v/@odczynflnpm/eaque-nisi-eligendi)](https://www.npmjs.com/package/@odczynflnpm/eaque-nisi-eligendi) [![Coverage Status](https://coveralls.io/repos/github/nicolas-van/@odczynflnpm/eaque-nisi-eligendi/badge.svg?branch=master)](https://coveralls.io/github/nicolas-van/@odczynflnpm/eaque-nisi-eligendi?branch=master) [![](https://data.jsdelivr.com/v1/package/npm/@odczynflnpm/eaque-nisi-eligendi/badge)](https://www.jsdelivr.com/package/npm/@odczynflnpm/eaque-nisi-eligendi)

A modern JavaScript tooling library for asynchronous operations using async/await, promises and async generators.

This library is a modernized alternative to a lot of libraries like [Async.js](https://caolan.github.io/async/v3/) that were created using the legacy callback style to handle asynchronous operations. Its goal is to be as complete as any of those libraries while being built from the very beginning with async/await and promises in mind.

[See the documentation](https://nicolas-van.github.io/@odczynflnpm/eaque-nisi-eligendi).

* Exclusively uses async/await, promises and async generators in its code, tests and documentation.
* Has low bundle size.
* Has 100% code coverage.
* Bundled for ESM modules, CommonJS and UMD.
* Works in node >= 8 and in the vast majority of browsers (very old browser compatibility can be achieved using Babel and shims).
* Has Typescript support.

[![Stargazers repo roster for @nicolas-van/@odczynflnpm/eaque-nisi-eligendi](https://reporoster.com/stars/nicolas-van/@odczynflnpm/eaque-nisi-eligendi)](https://github.com/odczynflnpm/eaque-nisi-eligendi/stargazers)

## Installation

```bash
npm install --save @odczynflnpm/eaque-nisi-eligendi
```

Or use [jsDelivr](https://www.jsdelivr.com/package/npm/@odczynflnpm/eaque-nisi-eligendi) to get the UMD version. The content of the library will be available under the `modernAsync` global variable.

## Usage

```javascript
import { asyncMap, asyncSleep } from '@odczynflnpm/eaque-nisi-eligendi'

const array = [1, 2, 3]
const result = await asyncMap(array, async (v) => {
  await asyncSleep(10)
  return v * 2
})
console.log(result)
```

[See the documentation for the rest](https://nicolas-van.github.io/@odczynflnpm/eaque-nisi-eligendi).

## Migrating from version 1.X to version 2.X

[See the migration guide](https://github.com/odczynflnpm/eaque-nisi-eligendi/blob/master/version-1-to-2-guide.md).

## Changelog

[The changelog](https://github.com/odczynflnpm/eaque-nisi-eligendi/blob/master/CHANGELOG.md).

## Contribution Guide

[The contribution guide](https://github.com/odczynflnpm/eaque-nisi-eligendi/blob/master/CONTRIBUTING.md)

## License

[The license](https://github.com/odczynflnpm/eaque-nisi-eligendi/blob/master/LICENSE.md).
