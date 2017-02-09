![A brunch and the ress name](http://i.imgur.com/1sXtcsA.png)

Modern CSS reset

[![Build Status](https://travis-ci.org/filipelinhares/ress.svg?branch=master)](https://travis-ci.org/filipelinhares/ress) [![Size](https://badge-size.herokuapp.com/filipelinhares/ress/master/dist/ress.min.css.svg?color=orange&label=file%20size)](https://github.com/filipelinhares/ress/blob/master/dist/ress.min.css) [![npm](https://img.shields.io/npm/v/ress.svg)](http://npmjs.com/packages/ress)

## Installation
```sh
npm install --save ress
```
or
```sh
bower install --save ress
```

## Features
1. Apply `box-sizing: border-box;` in all elements.
2. Reset `padding` and `margin` in all elements.
3. Specify `background-repeat: no-repeat` in all elements and pseudo elements.
4. Inherit `text-decoration` and `vertical-align` to `::before` and `::after`.
5. Remove the `outline` when hovering in all browsers.
6. Specify `font-family: monospace` in code elements.
7. Reset `border-radius` in input elements.
8. Specify font inheritance of form elements.
9. Remove the default button styling in all browsers.
10. Specify textarea resizability to vertical.
11. Apply `cursor: pointer` to button elements.

## Crossbrowser
**ress** uses [Normalize.css](https://github.com/necolas/normalize.css) under the hood with some customizations to apply a solid base to start your stylesheet.

## Browser support
Inherit from [Normalize](https://github.com/necolas/normalize.css#browser-support)

## CDN
[**unpkg**](https://unpkg.com)
```sh
https://unpkg.com/ress/dist/ress.min.css
```

[**RawGit**](https://rawgit.com)
```sh
# Production
https://cdn.rawgit.com/filipelinhares/ress/master/dist/ress.min.css

# Development
https://rawgit.com/filipelinhares/ress/master/dist/ress.min.css
```

## License
[MIT](LICENSE.md) © Filipe Linhares
