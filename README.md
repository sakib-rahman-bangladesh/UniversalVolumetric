# volumetric

An open source format for streaming meshes and volumetric playback with extremely fast encode + decode.

Currently playback works in WebGL with three.js

Unity and Unreal support are easy though, get in touch if you're interested!

This format uses Corto for quantized mesh compression
https://github.com/cnr-isti-vclab/corto

Example:
node ./src/Encoder.js example.drcs
Extended Example: 25 FPS, 500 frames
node ./src/Encoder.js example.drcs 25 0 499

Input is a series of .crt files in a folder called "assets"
You can encode these with the corto executable
"assets" folder must be in the same working directory we are calling this script from

## Maintainers Wanted
If you are interested in open source volumetric encoding and playback, email me at shawmakesmagic@gmail.com :)
