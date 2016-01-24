# stylus-material@0.0.1
[![npm version](https://badge.fury.io/js/stylus-material.svg)](https://npmjs.org/package/stylus-material)  
[![dependency status](https://david-dm.org/dbartholomae/stylus-material.svg?theme=shields.io)](https://david-dm.org/dbartholomae/stylus-material)
[![devDependency status](https://david-dm.org/dbartholomae/stylus-material/dev-status.svg)](https://david-dm.org/dbartholomae/stylus-material#info=devDependencies)
[![Gitter](https://badges.gitter.im/dbartholomae/stylus-material.svg)](https://gitter.im/dbartholomae/stylus-material) 

__This will be really useless before version 1.0.0!__

A collection of stylus mixins for material design. This is basically a port of
[materialize](https://github.com/Dogfalo/materialize/) to
[Stylus](https://github.com/stylus/stylus/) using Mixins.
 
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
  
  footer ul
    sm-horizontal-list('—')
```

## Library size
This library uses mostly mixins, therefore only what you actually use will increase your filesize.
Due to use of mixins, there will be a lot of repeated css in the output. If you don't already, make
sure you serve your css gzipped.  
