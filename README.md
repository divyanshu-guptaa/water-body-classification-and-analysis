# 🌊 Satellite Water Body Analysis

This project analyzes monthly satellite images from MODIS dataset to detect and quantify changes in permanent and seasonal water bodies over a 20-year period.

## 🔍 Key Features
- Downscale images using bilinear interpolation
- Segment water vs non-water using Otsu's thresholding
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


```bash
    git clone https://github.com/yourusername/water-body-analysis.git
    cd water-body-analysis
    pip install -r requirements.txt
```

This project uses satellite images for 20 years (monthly).

 **Download the dataset from Kaggle:**
 
[https://www.kaggle.com/datasets/adityapathakk/modis-2003-2012](https://www.kaggle.com/datasets/adityapathakk/modis-2003-2012)

[https://www.kaggle.com/datasets/aur1ga/modis-2013-2022](https://www.kaggle.com/datasets/aur1ga/modis-2013-2022)

Place all `.tif` files inside the `data/` folder.
