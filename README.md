# geojson-stream

Stream features into and out of [GeoJSON](http://geojson.org/) objects
and Feature Collections. Little more than [JSONStream](https://github.com/dominictarr/JSONStream)
with pre-filled settings.

## usage

    npm install --save geojson-stream

## api

### `geojsonStream.stringify()`

Returns a transform stream that accepts GeoJSON Feature objects and emits
a stringified FeatureCollection

### `geojsonStream.parse()`

Returns a transform stream that accepts a GeoJSON FeatureCollection as a stream
and emits Feature objects
