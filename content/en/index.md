---
title: Index
version: 0.1
badge: 'Version 0.1'
createdAt: "2020-06-22"
updatedAt: "2020-06-22" 
description: ''
position: 1
category: ''
---

<badge> {{ document.updatedAt }} </badge>

{{ document.updatedAt }}

<pre> {{ document }} </pre>

Check the [Nuxt.js documentation](https://nuxtjs.org/guides/configuration-glossary/configuration-modules) for more information about installing and using modules in Nuxt.js.

## Installation

Add `@nuxtjs/xxx` dependency to your project:

<code-group>
  <code-block label="Yarn" active>

  ```bash
  yarn add @nuxtjs/xxx
  ```

  </code-block>
  <code-block label="NPM">

  ```bash[nuxt.config.js]
  npm install @nuxtjs/xxx
  ```

  </code-block>
</code-group>

Then, add `@nuxtjs/xxx` to the `modules` section of `nuxt.config.js`:

```js[nuxt.config.js]
{
  modules: [
    '@nuxtjs/xxx'
  ],
  xxx: {
    // Options
  }
}
```
