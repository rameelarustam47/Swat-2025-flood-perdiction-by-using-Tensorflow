# Flood Prediction in Swat Valley (2025) using TensorFlow

## 🌊 Problem Statement

This project develops a deep learning model to predict flood occurrence in **Swat Valley, Khyber Pakhtunkhwa, Pakistan**, using multi-source remote sensing and environmental data.

---

## 📍 Study Area

Swat Valley

---

## 📊 Data Sources

All datasets were processed in Google Earth Engine:

* Sentinel-1 SAR (Pre-flood conditions)
* Sentinel-1 SAR (During flood events)
* SRTM DEM (30m resolution)
* Slope derived from DEM
* CHIRPS rainfall data
* Flood extent labels

> Note: Large GEE datasets (>25MB) were not uploaded in this repository.

---

## 🧠 Methodology

* Feature extraction from SAR and DEM data
* Terrain-informed variables (elevation, slope) used as hydrological proxies
* Data balancing using SMOTE
* Binary classification using TensorFlow neural network

---

## 🌐 Physically-Informed Component

The model incorporates **terrain and hydrological structure (DEM, slope, rainfall patterns)** to guide learning beyond purely statistical relationships.

---

## 📈 Results

* Test Accuracy: **99.88%**
* Dataset size: 127,320 samples
* F1-score (No Flood): 1.00
* F1-score (Flood): 1.00

> The model shows strong performance in distinguishing flood and non-flood conditions, although further validation on unseen basins is required for generalization.

---

## 🛠️ Tools & Technologies

* Google Earth Engine
* TensorFlow
* Scikit-learn
* Google Colab
* Rasterio

---

## 🎯 Future Work

* Transfer learning to other river basins
* Integration with real-time rainfall forecasting
* Coupling with hydrological simulation models

