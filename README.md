# RASAsLC

This repository deals with calibration of raw lightcurve data from RASA 11 and FKI camera Kepler KL4040. 

SPHEREx sub-project with Solar Sytem Object Catalog (SSOC) team. The members are
- Seoul National University (SNU) team
- Yoonsoo P. Bach (KASI)
- Jooyeon Geem (LTU)
- Max Malkhe
- Carey M. Lisse

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
