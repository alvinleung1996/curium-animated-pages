# \<curium-animated-pages\>

A component similar to neon-animated-pages with greater flexibility

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

Direct children of this component should mixin the Polymer.IronResizableBehavior inorder for the iron-resize notification to be properly spreaded.
Set "notifyResizeOnGrandchildren" to enable notifying resize on grandchildren, but it may slow down performance.
