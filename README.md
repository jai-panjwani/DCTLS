# DCTL Scripts for DaVinci Resolve

This repository contains custom DCTL (DaVinci Resolve) scripts designed for advanced color transformations. These scripts integrate various color models and are optimized for use in professional post-production workflows.

## Scripts

### CF Tetra Upper/Lower.dctl

A modified version of The Tetra transformation that applies upper and lower boundary transformations using a tetrahedral color space structure. Tetra works as described by Steve Yedlin ASC, was originally implemented for Nuke by calvinsilly, ported to Fusion by EmberLightVFX, and is presented here as a DCTL for the ResolveFX DCTL plug-in.

### CF OKLAB (DWG).dctl

A DCTL script for converting and manipulating colors in the OKLAB space, designed specifically for DaVinci Wide Gamut (DWG) workflows. OKLab code by Björn Ottosson (https://bottosson.github.io/posts/oklab/)

### CF OKLCH (DWG).dctl

This script focuses on transforming colors in the OKLCH model within DaVinci Wide Gamut (DWG). OKLCH comes from OKLab - code by Björn Ottosson (https://bottosson.github.io/posts/oklab/)

## Installation

1. Open DaVinci Resolve and navigate to File > Project Settings.
2. In the Color Management section, find the Lookup Tables section and click on Open LUT Folder.
3. Copy the DCTL files (`CF Tetra Upper:Lower.dctl`, `CF OKLAB (DWG).dctl`, `CF OKLCH (DWG).dctl`) into the opened LUT folder.
4. Restart DaVinci Resolve to load the new DCTL scripts.
