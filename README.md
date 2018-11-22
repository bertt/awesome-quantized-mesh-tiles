# awesome-quantized-mesh-tiles [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Awesome implementations of the quantized mesh tiles specification

## Format

https://github.com/AnalyticalGraphicsInc/quantized-mesh


## Encoders and decoders

- https://github.com/loicgasser/quantized-mesh-tile - Quantized-Mesh encoder/decoder and topology builder (Python)

- https://github.com/bertt/quantized-mesh-tile-cs - Quantized-Mesh decoder (C#)

- https://github.com/kjartab/qmesh - qmesh (Javascript)

- https://github.com/heremaps//quantized-mesh-decoder - decoder for the Quantized Mesh format (Javascript)


## Tile generators

- https://github.com/tum-gis/cesium-terrain-builder-docker - Dockerfile for the geo-data/cesium-terrain-builder app with quantized mesh support.

- https://github.com/heremaps/tin-terrain - tin-terrain dem2tintiles

- https://github.com/geoadmin/3d-forge - Read/Write quantized-mesh tiles

- https://github.com/geo-data/cesium-terrain-builder - A C++ library and associated command line tools designed to create terrain tiles for use in the Cesium JavaScript library

## Servers

- https://github.com/geo-data/cesium-terrain-server - A basic server for serving up filesystem based tilesets representing Cesium.js terrain models

## Visualisation

- http://cesiumjs.org/Cesium/Apps/Sandcastle/index.html - Cesium Sandcastle

- https://github.com/AnalyticalGraphicsInc/cesium - Cesium (Javascript)

- https://github.com/heremaps/quantized-mesh-viewer - Render custom quantized mesh tiles in Cesium.js and debug individual tiles using THREE.js renderer.


# Blogs

- Fast Cesium terrain rendering with the new quantized-mesh output of the opensource CesiumTerrainBuilder tool - https://www.linkedin.com/pulse/fast-cesium-terrain-rendering-new-quantized-mesh-output-alvaro-huarte/

- Visualizing Terrains with Cesium - https://bertt.wordpress.com/2016/12/08/visualizing-terrains-with-cesium/

## Datasets

- World terrain dataset by Analytical Graphics, Inc. (AGI)

```
$ curl 'https://assets.cesium.com/1/11/2148/1501.terrain?v=1.1.0' -H 'Accept: application/vnd.quantized-mesh,application/octet-stream;q=0.9,*/*;q=0.01,*/*;access_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiJkNDhkYmU1My04ZGQxLTQzNDgtOWUzOC05NmM0ZmY3NjU4ODEiLCJpZCI6MjU5LCJhc3NldHMiOnsiMSI6eyJ0eXBlIjoiVEVSUkFJTiIsImV4dGVuc2lvbnMiOlt0cnVlLHRydWUsdHJ1ZV19fSwic3JjIjoiNzkzNTg3YTEtYTk5Yi00ZGQ2LWJiODctMGJjNDMyNmQ1ODUwIiwiaWF0IjoxNTQxNTc4OTMxLCJleHAiOjE1NDE1ODI1MzF9.zZuQxTqsnyOPG_Mzr3-ZBEN7gHEELhvB3FhmzraL6Pg' --compressed
```

