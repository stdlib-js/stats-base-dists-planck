<!--

@license Apache-2.0

Copyright (c) 2025 The Stdlib Authors.

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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Planck

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Planck distribution.



<section class="usage">

## Usage

```javascript
import planck from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-planck@deno/mod.js';
```

You can also import the following named exports from the package:

```javascript
import { cdf, entropy, kurtosis, logcdf, logpmf, mean, median, mgf, mode, pmf, quantile, skewness, stdev, variance } from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-planck@deno/mod.js';
```

#### planck

Planck distribution.

```javascript
var dist = planck;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pmf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, lambda )`][@stdlib/stats/base/dists/planck/cdf]</span><span class="delimiter">: </span><span class="description">Planck distribution cumulative distribution function.</span>
-   <span class="signature">[`logcdf( x, lambda )`][@stdlib/stats/base/dists/planck/logcdf]</span><span class="delimiter">: </span><span class="description">Planck distribution logarithm of cumulative distribution function.</span>
-   <span class="signature">[`logpmf( x, lambda )`][@stdlib/stats/base/dists/planck/logpmf]</span><span class="delimiter">: </span><span class="description">Planck distribution logarithm of probability mass function (PMF).</span>
-   <span class="signature">[`mgf( t, lambda )`][@stdlib/stats/base/dists/planck/mgf]</span><span class="delimiter">: </span><span class="description">Planck distribution moment-generating function (MGF).</span>
-   <span class="signature">[`pmf( x, lambda )`][@stdlib/stats/base/dists/planck/pmf]</span><span class="delimiter">: </span><span class="description">Planck distribution probability mass function (PMF).</span>
-   <span class="signature">[`quantile( r, lambda )`][@stdlib/stats/base/dists/planck/quantile]</span><span class="delimiter">: </span><span class="description">Planck distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`entropy( lambda )`][@stdlib/stats/base/dists/planck/entropy]</span><span class="delimiter">: </span><span class="description">Planck distribution entropy.</span>
-   <span class="signature">[`kurtosis( lambda )`][@stdlib/stats/base/dists/planck/kurtosis]</span><span class="delimiter">: </span><span class="description">Planck distribution excess kurtosis.</span>
-   <span class="signature">[`mean( lambda )`][@stdlib/stats/base/dists/planck/mean]</span><span class="delimiter">: </span><span class="description">Planck distribution expected value.</span>
-   <span class="signature">[`median( lambda )`][@stdlib/stats/base/dists/planck/median]</span><span class="delimiter">: </span><span class="description">Planck distribution median.</span>
-   <span class="signature">[`mode( lambda )`][@stdlib/stats/base/dists/planck/mode]</span><span class="delimiter">: </span><span class="description">Planck distribution mode.</span>
-   <span class="signature">[`skewness( lambda )`][@stdlib/stats/base/dists/planck/skewness]</span><span class="delimiter">: </span><span class="description">Planck distribution skewness.</span>
-   <span class="signature">[`stdev( lambda )`][@stdlib/stats/base/dists/planck/stdev]</span><span class="delimiter">: </span><span class="description">Planck distribution standard deviation.</span>
-   <span class="signature">[`variance( lambda )`][@stdlib/stats/base/dists/planck/variance]</span><span class="delimiter">: </span><span class="description">Planck distribution variance.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
import objectKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@deno/mod.js';
import planck from 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-planck@deno/mod.js';

console.log( objectKeys( planck ) );
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

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2025. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-planck.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-planck

[test-image]: https://github.com/stdlib-js/stats-base-dists-planck/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/stats-base-dists-planck/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-planck/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-planck?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-planck.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-planck/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/stats-base-dists-planck/tree/deno
[deno-readme]: https://github.com/stdlib-js/stats-base-dists-planck/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/stats-base-dists-planck/tree/umd
[umd-readme]: https://github.com/stdlib-js/stats-base-dists-planck/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/stats-base-dists-planck/tree/esm
[esm-readme]: https://github.com/stdlib-js/stats-base-dists-planck/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/stats-base-dists-planck/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-planck/main/LICENSE

[@stdlib/stats/base/dists/planck/cdf]: https://github.com/stdlib-js/stats-base-dists-planck-cdf/tree/deno

[@stdlib/stats/base/dists/planck/entropy]: https://github.com/stdlib-js/stats-base-dists-planck-entropy/tree/deno

[@stdlib/stats/base/dists/planck/kurtosis]: https://github.com/stdlib-js/stats-base-dists-planck-kurtosis/tree/deno

[@stdlib/stats/base/dists/planck/logcdf]: https://github.com/stdlib-js/stats-base-dists-planck-logcdf/tree/deno

[@stdlib/stats/base/dists/planck/logpmf]: https://github.com/stdlib-js/stats-base-dists-planck-logpmf/tree/deno

[@stdlib/stats/base/dists/planck/mean]: https://github.com/stdlib-js/stats-base-dists-planck-mean/tree/deno

[@stdlib/stats/base/dists/planck/median]: https://github.com/stdlib-js/stats-base-dists-planck-median/tree/deno

[@stdlib/stats/base/dists/planck/mgf]: https://github.com/stdlib-js/stats-base-dists-planck-mgf/tree/deno

[@stdlib/stats/base/dists/planck/mode]: https://github.com/stdlib-js/stats-base-dists-planck-mode/tree/deno

[@stdlib/stats/base/dists/planck/pmf]: https://github.com/stdlib-js/stats-base-dists-planck-pmf/tree/deno

[@stdlib/stats/base/dists/planck/quantile]: https://github.com/stdlib-js/stats-base-dists-planck-quantile/tree/deno

[@stdlib/stats/base/dists/planck/skewness]: https://github.com/stdlib-js/stats-base-dists-planck-skewness/tree/deno

[@stdlib/stats/base/dists/planck/stdev]: https://github.com/stdlib-js/stats-base-dists-planck-stdev/tree/deno

[@stdlib/stats/base/dists/planck/variance]: https://github.com/stdlib-js/stats-base-dists-planck-variance/tree/deno

</section>

<!-- /.links -->
