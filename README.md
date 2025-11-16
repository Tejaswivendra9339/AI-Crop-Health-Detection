# 🌿 Sentinel Hub NDVI Visualizer

This project uses **Sentinel Hub** satellite imagery (Sentinel-2 L2A) to calculate and visualize vegetation health indices such as **NDVI**, **SAVI**, and **EVI** for major U.S. cities.  
It also performs **anomaly detection** using Isolation Forest to help identify potential **crop stress or disease** events.

Built with **Streamlit**, **sentinelhub-py**, and **scikit-learn**.

---

## 🚀 Features
- 🛰️ Fetch Sentinel-2 imagery via **Sentinel Hub Process API**
- 🌿 Compute **NDVI**, **SAVI**, and **EVI** indices using custom Evalscript
- 🗓️ Select a **city** and **date range** to visualize vegetation health
- ⚠️ Detect anomalies in vegetation index time series using **Isolation Forest**
- 📊 Interactive plots rendered with **matplotlib**
- 💾 Optional CSV dataset integration for bi-weekly NDVI trends

---

## 🧠 What is NDVI?
The **Normalized Difference Vegetation Index (NDVI)** is a remote-sensing measurement that indicates vegetation health using reflectance in the **red** (B04) and **near-infrared** (B08) bands:

\[
NDVI = \frac{(NIR - RED)}{(NIR + RED)}
\]

Healthy vegetation has NDVI values closer to **1**, while sparse or unhealthy vegetation approaches **0** or negative values.

---

## 🏗️ Project Structure

