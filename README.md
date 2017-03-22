# \<things-number-field\>

필드에 숫자 형식의 값을 넣어 정의한 설정에 따라서 포맷함


##엘리먼트 설명

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
