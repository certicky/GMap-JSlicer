GMap-JSlicer
============

Image to Google Maps powered by javascript

```
slicer = new JSlicer(document.getElementById('map'), 'myImage.png');
slicer.init();
```

This is not production ready and really should be only used as a code sample.  However is does work.

We take a IMG element of the image we want to mapify then use Canvas to generate the necessary tiles used by Google Maps when rendering.  The entire process is done client side in Javascript.

Eventually when Web Workers get better support for Canvas, we will use them to improve performance.

See it in the wild: http://gvgmaps.com/
