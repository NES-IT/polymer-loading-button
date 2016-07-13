# \<polymer-loading-button\>

A polymer elements that aggregates [iron-ajax](https://github.com/PolymerElements/iron-ajax) and [paper-button](https://github.com/PolymerElements/paper-button), morphing the paper-button to a [paper-spinner](https://github.com/PolymerElements/paper-spinner) during the request and to a [iron-icon](https://github.com/PolymerElements/iron-icons) when the request completes.

Check out the [demo](https://neweasysoft.github.io/polymer-loading-button/) or see the [API reference](https://neweasysoft.github.io/polymer-loading-button/)

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
