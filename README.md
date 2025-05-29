# 🌊 Satellite Water Body Analysis

This project analyzes monthly satellite images from MODIS dataset to detect and quantify changes in permanent and seasonal water bodies over a 20-year period.

## 🔍 Key Features
- Downscale images using lanczos interpolation
- Permanent vs temporary water bodies using Otsu's thresholding
- Compute area of water bodies monthly
- Track seasonal and long-term changes

## 🛠 Technologies
- Python, NumPy, OpenCV, Rasterio, Geopandas
- Matplotlib, Scikit-image

## 📁 Folder Structure

water-body-analysis/
- data/ # Local .tif files (ignored in Git)
- notebooks/ # Jupyter experiments
- analysis/ # Methodology and observations
- .gitignore
- README.md
- requirements.txt


```bash
    git clone https://github.com/divyanshu-guptaa/water-body-classification-and-analysis.git
    cd water-body-classification-and-analysis
    pip install -r requirements.txt
```

## 🛰️ Dataset Description
This project uses a dataset of raw satellite images, representing monthly observations over a 20-year period (240 images total). Each image contains a wide view of a geographic region, including the target area of interest.

Format: .tif (GeoTIFF)

Temporal coverage: January 2003 to December 2022

Frequency: 1 image per month

Contents: Each image includes land, water bodies, and seasonal variations

Preprocessing: Region of interest (Uttarakhand) is extracted during runtime before further analysis.

 **Download the dataset from Kaggle:**
 
[https://www.kaggle.com/datasets/adityapathakk/modis-2003-2012](https://www.kaggle.com/datasets/adityapathakk/modis-2003-2012)

[https://www.kaggle.com/datasets/aur1ga/modis-2013-2022](https://www.kaggle.com/datasets/aur1ga/modis-2013-2022)

Place all `.tif` files inside the `data/` folder.
