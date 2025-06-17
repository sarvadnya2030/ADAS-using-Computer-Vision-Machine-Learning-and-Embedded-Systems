# ADAS-using-Computer-Vision-Machine-Learning-and-Embedded-Systems
Implements a real-time object detection system using traditional feature descriptors (SIFT, ORB, FREAK, LBP) and ML classifiers (XGBoost, SVM, RF, etc.). Includes a comparative study of 28 combinations. LBP + XGBoost achieved 83.57% accuracy. Based on IJRES 2025 research paper.

# 🔍 Comparative Analysis of Feature Descriptors & Classifiers for Real-Time Object Detection

This project implements the methodology from the research paper:
**"Comparative Analysis of Feature Descriptors and Classifiers for Real-Time Object Detection"**  
📄 [IJRES, March 2025, Vol. 14, No. 1, pp. 89–99](http://ijres.iaescore.com)

## 📌 Summary

We explore 28 combinations of traditional feature descriptors and machine learning classifiers for real-time image-based object detection. The key focus is to identify the most effective and computationally efficient pair.

### ✅ Key Techniques:
- **Feature Descriptors**: SIFT, ORB, FREAK, LBP
- **Classifiers**: XGBoost, SVM, Random Forest, KNN, Logistic Regression, Naive Bayes, Decision Tree
- **Feature Reduction**: K-Means + PCA
- **Target Classes**: "Car on Road" vs. "Not Car on Road"

### ⭐ Best Performing Model
- **LBP + XGBoost**
- Accuracy: **83.57%**
- Deployed on: **Raspberry Pi 4B (8 GB)**

## 🛠 Installation

```bash
git clone https://github.com/<your-username>/feature-descriptor-comparison.git
cd feature-descriptor-comparison
pip install -r requirements.txt
