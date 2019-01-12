<h1 align="center">
  funcy.js: A functional web-components wrapper
</h1>
<p align="center">
  <img src="https://i.imgur.com/1nJ9kJd.png" width="572" alt="example of code">
</p>

### Why 'funcy.js'?

Naming things is hard and 'funcy.js' (pronounced like funky.js) seemed like a [fun](http://www.badum-tish.com/), recognizable name.

### What is it?

funcy.js seeks to provide a functional way of defining web components, very much akin to [react](https://reactjs.org/)  [functional components](https://reactjs.org/docs/components-and-props.html#function-and-class-components) with [hooks](https://reactjs.org/docs/hooks-intro.html). This is as of right now *purely experimental*.

Proper documentation will follow soon. For now you may look at todo example in the examples folder or the following codepen:

https://codepen.io/michael-klein/pen/xmQZBx

### Installation

Using npm:

```js
npm install funcy-components
```

```js
import {defineComponent} from "funcy-components"
```

As ES6 module via hotlinking from unpkg:

```js
import {defineComponent} from "https://unpkg.com/funcy-components/dist/core.min.mjs"
```

or the full version with all hooks:

```js
import {defineComponent} from "https://unpkg.com/funcy-components/dist/full.min.mjs"
```

#### currently implemented hooks:

* __useReducer__
* __useState__
* __useEffect__
* useRenderer 
* usePreactHtm
* useAttribute
* useCSS
* useExposeMethod
