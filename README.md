## GLTF Loder

To import geometries from a GLTF file  
Warning : the project must contain ThreeJS 0.140

## Installation
```sh
$ npm install https://github.com/codeurdenuit/GLTFLoader.git#main
```

## How to use it
```sh
$ import GLTFLoader from 'codeurdenuit/GLTFLoader'

const geometries = await GLTFLoader.loadGeometry('mesh.glb')

```