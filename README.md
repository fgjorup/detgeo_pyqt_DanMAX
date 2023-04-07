# detgeo_pyqt

Detector geometry in pyqtgraph
# detector_geometry
#### A tool to project X-ray diffraction cones on a detector screen at different geometries (tilt, rotation, offset) and X-ray energies
 - Main application is to visualize the maximum achievable resolution at a given geometry.
 - The math used is not meant to bring people to the moon but to provide a quick and simple preview.
 - The module building code is designed for [Dectris](https://www.dectris.com) [Pilatus3](https://www.dectris.com/detectors/x-ray-detectors/pilatus3/) and [Eiger2](https://www.dectris.com/detectors/x-ray-detectors/eiger2/) Detectors but one-module systems like the [Bruker](https://www.bruker.com/en.html) [Photon II](https://www.bruker.com/en/products-and-solutions/diffractometers-and-scattering-systems/single-crystal-x-ray-diffractometers/sc-xrd-components/detectors.html) are possible as well.
## It uses:
 - [python3](https://www.python.org)
 - [numpy](https://numpy.org)
 - [PyQt6](https://www.riverbankcomputing.com/software/pyqt/)
 - [PyQtGraph](https://pyqtgraph.readthedocs.io/en/latest/)
 - [Contourpy](https://contourpy.readthedocs.io/en/v1.0.7/)

## Short how-to:
 - Choose detector and model from the menu.
 - Pick reference from the menu to plot its contours.
 - Use the units you are the most comfortable with.
 - Hover over the grey line at the top to show the sliders.
  - Click it to make it stay open.
  - Move it around but don't lose it!
 - Drag the sliders to change energy and geometry.

## Latest update:
  - 2023-03-23 Update: uses pyqt6 and pyqtgraph, dropped matplotlib backend

## Here's an example showing a rotated Eiger2 4M:
![detgeo](Sample.png)

##### I hope this turns out to be useful for someone!
