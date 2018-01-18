# Vega Library Clone

This repository holds an unmodified compiled copy of the [Vega library browser code](https://github.com/vega/vega) (without the Canvas dependencies).

## Updating
* Download the latest `vega.zip` file from [Vega releases page](https://github.com/vega/vega/releases)
* Copy `vega.js` from vega.zip into the root
* `npm run build`  (this will update package.json's version and remove require(canvas) statements)
* `git commit -a`
* `git push`
* `npm publish --access public`
