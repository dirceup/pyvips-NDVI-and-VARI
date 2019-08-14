# pyvips-NDVI-and-VARI

Applies NDVI (Normalized Difference Vegetation Index) and VARI (Visible Atmospherically Resistant Index) Vegetation Index in NIR (near-infrared) and RGB orthophotos using **[libvips](https://libvips.github.io/libvips/)** image processing library and their [Python binding](https://github.com/libvips/pyvips).

It is a simplified and translated (from Ruby to Python) version of my project [tiled-vegetation-indices](https://github.com/dirceup/tiled-vegetation-indices/) where I demonstrate how to compute statistics from orthophoto thumbnails then use it to apply the index to [map tiles](https://en.wikipedia.org/wiki/Tiled_web_map).

## Running it:

Install [libvips](https://libvips.github.io/libvips/install.html) and [Python](https://www.python.org/). Then use PIP to install 'pyvips' and 'numpy' packages:

```
pip install pyvips
pip install numpy
```

Okay? Run the program:

```
python3 pyvips-vari-ndvi.py
```

_nir.png_ and _rgb.png_ orthophoto thumbnails will be processed and resulting _ndvi.png_ and _vari.png_ will be saved.

## Demo

### RGB → VARI
<img src="https://github.com/dirceup/pyvips-NDVI-and-VARI/blob/master/rgb.png" width="400"/> → <img src="https://github.com/dirceup/pyvips-NDVI-and-VARI/blob/master/vari.png" width="400"/>

### NIR → NDVI
<img src="https://github.com/dirceup/pyvips-NDVI-and-VARI/blob/master/nir.png" width="400"/> → <img src="https://github.com/dirceup/pyvips-NDVI-and-VARI/blob/master/ndvi.png" width="400"/>
