# scipy2015
Notebooks for my talk.

## How to use

All notebooks are optimized in layout for 'presentation mode'. I highly recommend @damianavila 's notebook plugin `RISE` to enable one-click launch of the presentation without command-line conversions to HTML required.
You can find it here:
https://github.com/damianavila/RISE

## Issues

### Parallel use case

I had not enough time at the end, so I forgot to switch to presentation mode for the "Shortest parallel computation use case", which looked ugly. Switch the presentation mode on with Damian's plugin and things make much more sense. Or, alternatively, delete or cut out the markdown to have the code be closer to each other. Contact me for any questions (twitter: @michaelaye)

### What I had no time for

My upcoming toolset that will be integrated in one way or another into planetarypy. Beginnings are visible at https://github.com/michaelaye/planetpy .
* Spicer
  * Calculate and integrate solar irradiation on any surface of the major planetary bodies in the solar system. It's based on SPICE, so, if there's a kernel, it will work.
  * Py(Geo)Raster (still thinking about best name).
    * A convenience interface that combines SPICE and GDAL to perform:
        * Coordinate conversions like pixel_to_meter, meter_to_lonlat
        * Calculations for location the solar azimuth for images. (Important for understanding terrain in images).

