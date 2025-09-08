# RICE-PLANT-
📘 Rice Plant Leaf Disease Detection
🌱 Project Overview

This project focuses on the automatic recognition of rice leaf diseases using image processing and machine learning techniques.
It identifies three common rice leaf diseases:
Bacterial Leaf Blight (BLB) – Yellowing & drying of leaves caused by Xanthomonas oryzae.
Brown Spot – Small brown lesions with yellow halos caused by Bipolaris oryzae.
Leaf Smut – Black, soot-like spots caused by Entyloma oryzae.
The goal is to help farmers detect diseases early, improve crop yield, and support precision agriculture.

🎯 Objectives

Early and accurate detection of rice plant leaf diseases.
Classification of healthy vs. diseased leaves using SVM and Deep Learning.
Development of a user-friendly system for farmers and researchers.
Contribution to smart farming and food security.

🛠️ Methodology

Image Acquisition – Collecting rice leaf images (real-time or dataset).

Preprocessing – Resizing, noise removal, grayscale conversion, and contrast enhancement.

Segmentation – Using Otsu Thresholding and Canny Edge Detection to isolate diseased regions.

Feature Extraction – Color (RGB/HSV), Texture (GLCM), and Shape features.

Classification – Using SVM (RBF kernel) and optional deep learning (CNN/ITNN).

Output – Disease name and detection results.

📂 Repository Structure
Rice-Plant/
├── report/                # Project Report (PDF)
├── presentation/          # Project Presentation (PPT)
├── images/                # Dataset images
│   ├── bacterial_leaf_blight/
│   ├── brown_spot/
│   └── leaf_smut/
├── code/                  # MATLAB/Python source code
└── README.md              # This file

🌾 Sample Images
Bacterial Leaf Blight
Brown Spot
Leaf Smut


📊 Results

Healthy leaf detection → ✅ Correctly identified.
Diseased leaf detection → High accuracy using SVM with extracted features.
Model shows potential for real-time agricultural use.

🚀 Future Scope

Integrate deep learning (CNNs, Transfer Learning) for higher accuracy.
Build a mobile app for farmers (upload photo → get disease info).
Connect with IoT devices / drones for real-time large-scale monitoring.
Expand dataset to cover more rice diseases & crops.

👨‍💻 Contributors

G. Bharath – 2182951021
P. Lasya Vardhini – 2182951040
Y. Naga Uday Kiran – 2182951066
D. Tejeswara Rao – 2182951014

Under the guidance of:
Mrs. Ch. Sravani, M.Tech (Ph.D) – Assistant Professor, Dept. of ECE

📚 References

PlantVillage & Kaggle datasets.
Research papers on rice disease detection using ML & CNNs.
MATLAB Image Processing & Machine Learning toolboxes.

✅ This README will make your repository clear, professional, and attractive.
