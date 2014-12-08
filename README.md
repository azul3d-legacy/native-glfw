What is this?
=============

- Go bindings to GLFW.
- This repository is mirroring [go-gl](http://github.com/go-gl/glfw3)'s `devel_glfw3.1` branch currently.
- This has versioned import paths that guarantee API-backwards compatability.
- Azul3D uses this import path to ensure that old code still builds fine.

Versions
============

- v4
  - `import "azul3d.org/native/glfw.v4"`
  - Reference in your code as `glfw`.
  - Bindings to GLFW _development_ version 3.1.
  - `devel_glfw3.1@c9b99f05633949d5e44a138875b1bd9d588edc27`
- v3
  - `import "azul3d.org/native/glfw.v3"`
  - Reference in your code as `glfw3`.
  - Bindings to GLFW _development_ version 3.1.
- v3.1
  - Use v3 instead, exposing v3.1 was a mistake (_v3 is 100% identical_).
