# THREE.VREffect as a module

[![Latest NPM release][npm-badge]][npm-badge-url]
[![License][license-badge]][license-badge-url]
[![Dependencies][dependencies-badge]][dependencies-badge-url]

I didn't like any of the existing solutions I could find for using VREffect in a modular js build. So I made this.

1. Install:
```bash
npm i -S three-vreffect-module
```

2. Use:
```javascript
import VREffect from 'three-vreffect-module';
const effect = new VREffect(renderer);
effect.setSize(window.innerWidth, window.innerHeight);
```

Converted from: https://github.com/mrdoob/three.js/blob/master/examples/js/effects/VREffect.js

Currently up to date with THREE r85

[npm-badge]: https://img.shields.io/npm/v/three-vreffect-module.svg
[npm-badge-url]: https://www.npmjs.com/package/three-vreffect-module
[license-badge]: https://img.shields.io/npm/l/three-vreffect-module.svg
[license-badge-url]: ./LICENSE.md
[dependencies-badge]: https://img.shields.io/david/halvves/three-vreffect-module.svg
[dependencies-badge-url]: https://david-dm.org/halvves/three-vreffect-module
