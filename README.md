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

# lowercase

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Convert a string to lowercase.

<section class="intro">

</section>

<!-- /.intro -->

<section class="installation">

## Installation

```bash
npm install @stdlib/string-lowercase
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].
-   To use as a general utility for the command line, install the corresponding [CLI package][cli-section] globally.

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

</section>

<section class="usage">

## Usage

```javascript
var lowercase = require( '@stdlib/string-lowercase' );
```

#### lowercase( str )

Converts a string to lowercase.

```javascript
var str = lowercase( 'bEEp' );
// returns 'beep'
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var lowercase = require( '@stdlib/string-lowercase' );

var str = lowercase( 'Beep' );
// returns 'beep'

str = lowercase( 'BeEp' );
// returns 'beep'

str = lowercase( 'Beep BOOP' );
// returns 'beep boop'

str = lowercase( '$**_Beep_BoOp_**$' );
// returns '$**_beep_boop_**$'

str = lowercase( '' );
// returns ''
```

</section>

<!-- /.examples -->

* * *

<section class="cli">

## CLI

<section class="installation">

## Installation

To use as a general utility, install the CLI package globally

```bash
npm install -g @stdlib/string-lowercase-cli
```

</section>

<!-- CLI usage documentation. -->

<section class="usage">

### Usage

```text
Usage: lowercase [options] [<string>]

Options:

  -h,    --help                Print this message.
  -V,    --version             Print the package version.
```

</section>

<!-- /.usage -->

<section class="examples">

### Examples

```bash
$ lowercase bEEp
beep
```

To use as a [standard stream][standard-streams],

```bash
$ echo -n 'bEEp' | lowercase
beep
```

</section>

<!-- /.examples -->

</section>

<!-- /.cli -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/string-uncapitalize`][@stdlib/string/uncapitalize]</span><span class="delimiter">: </span><span class="description">uncapitalize the first character of a string.</span>
-   <span class="package-name">[`@stdlib/string-uppercase`][@stdlib/string/uppercase]</span><span class="delimiter">: </span><span class="description">convert a string to uppercase.</span>

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

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/string-lowercase.svg
[npm-url]: https://npmjs.org/package/@stdlib/string-lowercase

[test-image]: https://github.com/stdlib-js/string-lowercase/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/string-lowercase/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/string-lowercase/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/string-lowercase?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/string-lowercase.svg
[dependencies-url]: https://david-dm.org/stdlib-js/string-lowercase/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[cli-section]: https://github.com/stdlib-js/string-lowercase#cli
[cli-url]: https://github.com/stdlib-js/string-lowercase/tree/cli
[@stdlib/string-lowercase]: https://github.com/stdlib-js/string-lowercase/tree/main

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/string-lowercase/tree/deno
[umd-url]: https://github.com/stdlib-js/string-lowercase/tree/umd
[esm-url]: https://github.com/stdlib-js/string-lowercase/tree/esm
[branches-url]: https://github.com/stdlib-js/string-lowercase/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/string-lowercase/main/LICENSE

[standard-streams]: https://en.wikipedia.org/wiki/Standard_streams

<!-- <related-links> -->

[@stdlib/string/uncapitalize]: https://github.com/stdlib-js/string-uncapitalize

[@stdlib/string/uppercase]: https://github.com/stdlib-js/string-uppercase

<!-- </related-links> -->

</section>

<!-- /.links -->
