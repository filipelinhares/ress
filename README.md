# ress
Modern CSS reset

[![BuildStatus](https://travis-ci.org/filipelinhares/ress?branch=master)](https://travis-ci.org/filipelinhares/ress)

## Installation
```sh
npm install --save ress
```

## Features
1. Apply `box-sizing: border-box;` in all elements.
2. Reset `padding` and `margin` in all elements.
3. Specify `background-repeat: no-repeat` in all elements.
4. Inherit `text-decoration` and `vertical-align` to `::before` and `::after`.
5. Remove the `outline` when hovering in all browsers.
6. Specify `font-family: monospace` in code elements.
7. Reset `border-radius` in input elements.
8. Specify font inheritance of form elements.
9. Remove the default button styling in all browsers.
10. Specify textarea resizability to vertical.

## Crossbrowser
**ress** uses [Normalize.css](https://github.com/necolas/normalize.css) under the hood with some customizations to apply a solid base to start your stylesheet.

## Browser support
Inherit from [Normalize](https://github.com/necolas/normalize.css#browser-support)

## License
[MIT](LICENSE.md) © Filipe Linhares
