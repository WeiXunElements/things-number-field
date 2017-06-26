# \<things-number-field\>

It formats according to the defined settings by entering a numeric value in the field.

Input value |  Value |  After formatting
--|---|--
10000| '0,0.0000'| '10,000.0000'
10000.23| '0,0'| '10,000'
-10000| '0,0.0'| '-10,000.0'
10000.1234| '0.000'| '10000.123'
-10000| '(0,0.0000)'| '(-10,000.0000)'
-0.23| '.00'| '-.23'
-0.23| '(.00)'| '(.23)'
0.23| '0.00000'| '0.23000'
1230974| '0.0a'| '1.2m'
1460| '0a'| '1k'
-104000| '0a'| '-104k'
1| '0o'| '1st'
52| '0o'| '52nd'
23| '0o'| '23rd'
100| '0o'| '100th'

## Element Description

Example:

```html
    <things-number-field format-with="#,###.000"></things-number-field>
```
*****

Example:

```html
    <things-number-field format-with="#,###.000">
      <h2>Hello things-number-field format</h2>
    </things-number-field>
```
*****

## Install Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## View Application

```
$ polymer serve
```

## Build Application

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

## Run Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
