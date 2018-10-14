# VueVisible

v-visible directive for VueJS (2.x)

## Demo
A jsFiddle live demo: https://jsfiddle.net/fcpc6utm/

## About

This plugins adds a v-visible directive (similar to the native v-show) that changes the `visibility` style of the applied element (hidden or visible).

## Install

With npm:

```console
$ npm install --save vue-visible
```

With CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/vue-visible@1/dist/v-visible.min.js"></script>
```

## Usage

If you're using modules, first import it:

```js
import VueVisible from 'vue-visible';

Vue.use(VueVisible);
```

Then in your template just use the directive:

```html
<div v-visible="myCondition">I'm visible</div>
```

Or if you're not using modules, just include the js:

```html
<script src="node_modules/vue-visible/dist/v-visible.js"></script>
```
```html
<div v-visible="myCondition">I'm visible</div>
```
