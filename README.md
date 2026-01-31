# Amazon Product ML 📦

🚧 **Status: Work in Progress**  
(Currently implements dataset preparation. Price prediction model will be added.)

---

## 📌 Project Overview
This project focuses on building a **machine learning–ready dataset pipeline** for Amazon product data.  
It involves loading product metadata, downloading large-scale product images, organizing them into structured folders, and validating the dataset for future ML tasks.

The prepared dataset can later be used for:
- Product price prediction
- Product category classification
- Recommendation systems
- Computer vision–based analysis

---

## 🎯 Objectives
- Load Amazon product metadata from CSV files
- Download and store thousands of product images efficiently
- Organize images into train/test directories
- Verify dataset integrity through visualization
- Prepare a clean foundation for future ML model development

---

## 🛠️ Tech Stack
- **Language:** Python
- **Environment:** Jupyter Notebook (Google Colab)
- **Libraries:**
  - Pandas
  - Requests
  - TQDM
  - OS / PIL / Matplotlib

---

---

## 🔍 Current Implementation
✔ Dataset loading from CSV  
✔ Image URL extraction  
✔ Batch-wise image downloading  
✔ Train/Test image organization  
✔ Dataset validation & visualization  

---

## ❌ Not Implemented Yet
- Feature extraction
- Machine learning model
- Price prediction
- Model evaluation

---

## 🚀 Future Scope
- Image feature extraction using CNNs
- Product price prediction using regression models
- Multi-modal learning (image + metadata)
- Model evaluation using MAE / RMSE
- Deployment as a web or API-based ML service

---

## 👨‍💻 Author
**Pabolu Sai Harsha**  
B.Tech – Computer Science & Design

---

## 📌 Note
This repository represents the **dataset engineering phase** of an ML project and will be extended to a complete end-to-end machine learning solution.
