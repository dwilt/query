---
id: installation
title: Installation
---

You can install React Query with [NPM](https://npmjs.com),
[Yarn](https://yarnpkg.com), or a good ol' `<script>` via
[unpkg.com](https://unpkg.com).

### NPM

```bash
$ npm i react-query
# or
$ yarn add react-query
```

React Query is compatible with React v16.8+ and works with ReactDOM and React Native.

> Wanna give it a spin before you download? Try out the [simple](/docs/examples/simple) or [basic](/docs/examples/basic) examples!

### CDN

If you're not using a module bundler or package manager we also have a global ("UMD") build hosted on the [unpkg.com](https://unpkg.com) CDN. Simply add the following `<script>` tag to the bottom of your HTML file:

```html
<script src="https://unpkg.com/react-query/dist/react-query.production.min.js"></script>
```

Once you've added this you will have access to the `window.ReactQuery` object and its exports.

> This installation/usage requires the [React CDN script bundles](https://reactjs.org/docs/cdn-links.html) to be on the page as well.

### Requirements

React Query is optimized for modern browsers. It is compatible with the following browsers config

```
Chrome >= 73
Firefox >= 78
Edge >= 79
Safari >= 12.0
iOS >= 12.0
opera >= 53
```

> Depending on your environment, you might need to add polyfills. If you want to support older browsers, you need to transpile the library from `node_modules` yourselves.
