# template-mixin
Mixin to extend a Polymer element and also override styles on the base element.

## Usage

```
<link rel="import" href="template-mixin.html">
<dom-module id="my-element">
<template>
    <style>
        ...
    </style>
    <script>
        class MyElement extends Polymer.TemplateMixin('paper-element') {
            ...
        }
    </script>
</template>         
</dom-module>

```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

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
