Leaflet.GeometryUtil
====================

[![Build Status](https://travis-ci.org/makinacorpus/Leaflet.GeometryUtil.png?branch=master)](https://travis-ci.org/makinacorpus/Leaflet.GeometryUtil)

* Tested with stable Leaflet 0.7.0

For Leaflet 1.0, some users encounter problems with closest method.

We plan to open a new branch for testing purpose soon !

Don't hesitate to submit issues or Pull Request if you detect something wrong.

Usage
-----

Using Node:

```
    npm install leaflet-geometryutil
```

Or browser:

```
    <script src="leaflet.geometryutil.js"></script>
```


Check out [online documentation](http://makinacorpus.github.io/Leaflet.GeometryUtil/).


Development
-----------

### Running tests in command-line

* Install [nodejs](http://nodejs.org) and [phantomjs](http://phantomjs.org)

```
    sudo apt-get install nodejs phantomjs
```

* Ready !

```
    npm test
```

Changelog
---------

### master ###

* Nothing changed yet.

### 0.6.0 ###

* Add nested arrays for `layer` param in `closest` method

### 0.5.1 ###

* Fix closestLayer to be able to work with GeoJSON nested layers
* Restrict closest method to Array and L.Polyline (L.Polygon extend L.Polyline)

### 0.5.0 ###

* Add function `layersWithin()` (#34, thanks @haoliangyu)
* Fix safety check on the ratio value in ``interpolateOnLine()` (#29, thanks @Marcussacapuces91)

### 0.4.0 ###

* Same version as v0.3.3, new release as v0.4.0 to keep numbering coherent as a new feature has been added

### 0.3.3 ###

* Add bearing and destination functions (thanks @doublestranded)

### 0.3.2 ###

* Use a soft dependency for Leaflet (thanks Erik Escoffier)

### 0.3.1 ###

* Make sure interpolateOnLine() always returns a L.LatLng object (thanks Justin Manley)

### 0.3.0 ###

* Added UMD style initialization (thanks @PerLiedman)
* Added readable distance (thanks @Mylen)
* Fix side effects on latlngs with `closest()` (thanks @AndrewIngram)

### 0.2.0 ###

* Locate point on line
* Rotate point around center
* Fixed bug if closest point was on last segment

### 0.1.0 ###

* Line subpart extraction
* Line lengths
* Angle and slope computation
* Line reverse
* Line interpolation

### 0.0.1 ###

* Initial working version


License
-------

* BSD New


Authors
-------

* [Benjamin Becquet](https://github.com/bbecquet)
* [Mathieu Leplatre](https://github.com/leplatrem)
* [Simon Thépot](https://github.com/djcoin)
* [Nhinze](https://github.com/nhinze)
* [Frédéric Bonifas](https://github.com/fredericbonifas)
* [Alexander Melard](https://github.com/mylen)

[![Makina Corpus](http://depot.makina-corpus.org/public/logo.gif)](http://makinacorpus.com)
