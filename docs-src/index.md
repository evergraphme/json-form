---
layout: page.11ty.cjs
title: <json-form> ⌲ Home
---

# &lt;json-form>

`<json-form>` is an awesome element. It's a great introduction to building web components with LitElement, with nice documentation site as well.

## As easy as HTML

<section class="columns">
  <div>

`<json-form>` is just an HTML element. You can it anywhere you can use HTML!

```html
<json-form></json-form>
```

  </div>
  <div>

<json-form></json-form>

  </div>
</section>

## Configure with attributes

<section class="columns">
  <div>

`<json-form>` can be configured with attributed in plain HTML.

```html
<json-form name="HTML"></json-form>
```

  </div>
  <div>

<json-form name="HTML"></json-form>

  </div>
</section>

## Declarative rendering

<section class="columns">
  <div>

`<json-form>` can be used with declarative rendering libraries like Angular, React, Vue, and lit-html

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;json-form&gt;</h2>
    <json-form .name=${name}></json-form>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;json-form&gt;</h2>
<json-form name="lit-html"></json-form>

  </div>
</section>
