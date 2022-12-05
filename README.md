`ORG.IPEP:`
![GitHub release (latest by date)](https://img.shields.io/github/v/release/ImageProcessing-ElectronicPublications/pied)
![GitHub Release Date](https://img.shields.io/github/release-date/ImageProcessing-ElectronicPublications/pied)
![GitHub repo size](https://img.shields.io/github/repo-size/ImageProcessing-ElectronicPublications/pied)
![GitHub all releases](https://img.shields.io/github/downloads/ImageProcessing-ElectronicPublications/pied/total)
![GitHub](https://img.shields.io/github/license/ImageProcessing-ElectronicPublications/pied)  

# PIED

## Overview

A program that reconstructs an image from a palette using the error diffusion method.

## Dependencies

- OpenCV4
``` sh
sudo apt install libopencv-dev
```

## Install

``` sh
make
sudo make install
```

## Usage

``` sh
pied [input image file name] [output image file name] [palette image file name]
```

## Remarks

The palette image is 1px high and wide. `color_palette.png` is it.

## Origin

[Japanese README](README.jp.md).
