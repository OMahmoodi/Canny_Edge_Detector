Edge detection of potential-field sources
Edge detection can provide useful information for potential field data interpretation. A contact between a magnetic source and its host rock, and deep-seated faults are two geological phenomena that can be observed by edges in potential field data. So, finding the edges which might be related to possible conduit to hydrothermal fluids (i.e. geological contacts and fault) may lead to the discovery of a mineral deposit.

Image processing techniques are widely used for edge detection for images. Such techniques can be used on magnetic and gravity grids to detect boundaries of magnetic and gravity sources. There are a number of algorithms used in geophysical software packages to create a map showing detected edges. With the recent increase in desire to use open-source libraries for geophysical data processing and mineral potential mapping, it is preferred for many to execute the edge detection step as one of the pre-processing steps in mineral potential mapping in Python.

This script reads a magnetic/gravity grid as a raster file and implement Canny edge detection algorithm on the image. The result can be represented as a raster file for which pixels with True values represent detected edges.