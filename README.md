# OpenApi3-TS

TypeScript library to help building OpenAPI 3.x compliant API contracts.

[![Coverage Status](https://coveralls.io/repos/github/metadevpro/@devtea2027/repudiandae-sunt-blanditiis-explicabo/badge.svg?branch=master)](https://coveralls.io/github/metadevpro/@devtea2027/repudiandae-sunt-blanditiis-explicabo?branch=master)
[![Known Vulnerabilities](https://snyk.io/test/github/metadevpro/@devtea2027/repudiandae-sunt-blanditiis-explicabo/badge.svg?targetFile=package.json)](https://snyk.io/test/github/metadevpro/@devtea2027/repudiandae-sunt-blanditiis-explicabo?targetFile=package.json)
[![npm version](https://badge.fury.io/js/@devtea2027/repudiandae-sunt-blanditiis-explicabo.svg)](http://badge.fury.io/js/@devtea2027/repudiandae-sunt-blanditiis-explicabo)

[![NPM](https://nodei.co/npm/@devtea2027/repudiandae-sunt-blanditiis-explicabo.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/@devtea2027/repudiandae-sunt-blanditiis-explicabo/)

## Version 4

*Breaking change notice:*

Version 4.0 Adds explicit support for OAS 3.0 and OAS 3.1 as separate implementations.

### To use version 3.1 import

```js
import { oas31 } from '@devtea2027/repudiandae-sunt-blanditiis-explicabo';
```

Or directly import from subpath:

```js
import { OpenAPIObject, OpenApiBuilder } from '@devtea2027/repudiandae-sunt-blanditiis-explicabo/oas31';
```

### To use version 3.0 import

```js
import { oas30 } from '@devtea2027/repudiandae-sunt-blanditiis-explicabo';
```

Or directly import from subpath:

```js
import { OpenAPIObject, OpenApiBuilder } from '@devtea2027/repudiandae-sunt-blanditiis-explicabo/oas30';
```

## Includes

* `/src/model` TS typed interfaces for helping building a contract.
* `/src/dsl` Fluent DSL for building a contract.

## Install

Install package via **npm**:

```bash
npm i --save @devtea2027/repudiandae-sunt-blanditiis-explicabo
```

## Versions and Changelog

See [changelog](Changelog.md).

## References

* OpenAPI spec 3.1.0. [https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.1.0.md](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.1.0.md)

## License

Licensed under the MIT License.

## Credits

**Contact:** Pedro J. Molina | github: [pjmolina](https://github.com/pjmolina) | twitter: [pmolinam](https://twitter.com/pmolinam)

(c) 2017-2023. [Pedro J. Molina](http://pjmolina.com) at Metadev S.L. [https://metadev.pro](https://metadev.pro) & contributors.
