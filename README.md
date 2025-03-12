# awesome-quantized-mesh-tiles [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Awesome implementations of the quantized mesh tiles specification (terrain tileset)

## Specification

https://github.com/AnalyticalGraphicsInc/quantized-mesh

## Tilesets

- Dutch AHN4 level 0-15 https://api.pdok.nl/kadaster/3d-basisvoorziening/ogc/v1_0/collections/digitaalterreinmodel/quantized-mesh. See [metadata](https://api.pdok.nl/kadaster/3d-basisvoorziening/ogc/v1_0/collections/digitaalterreinmodel) for details. 

- Corsica France level 0 - 15 https://storage.googleapis.com/ahp-research/maquette/corsica_5m/tiles2/layer.json

- Switzerland level 0-18 https://3d.geo.admin.ch/1.0.0/ch.swisstopo.terrain.3d/default/20200520/4326/layer.json. See the [documentation](https://api3.geo.admin.ch/services/sdiservices.html#terrain-service) for details.

## Encoders and decoders (Libraries)

- https://github.com/loicgasser/quantized-mesh-tile - Quantized-Mesh encoder/decoder and topology builder (Python)

- https://github.com/bertt/quantized-mesh-tile-cs - Quantized-Mesh decoder (C#)

- https://github.com/kjartab/qmesh - qmesh (Javascript)

- https://github.com/heremaps/quantized-mesh-decoder - decoder for the Quantized Mesh format (Javascript)

- https://github.com/kylebarron/quantized-mesh-encoder - fast Quantized Mesh encoder (Python)

## Tile generators (Tooling)

- https://github.com/Gaia3D/mago-3d-terrainer - mago-3d-terrainer

- https://github.com/Geodan/terrain - Docker images for creating Cesium Quantized mesh terrain tiles

- https://github.com/tum-gis/cesium-terrain-builder-docker - Dockerfile for the geo-data/cesium-terrain-builder app with quantized mesh support.

- https://github.com/ahuarte47/cesium-terrain-builder/tree/master-quantized-mesh - ctb-tile with Quantized Mesh support

- https://github.com/geoadmin/3d-forge - Read/Write quantized-mesh tiles

- https://github.com/geo-data/cesium-terrain-builder - A C++ library and associated command line tools designed to create terrain tiles for use in the Cesium JavaScript library

## Servers

- https://github.com/sogelink-research/ctod Cesium Terrain on Demand. Service for serving quantized mesh terrain tiles based on Cloud Optimized GeoTIFF (COG).

- https://github.com/geo-data/cesium-terrain-server - A basic server for serving up filesystem based tilesets representing Cesium.js terrain models

## Visualisation

- https://cesium.com/ - Terrain visualization in CesiumJS (https://github.com/CesiumGS/cesium) and Cesium Native (https://github.com/CesiumGS/cesium-native) for Unity3D, Unreal, Omniverse and O3DE.

- [QGIS](https://qgis.org/) - Support for quantized mesh terrain in 2D and 3D views since QGIS 3.40. Use "Scenes" item in Browser dock widget or "Scene" tab in the Data Source Manager window to define a connection to a quantized mesh dataset.

- https://github.com/timoore/vsgCs - Cesium native based client for Vulkan Scene Graph (VSG)

- Deck.gl - Loaders.gl https://github.com/visgl/loaders.gl/pull/729 

- Quantized mesh tile viewer - https://quantized-mesh-tile.readthedocs.io/en/latest/viewer.html?z=9&x=536&y=391&tileUrl=https://bertt.github.io/cesium_terrain/texel/ahn4/tiles/19/538140/416814.terrain?v=1.1.0

![image](https://github.com/bertt/awesome-quantized-mesh-tiles/assets/538812/725d9abf-cc55-4e97-9379-0f95d76a0883)

## Blogs

- 2023-07-27: Creating 3D terrain from Lidar data - https://bertt.wordpress.com/2023/07/27/create-3d-terrain-from-lidar-data/

- 2018-11-26: Visualizing terrains with Cesium - Part II  https://bertt.wordpress.com/2018/11/26/visualizing-terrains-with-cesium-ii/

- 2018-08-31: Free Terrain Tiles for Cesium https://www.maptiler.com/blog/2018/08/free-terrain-tiles-for-cesium.html

- 2018-01-11: Fast Cesium terrain rendering with the new quantized-mesh output of the opensource CesiumTerrainBuilder tool - https://www.linkedin.com/pulse/fast-cesium-terrain-rendering-new-quantized-mesh-output-alvaro-huarte/

- 2016-12-08: Visualizing Terrains with Cesium - https://bertt.wordpress.com/2016/12/08/visualizing-terrains-with-cesium/

- 2014-10-12: Creating 3D terrains with Cesium - http://blog.mastermaps.com/2014/10/3d-terrains-with-cesium.html

## Datasets

- MapTiler

Blog: https://www.maptiler.com/blog/2018/08/free-terrain-tiles-for-cesium.html

Sample tile: https://maps.tilehosting.com/data/terrain-quantized-mesh/9/536/391.terrain?key=wYrAjVu6bV6ycoXliAPl

- World terrain dataset by Analytical Graphics, Inc. (AGI)

- - https://bertt.github.io/cesium_terrain/texel/ahn4/ - Texel

<img width="1008" alt="Screenshot 2023-05-17 at 19 18 48" src="https://github.com/bertt/awesome-quantized-mesh-tiles/assets/538812/e5b18361-7618-4699-b183-a58adfcbaad1">

- Mount Ventoux on SketchFab based on MapTiler Quantized Mesh Tiles https://sketchfab.com/3d-models/ventoux-afb8aada3971440f99d3ad4361a059d3

![image](https://github.com/bertt/awesome-quantized-mesh-tiles/assets/538812/f4d81730-fa94-42cb-8681-2de688b973c6)




