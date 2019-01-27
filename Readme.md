# Haip

"haip.*" are namespace based python packages for various purposes. We use namespaced packages to avoid conflicts with existing packages and projects.

Normally you should not get in touch with the base-package ("haip") at all but use the subpackages directly. A design goal is to keep these subpackages as independent as possible to be able to use them seperatly (as you normaly would expect from a global python package).

## Subpackages (ongoing)

* haip.config - a simple configuration manager for yaml based config files
