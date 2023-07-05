# WebFont Ubuntu Mono

Package for integrating `Ubuntu Mono` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@wikiline/webfont-ubuntu-mono?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@wikiline/webfont-ubuntu-mono?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@wikiline/webfont-ubuntu-mono?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @wikiline/webfont-ubuntu-mono
```

## Usage (CSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```css
body {
    font-family: 'Ubuntu Mono', monospace;
}
```

### Importing

```css
@import "~@wikiline/webfont-ubuntu-mono/src/css/all.css";
@import "~@wikiline/webfont-ubuntu-mono/src/css/all-normal.css";
@import "~@wikiline/webfont-ubuntu-mono/src/css/all-italic.css";
```

To import specific fonts, you can use:

```css
@import "~@wikiline/webfont-ubuntu-mono/src/css/weight-400.css";
@import "~@wikiline/webfont-ubuntu-mono/src/css/weight-400-normal.css";
@import "~@wikiline/webfont-ubuntu-mono/src/css/weight-400-italic.css";
@import "~@wikiline/webfont-ubuntu-mono/src/css/weight-700.css";
@import "~@wikiline/webfont-ubuntu-mono/src/css/weight-700-normal.css";
@import "~@wikiline/webfont-ubuntu-mono/src/css/weight-700-italic.css";
```

Note: Also, each file is presented in a minimized form.

### Variables

Each font uses the following CSS variables to set the font display property with the default `swap` value if CSS
variables are not defined:

```css
:root {
    --font-display: swap;
    --font-display-ubuntu-mono: swap;
}
```

## Usage (SCSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```scss
body {
    font-family: 'Ubuntu Mono', monospace;
}
```

### Importing

```scss
@import "~@wikiline/webfont-ubuntu-mono/src/scss/all";
@import "~@wikiline/webfont-ubuntu-mono/src/scss/all-normal";
@import "~@wikiline/webfont-ubuntu-mono/src/scss/all-italic";
```

To import specific fonts, you can use:

```scss
@import "~@wikiline/webfont-ubuntu-mono/src/scss/weight-400";
@import "~@wikiline/webfont-ubuntu-mono/src/scss/weight-400-normal";
@import "~@wikiline/webfont-ubuntu-mono/src/scss/weight-400-italic";
@import "~@wikiline/webfont-ubuntu-mono/src/scss/weight-700";
@import "~@wikiline/webfont-ubuntu-mono/src/scss/weight-700-normal";
@import "~@wikiline/webfont-ubuntu-mono/src/scss/weight-700-italic";
```

### Variables

Each font uses the following SCSS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```scss
$font-display: swap;
$font-display-ubuntu-mono: swap;
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the SIL
Open Font License, v1.1. Some fonts use the Apache 2 license. The Ubuntu fonts use the Ubuntu Font License v1.0.
