# bvh to VRMA

This is a web application that converts BVH files to VRM animation files.

# Demo

A demo is available on GitHub Pages (in Japanese): https://vrm-c.github.io/bvh2vrma/

## Note

Conversion may fail depending on the input BVH file. There is no guarantee of the conversion result.

# To Develop

1. To start development locally, clone this repository.

        git clone https://github.com/icedwater/bvh2vrma

2. Install the necessary packages and start the development web server.

        yarn install && yarn dev

# VRM Animation

VRM Animation is a glTF extension for describing animations of humanoid models defined in VRM. More about the VRMA format can be found [here][vrma].
The full [specification][spec] offers more details.

# Licence

[MIT Licence][mitl]

[vrma]: https://vrm.dev/vrma/
[spec]: https://github.com/vrm-c/vrm-specification/blob/master/specification/VRMC_vrm_animation-1.0/README.md
[mitl]: LICENSE.txt
