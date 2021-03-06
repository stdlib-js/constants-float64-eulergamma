<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Euler-Mascheroni Constant

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> The [Euler-Mascheroni][eulergamma] constant.

<section class="intro">

The [Euler-Mascheroni][eulergamma] constant `gamma` (also known as "Euler's constant" or "the Euler constant") is defined as the limit of the sequence

<!-- <equation class="equation" label="eq:eulergamma_constant" align="center" raw="\gamma = \lim_{n\to\infty} \left( \sum_{k=1}^n \frac{1}{k} - \ln n \right)" alt="Equation for the Euler-Mascheroni constant."> -->

<div class="equation" align="center" data-raw-text="\gamma = \lim_{n\to\infty} \left( \sum_{k=1}^n \frac{1}{k} - \ln n \right)" data-equation="eq:eulergamma_constant">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@5d87cc7cb2c58aeb732872f89562d2c89571cc8a/lib/node_modules/@stdlib/constants/float64/eulergamma/docs/img/equation_eulergamma_constant.svg" alt="Equation for the Euler-Mascheroni constant.">
    <br>
</div>

<!-- </equation> -->

</section>

<!-- /.intro -->

<section class="installation">

## Installation

```bash
npm install @stdlib/constants-float64-eulergamma
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

</section>

<section class="usage">

## Usage

```javascript
var GAMMA = require( '@stdlib/constants-float64-eulergamma' );
```

#### GAMMA

The [Euler-Mascheroni][eulergamma] constant.

```javascript
var bool = ( GAMMA === 0.5772156649015329 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better example -->

<!-- eslint no-undef: "error" -->

```javascript
var GAMMA = require( '@stdlib/constants-float64-eulergamma' );

console.log( GAMMA );
// => 0.5772156649015329
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-float64-eulergamma.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-float64-eulergamma

[test-image]: https://github.com/stdlib-js/constants-float64-eulergamma/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/constants-float64-eulergamma/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-float64-eulergamma/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-float64-eulergamma?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-float64-eulergamma.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-float64-eulergamma/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-float64-eulergamma/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-float64-eulergamma/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-float64-eulergamma/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-float64-eulergamma/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-float64-eulergamma/main/LICENSE

[eulergamma]: http://mathworld.wolfram.com/Euler-MascheroniConstant.html

</section>

<!-- /.links -->
