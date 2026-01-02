# Semantic Segmentation of Aerial Imagery

This repository contains a **Google Colab notebook** that implements a complete **data preprocessing pipeline for semantic segmentation** using aerial satellite imagery.

The dataset consists of satellite images of **Dubai, United Arab Emirates**, where each image is paired with an **RGB segmentation mask** representing six semantic classes.

---

## 📌 Dataset

- Aerial satellite imagery of **Dubai, UAE**
- Corresponding **RGB segmentation masks**
- **Six semantic classes**:
  - Water  
  - Land  
  - Road  
  - Building  
  - Vegetation  
  - Unlabeled  

> ⚠️ The dataset itself is **not included** in this repository.

---

## 🛠️ What This Notebook Does

The notebook covers the **full preprocessing workflow** required before training a deep learning semantic segmentation model:

- Loading and validating image–mask pairs  
- Cropping images to patch-compatible dimensions  
- Extracting fixed-size patches from high-resolution images  
- Handling **RGB mask data correctly** (not grayscale)  
- Converting RGB mask values to **class-index label maps**  
- Resolving common issues such as:
  - Shape mismatches  
  - Extra dimensions introduced during patch extraction  
- Preparing **clean image and label datasets** suitable for training semantic segmentation models  

---

## 🧰 Technologies Used

- Python  
- NumPy  
- OpenCV  
- Patchify  
- Matplotlib  
- Google Colab  

---

## 📚 Reference & Learning Source

This work is **based on and adapted from tutorials** by the YouTube channel **650 AI Lab**.

The implementation includes:
- Additional debugging  
- Modifications made during hands-on experimentation  
- Practical fixes for common preprocessing pitfalls  

---

## 🎯 Purpose of This Repository

This repository is intended for:

- Serving as a **starting point** for training deep learning segmentation models  
- Integration with frameworks such as **TensorFlow** or **PyTorch**  

---

## ⚠️ Notes

- The dataset is **not included**
- This repository focuses on **data preparation**, not model training  

---

## ✅ Status

- ✔️ Complete  
- ✔️ Verified with visualization and sanity checks  
- ✔️ Ready for model training  
