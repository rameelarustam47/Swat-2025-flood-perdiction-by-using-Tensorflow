# Swat KPK Flood Prediction 2025
## Using TensorFlow Deep Learning

## Study Area
Swat Valley, KPK, Pakistan

## Data Used
- Sentinel-1 SAR Before Flood (GEE)
- Sentinel-1 SAR During Flood (GEE)
- SRTM DEM 30m (GEE)
- Slope derived from DEM (GEE)
- CHIRPS Rainfall data (GEE)
- Flood Extent Label (GEE)
Note : Gee files above 25 MB so upload here is not possible 
## Methods
- Data balancing using SMOTE
- TensorFlow Neural Network
- Binary classification

## Results
- Test Accuracy: 99.88%
- Balanced dataset: 127,320 samples
- No Flood F1: 1.00
- Flood F1: 1.00

## Tools Used
- Google Earth Engine
- Google Colab
- TensorFlow
- Scikit-learn
- Rasterio
