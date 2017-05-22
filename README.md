[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/daKmoR/grain-overlay)
[![Polymer Version](https://img.shields.io/badge/polymer-v2-blue.svg)](https://www.polymer-project.org)

# \<grain-overlay\>

Opens more content on click.

## Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="grain-overlay.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<div style="width: 300px; height: 100px; background: #ccc; position: relative;">
	I am some element that has an overlay.
	Activate with click.
	<grain-overlay style="background: #fffda4;">
		I'm an overlay
	</grain-overlay>
</div>
```

## Installation

```sh
$ bower install --save daKmoR/grain-overlay
```

## Getting Started

Import the package.

```html
<link rel="import" href="/bower_components/grain-overlay/grain-overlay.html">
```

*For more information, see the API documentation.*

## Working on the Element

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.
* View the Element via `polymer serve`
* Run tests via `polymer test`
