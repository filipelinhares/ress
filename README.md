![A brunch and the ress name](https://i.imgur.com/NHz9ef3.png)

Modern CSS reset

[![Build Status](https://travis-ci.org/filipelinhares/ress.svg?branch=master)](https://travis-ci.org/filipelinhares/ress) [![Size](https://img.shields.io/bundlephobia/min/ress?color=orange)](https://github.com/filipelinhares/ress/blob/master/dist/ress.min.css) [![npm](https://img.shields.io/npm/v/ress.svg)](https://npmjs.com/ress)

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
12. Apply `tab-size: 4` in `html`.
13. Style `select` like a standard input.
14. Style `cursor` by aria attributes.

## Crossbrowser

**ress** uses [Normalize.css](https://github.com/necolas/normalize.css) under the hood with some customizations to apply a solid base to start your stylesheet.

## Browser support

Inherit from [Normalize](https://github.com/necolas/normalize.css#browser-support)

## CDN

[**unpkg**](https://unpkg.com)

```sh
https://unpkg.com/ress/dist/ress.min.css
```

[**jsDevlivr**](https://www.jsdelivr.com/)

```sh
# Production
https://cdn.jsdelivr.net/npm/ress@4.0.0/dist/ress.min.css

# Development
https://cdn.jsdelivr.net/gh/filipelinhares/ress@latest/dist/ress.min.css
```

## License

[MIT](LICENSE.md) © Filipe Linhares
