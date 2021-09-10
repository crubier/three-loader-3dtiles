<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [three-loader-3dtiles](./three-loader-3dtiles.md) &gt; [Runtime](./three-loader-3dtiles.runtime.md)

## Runtime interface

Runtime methods that can be used once a tileset is loaded

<b>Signature:</b>

```typescript
interface Runtime 
```

## Methods

|  Method | Description |
|  --- | --- |
|  [dispose()](./three-loader-3dtiles.runtime.dispose.md) | Dispose of all of the tileset's assets in memory. |
|  [getCameraFrustum(Camera)](./three-loader-3dtiles.runtime.getcamerafrustum.md) | Get the current camera frustum as mesh planes (for debugging purposes). |
|  [getLatLongHeightFromPosition(Vector3)](./three-loader-3dtiles.runtime.getlatlongheightfromposition.md) | When viewing a Geo-located tileset, get the [GeoCoord](./three-loader-3dtiles.geocoord.md) value from a world-space <code>Vector3</code>. |
|  [getPositionFromLatLongHeight(GeoCoord)](./three-loader-3dtiles.runtime.getpositionfromlatlongheight.md) | When viewing a Geo-located tileset, world-space <code>Vector3</code> from a [GeoCoord](./three-loader-3dtiles.geocoord.md)<!-- -->. |
|  [getStats()](./three-loader-3dtiles.runtime.getstats.md) | Get a reference to the probe.gl [Stats](https://github.com/uber-web/probe.gl/blob/master/docs/api-reference/stats/stats.md) object. |
|  [getTileBoxes()](./three-loader-3dtiles.runtime.gettileboxes.md) | Get the tile bounding boxes group when <code>debug: true</code> is set. |
|  [getTileset()](./three-loader-3dtiles.runtime.gettileset.md) | Get a reference to the loaders.gl [Tileset3D](https://github.com/visgl/loaders.gl/blob/master/modules/tiles/docs/api-reference/tileset-3d.md) object. |
|  [getTransform()](./three-loader-3dtiles.runtime.gettransform.md) | Get the current tileset transform. |
|  [setDebug(boolean)](./three-loader-3dtiles.runtime.setdebug.md) | Enable or disable deubg mode. |
|  [setElevationRange(range)](./three-loader-3dtiles.runtime.setelevationrange.md) | In point clouds when coloring by <code>PointCloudColoring.Elevation</code>, set the min/max elevation values - Default: <code>[0, 400]</code>. |
|  [setHideGround(boolean)](./three-loader-3dtiles.runtime.sethideground.md) | In point clouds wher the points are classified as <code>Ground</code>, hide the ground level points - Default: <code>false</code>. |
|  [setIntensityContrast(number)](./three-loader-3dtiles.runtime.setintensitycontrast.md) | In point clouds when coloring by <code>PointCloudColoring.Intensity</code>, set the contrast factor. Default: <code>1.0</code>. |
|  [setMaxIntensity(number)](./three-loader-3dtiles.runtime.setmaxintensity.md) | In point clouds when coloring by <code>PointCloudColoring.Intensity</code>, set the max intensity value - Default: <code>1.0</code> |
|  [setPointCloudColoring(PointCloudColoring)](./three-loader-3dtiles.runtime.setpointcloudcoloring.md) | In point clouds set the type of coloring used. See [PointCloudColoring](./three-loader-3dtiles.pointcloudcoloring.md) |
|  [setShading(Shading)](./three-loader-3dtiles.runtime.setshading.md) | Set the current shading mode for b3dm tiles. See [Shading](./three-loader-3dtiles.shading.md)<!-- -->. |
|  [setTransform(Matrix4)](./three-loader-3dtiles.runtime.settransform.md) | Set the tileset transform. Make sure <code>updateTransforms</code> is set to <code>true</code> (in [LoaderOptions](./three-loader-3dtiles.loaderoptions.md)<!-- -->). |
|  [setViewDistanceScale(number)](./three-loader-3dtiles.runtime.setviewdistancescale.md) | Set the current view distance scale. See [LoaderOptions](./three-loader-3dtiles.loaderoptions.md) |
|  [setWireframe(boolean)](./three-loader-3dtiles.runtime.setwireframe.md) | Enable or disable wireframe mode. |
|  [showTiles(boolean)](./three-loader-3dtiles.runtime.showtiles.md) | Show or hide the tile bounding boxes. |
|  [update(number, WebGLRenderer, Camera)](./three-loader-3dtiles.runtime.update.md) | Update the tileset for rendering. |
