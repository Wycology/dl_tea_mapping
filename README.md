# Deep Learning Session

# Tea Mapping in Kenya with Deep Learning

This Colab-based notebook is part of a PhD workshop on remote sensing and deep learning. It demonstrates how to map tea plantations at the foot of Mount Kenya using satellite imagery and a U-Net model in PyTorch.

## What it covers
- Load raster and vector geospatial data with `torchgeo`
- Apply augmentations (`albumentations`)
- Train a U-Net (ResNet-18) for binary segmentation (tea / no tea)
- Evaluate with accuracy and Intersection over Union
- Save metrics and best model

## Run it
[Open in Google Colab](https://colab.research.google.com/github/Wycology/dl_tea_mapping/blob/main/dl_tea4.ipynb)

## 📁 Data
Ensure you upload the `.tif` (satellite image) and `.gpkg` (training labels) files in `/content/` before running the Google Colaboratory.

## Instructors
Developed for a PhD workshop by David Wuepper, Lisa Biber-Freudenberger, Hadi, and Wyclife Agumba Oluoch.

## License
MIT License.
