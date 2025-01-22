# GeoTIFF Pixel Center Latitude/Longitude Extraction

This repository provides a utility to compute the central latitude and longitude for each pixel in a GeoTIFF file. It also includes options to save the results as `.npy` files and visualize the longitude mesh grid.

## Features

- Compute central latitude and longitude for each pixel in a GeoTIFF file.
- Save the latitude and longitude mesh grids for further use.
- Visualize the longitude mesh grid for quick verification.

## Requirements

The script requires the following Python libraries:

- `rasterio`
- `numpy`
- `pyproj`
- `matplotlib`

You can install the required libraries using:

```bash
pip install rasterio numpy pyproj matplotlib
