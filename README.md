# 📍 unrouting

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![bundle][bundle-src]][bundle-href]
[![Codecov][codecov-src]][codecov-href]
[![License][license-src]][license-href]
[![JSDocs][jsdocs-src]][jsdocs-href]

> Making filesystem routing universal

## 🚧 In development

This library is a work in progress and in active development.

- [ ] generic route parsing function with options to cover major filesystem routing patterns
  - [x] [Nuxt](https://github.com/nuxt/nuxt)
  - [ ] [unplugin-vue-router](https://github.com/posva/unplugin-vue-router)
- [ ] export capability for framework routers
  - [x] RegExp patterns
  - [ ] [`vue-router`](https://router.vuejs.org/) routes
  - [ ] [radix3](http://github.com/unjs/radix3)/[Nitro](https://nitro.unjs.io/) routes
  - [ ] [SolidStart](https://start.solidjs.com/core-concepts/routing)
  - [ ] [SvelteKit](https://kit.svelte.dev/docs/routing) routes
- [ ] support scanning FS (with optional watch mode)
- [ ] and more

## Usage

Install package:

```sh
# npm
npm install unrouting

# pnpm
pnpm install unrouting
```

```js
import {} from 'unrouting'
```

## 💻 Development

- Clone this repository
- Enable [Corepack](https://github.com/nodejs/corepack) using `corepack enable`
- Install dependencies using `pnpm install`
- Run interactive tests using `pnpm dev`

## License

Made with ❤️

Published under [MIT License](./LICENCE).

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/unrouting?style=flat&colorA=18181B&colorB=F0DB4F
[npm-version-href]: https://npmjs.com/package/unrouting
[npm-downloads-src]: https://img.shields.io/npm/dm/unrouting?style=flat&colorA=18181B&colorB=F0DB4F
[npm-downloads-href]: https://npm.chart.dev/unrouting
[codecov-src]: https://img.shields.io/codecov/c/gh/unjs/unrouting/main?style=flat&colorA=18181B&colorB=F0DB4F
[codecov-href]: https://codecov.io/gh/unjs/unrouting
[bundle-src]: https://img.shields.io/bundlephobia/minzip/unrouting?style=flat&colorA=18181B&colorB=F0DB4F
[bundle-href]: https://bundlephobia.com/result?p=unrouting
[license-src]: https://img.shields.io/github/license/unjs/unrouting.svg?style=flat&colorA=18181B&colorB=F0DB4F
[license-href]: https://github.com/unjs/unrouting/blob/main/LICENSE
[jsdocs-src]: https://img.shields.io/badge/jsDocs.io-reference-18181B?style=flat&colorA=18181B&colorB=F0DB4F
[jsdocs-href]: https://www.jsdocs.io/package/unrouting
