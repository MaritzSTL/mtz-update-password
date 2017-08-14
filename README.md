[![Build Status](https://img.shields.io/travis/MaritzSTL/mtz-update-password/master.svg?style=flat-square)](https://travis-ci.org/MaritzSTL/mtz-update-password)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/MaritzSTL/mtz-update-password)

# \<mtz-update-password\>

Takes a password in from the user and validates it against a set of requirements.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../iron-icons/iron-icons.html">
    <link rel="import" href="mtz-update-password.html">

    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<mtz-update-password
  min-symbols="2"
  min-upper="2"
  auto-validate
></mtz-update-password>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
