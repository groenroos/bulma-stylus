# Bulma Stylus

[![npm](https://img.shields.io/npm/v/bulma-stylus.svg)](https://www.npmjs.com/package/bulma-stylus)
[![npm](https://img.shields.io/npm/dm/bulma-stylus.svg)](https://www.npmjs.com/package/bulma-stylus)

This is a 1:1 Stylus translation of the [Bulma](http://bulma.io) CSS framework.

![Bulma Stylus: a Stylus translation of a Flexbox CSS framework](http://i.imgur.com/CemfgQf.png)

Bulma Stylus aims at 1:1 functional parity with the latest tagged version of [the original Sass-based Bulma](https://github.com/jgthms/bulma).

## Installation

If you simply want to include the built CSS file ([`/css/bulma.css`](https://github.com/groenroos/bulma-stylus/blob/master/css/bulma.css)), you can. However, 10 out of 10 times a better bet is to instead include [built CSS file of the original Bulma](https://github.com/jgthms/bulma/blob/master/css/bulma.css).

However, if you want the Stylus files in order to customize variables and include only certain components, you have two choices:

### Install from npm

```sh
npm install bulma-stylus
```

### Install from Bower

```sh
bower install bulma-stylus
```

## Documentation

Since Bulma Stylus is functionally identical to the original Bulma, you can refer to the original [Bulma documentation](http://bulma.io/documentation/overview/start/) for instructions, examples, syntax and browser support.

All variable and mixin names are the same. The only caveat is that if you wish to customize the `$colors` variable, you must adhere to the Stylus hash format.

## Bugs & support

Any bugs or support requests can be posted into [the GitHub issue tracker](https://github.com/groenroos/bulma-stylus/issues).

**Please note:** Bulma Stylus is simply a translation of Bulma from Sass to Stylus, with no corrections or deviations made. Therefore, before submitting a bug, please make sure the issue is actually related specifically to the translation, and the Sass edition of Bulma does not exhibit the same bug. If it does, please submit your issue to [Bulma's issue tracker](https://github.com/jgthms/bulma/issues) instead.

Similarly, any pull requests should only relate directly to the translation (translate a newer version of Bulma into Stylus, fix syntax errors). Any pull requests for new features or behavior fixes should go [directly to Bulma](https://github.com/jgthms/bulma/pulls).

## License

Released under the MIT license.
