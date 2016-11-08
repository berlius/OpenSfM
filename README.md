[![Build Status](https://travis-ci.org/mapillary/OpenSfM.svg?branch=master)](https://travis-ci.org/mapillary/OpenSfM)
OpenSfM
=======

you can pull [the container](https://hub.docker.com/r/berlius/opensfm/) :

```
docker pull berlius/opensfm
```
## Overview
[OpenSfM is a Structure from Motion library](https://github.com/mapillary/OpenSfM) written in Python on top of OpenCV. The library serves as a processing pipeline for reconstructing camera poses and 3D scenes from multiple images. It consists of basic modules for Structure from Motion (feature detection/matching, minimal solvers) with a focus on building a robust and scalable reconstruction pipeline. It also integrates external sensor (e.g. GPS, accelerometer) measurements for geographical alignment and robustness. A JavaScript viewer is provided to preview the models and debug the pipeline.

