# Toybox-Data
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23667970.svg)](https://doi.org/10.5281/zenodo.23667970)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


## Overview
This repository contains the dataset ($x_1, x_2, y$) that create the Toybox Surface from the paper
> **Daisy Bradley, Nathan Hinchliffe, Daniel Pitchforth, Matthew Jones and Elizabeth Cross** (2026). *From Grey-Box to Green-Box: When can Physics-Informed Machine Learning Reduce Carbon Footprints in Structural Health Monitoring?* [[arXiV link](https://arxiv.org/pdf/2609.33387)]


## The Toybox Surface

See the surface below:

![Toybox surface](toybox_surface.png)

Defined by the equation $y = \sqrt{|x_2|} \sin(4x_1)$

## The Dataset

* **File:** `toybox_data.csv`
* **Format:** Comma-Separated Values (`.csv`)

Contains the x1, x2 and y variables
x1 and x2 have been flattened from their original generation as a mesh grid
