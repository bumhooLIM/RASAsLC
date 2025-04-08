# RASAsLC

A Python-based project for managing and analyzing astronomical CCD data.

## Features
- FITS file handling
- CCD calibration (bias, dark, flat)
- Photometry (aperture/SEP-based)
- Large dataset support

## Environment
This project uses a conda environment named `rasapy`. To recreate it:

```bash
conda env create -f environment.yml
conda activate rasapy
