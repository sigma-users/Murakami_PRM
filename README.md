# Data description

This repository contains DPC-STEM data for two ferrite systems: **Sr-based ferrite** and **Ca–La–Co-based ferrite**.

## Repository structure

- **Root directory**
  - DPC images (vector components) for each material:
    - `DPCx_Sr-based.tif`,`DPCy_Sr-based.tif` : DPC images (x- and y-components) for the Sr-based ferrite.
    - `DPCx_Ca-La-Co-based.tif`,`DPCy_Ca-La-Co-based.tif` : DPC images (x- and y-components) for the Ca-La-Co-based ferrite.

- **Raw detector images**
  - `RawData_Sr-based/`
    - Raw data for the Sr-based ferrite
    - **40 images** acquired with a **40-segment detector** (one image per segment)
  - `RawData_Ca-La-Co-based/`
    - Raw data for the Ca–La–Co-based ferrite
    - **40 images** acquired with a **40-segment detector** (one image per segment)

## Notes
- The DPC images in the root directory correspond to the x- and y-components derived from the segmented-detector raw data.
