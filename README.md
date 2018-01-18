# Vega Library Clone

This library is a drop-in replacement for the [Vega library browser code](https://github.com/vega/vega), but without any external dependencies, and without the `require('canvas')` and `require('canvas-prebuilt')`.

## Usage
* in `package.json`, use `"vega-nocanvas"` instead of `"vega"`.

## Updating
* Download the latest `vega.zip` file from [Vega releases page](https://github.com/vega/vega/releases)
* Copy `vega.js` from vega.zip into the root
* `npm run build`  (this will update package.json's version and remove require(canvas) statements)
* `git commit -a`
* `git push`
* `npm publish --access public`
