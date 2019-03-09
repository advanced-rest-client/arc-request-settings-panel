[![Published on NPM](https://img.shields.io/npm/v/@advanced-rest-client/arc-request-settings-panel.svg)](https://www.npmjs.com/package/@advanced-rest-client/arc-request-settings-panel)

[![Build Status](https://travis-ci.org/advanced-rest-client/arc-request-settings-panel.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/arc-request-settings-panel)

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/advanced-rest-client/arc-request-settings-panel)

## &lt;arc-request-settings-panel&gt;

A settings panel with request settings


```html
<arc-request-settings-panel></arc-request-settings-panel>
```

### API components

This components is a part of [API components ecosystem](https://elements.advancedrestclient.com/)

## Usage
``
### Installation
```
npm install --save @advanced-rest-client/arc-request-settings-panel
```

### In an html file

```html
<html>
  <head>
    <script type="module">
      import '@advanced-rest-client/arc-request-settings-panel/arc-request-settings-panel.js';
    </script>
  </head>
  <body>
    <arc-request-settings-panel></arc-request-settings-panel>
  </body>
</html>
```

### In a Polymer 3 element

```js
import {PolymerElement, html} from '@polymer/polymer';
import '@advanced-rest-client/arc-request-settings-panel/arc-request-settings-panel.js';

class SampleElement extends PolymerElement {
  static get template() {
    return html`
    <arc-request-settings-panel></arc-request-settings-panel>
    `;
  }
}
customElements.define('sample-element', SampleElement);
```

### Installation

```sh
git clone https://github.com/advanced-rest-client/arc-request-settings-panel
cd api-url-editor
npm install
npm install -g polymer-cli
```

### Running the demo locally

```sh
polymer serve --npm
open http://127.0.0.1:<port>/demo/
```

### Running the tests
```sh
polymer test --npm
```
