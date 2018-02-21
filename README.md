# VignetteShader
Simple horizontal / radial vignette shader for Three.js

```javascript
var vignette = new THREE.ShaderPass(THREE.VignetteShader);
vignette.uniforms[ "resolution" ].value = new THREE.Vector2( window.innerWidth, window.innerHeight );
vignette.uniforms[ "horizontal" ].value = true; // default is false
vignette.uniforms[ "radius" ].value = .8; // default is 0.75
vignette.uniforms[ "softness" ].value = .3; // default is 0.3
vignette.uniforms[ "gain" ].value = .3; // default is 0.9
```

