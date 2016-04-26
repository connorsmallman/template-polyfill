# template-polyfill

A polyfill for the HTML5 `<template>` tag.

The code is from Brian Blakely's [JSFiddle](http://jsfiddle.net/brianblakely/h3EmY/). Packaged up so that people can use it via npm.

## Usage

```sh
npm install template-polyfill
```

```js
require('template-polyfill')
```

You'll also need:

```html
<script>
// In your <head> tag
document.createElement('template');
</script>
```

```css
/* In your CSS */
template {
  display: none !important;
}
```
