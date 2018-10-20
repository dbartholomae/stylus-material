# stylus-material@1.4.3
[![npm version](https://badge.fury.io/js/stylus-material.svg)](https://npmjs.org/package/stylus-material)
[![dependency status](https://david-dm.org/dbartholomae/stylus-material.svg?theme=shields.io)](https://david-dm.org/dbartholomae/stylus-material)
[![devDependency status](https://david-dm.org/dbartholomae/stylus-material/dev-status.svg)](https://david-dm.org/dbartholomae/stylus-material#info=devDependencies)
[![Gitter](https://badges.gitter.im/dbartholomae/stylus-material.svg)](https://gitter.im/dbartholomae/stylus-material) [![Greenkeeper badge](https://badges.greenkeeper.io/dbartholomae/stylus-material.svg)](https://greenkeeper.io/) 

A collection of stylus mixins for material design. This is basically a port of the static parts of
[materialize](https://github.com/Dogfalo/materialize/) to
[Stylus](https://github.com/stylus/stylus/) using Mixins.

Here's [the documentation](https://rawgit.com/dbartholomae/stylus-material/v1.4.3/docs/index.html).

## Installation
Install with `npm`:
```sh
npm install stylus-material --save
```
 
## Usage
```html
...
<footer>
  <ul>
    <li>Imprint</li>
    <li>Privacy</li>
    <li>Terms and Conditions</li>
  </ul>
</footer>
...
```

```styl
@require "../node_modules/stylus-material"
  
footer
  sm-navbar()

  & ul
    sm-horizontal-list('—')
```

Find examples of all components in the `docs` folder.

## Library size
This library uses mostly mixins, therefore only what you actually use will increase your filesize.
Due to use of mixins, there will be a lot of repeated css in the output. If you don't already, make
sure you serve your css gzipped.  
