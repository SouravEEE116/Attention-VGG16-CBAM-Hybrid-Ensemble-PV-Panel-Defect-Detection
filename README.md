# 📘 Attention-Enhanced VGG16 with Hybrid Ensemble Learning for Automated Photovoltaic Panel Defect Classification

## 🔬 Official Implementation (Q1 Journal-Level Project)

This repository presents a **deep learning and hybrid machine learning framework** for automated photovoltaic (PV) panel defect detection and classification.

The proposed system integrates **CBAM (Convolutional Block Attention Module) with VGG16** along with **multiple machine learning classifiers and ensemble learning techniques** to achieve high accuracy, robustness, and interpretability.

---

# 📌 Research Overview

Photovoltaic panel defects significantly affect energy efficiency and system reliability. Manual inspection is costly, time-consuming, and prone to human error.

To solve this problem, we propose an **AI-based automated defect classification framework** combining:

- Deep feature extraction (VGG16)
- Attention mechanism (CBAM)
- Hybrid machine learning models
- Explainable AI (Grad-CAM)

This ensures both **high performance and interpretability**, suitable for real-world deployment in solar energy systems.

---

# ⚙️ Methodology Pipeline

The proposed framework follows a complete end-to-end pipeline:

## 1️⃣ Data Preprocessing
- Image loading from structured dataset
- Rescaling and normalization
- Data augmentation (rotation, zoom, brightness adjustment)

## 2️⃣ Deep Feature Extraction
- Pretrained VGG16 (ImageNet weights)
- Feature map extraction from convolutional layers

## 3️⃣ Attention Mechanism (CBAM)
- Channel Attention Module
- Spatial Attention Module
- Enhances defect-relevant regions in images

## 4️⃣ Feature Extraction
- Dense layer feature extraction
- Standard scaling for ML models

## 5️⃣ Classification Models

### 🔹 Deep Learning Models
- Vanilla VGG16 (Baseline)
- Attention VGG16 (Proposed)

### 🔹 Machine Learning Models
- Support Vector Machine (SVM - RBF)
- Random Forest
- XGBoost
- Stacking Ensemble

## 6️⃣ Explainability (XAI)
- Grad-CAM visualization
- Feature importance interpretation

## 7️⃣ Statistical Analysis
- 5-Fold Cross Validation
- Paired t-test
- Wilcoxon signed-rank test
- 95% Confidence Interval

---

# 🤖 Models Used

## 🔷 CNN Models
- VGG16 (Baseline)
- Attention VGG16 (CBAM - Proposed)

## 🔷 Hybrid ML Models
- SVM (RBF Kernel)
- Random Forest
- XGBoost ⭐ (Best Performing)
- Stacking Classifier

## 🔷 Additional CNN Backbones (Benchmarking)
- ResNet50
- DenseNet169
- MobileNetV2
- InceptionV3
- EfficientNetB0
- Xception
- NASNetMobile

---

# 📊 Key Contributions

✔ CBAM-based attention-enhanced feature learning  
✔ Hybrid deep learning + machine learning framework  
✔ 8+ CNN backbone comparative study  
✔ Statistical significance validation  
✔ Grad-CAM explainability visualization  
✔ Ablation study of architecture components  
✔ Comprehensive performance benchmarking  

---

# 📈 Results Summary

| Model | Performance |
|------|------------|
| Attention VGG16 + XGBoost | ⭐ Highest Accuracy (~95%+) |
| Stacking Ensemble | Strong Performance |
| SVM | Stable Baseline |
| Random Forest | Competitive Results |

---

# 📊 Outputs Generated

The system produces the following results:

- Confusion Matrices (all models)
- ROC Curves (multi-class)
- Training Accuracy & Loss Curves
- Grad-CAM Visualizations
- Ablation Study Results
- Model Comparison Tables
- Statistical Test Reports
- Classification Reports

---

# 🧠 Explainable AI (XAI)

This framework uses Grad-CAM to visualize CNN decision-making:

✔ Highlights defect regions
✔ Improves model transparency
✔ Supports industrial trustworthiness

# 📦 Requirements
tensorflow,
keras,
numpy,
pandas,
matplotlib,
seaborn,
scikit-learn,
xgboost,
opencv-python,
tqdm,
joblib,
scipy.

Install dependencies:

pip install -r requirements.txt

# 👨‍🔬 Author

Sourav Sana

B.Sc. in Electrical and Electronic Engineering (EEE)
Gopalganj Science & Technology University (GSTU)

Research Interests:
Deep Learning,
Computer Vision,
Medical Image & Signal Processing.

# 🚀 How to Run

```bash
git clone https://github.com/your-username/Attention-VGG16-CBAM-Hybrid-Ensemble-PV-Panel-Defect-Detection.git
cd Attention-VGG16-CBAM-Hybrid-Ensemble-PV-Panel-Defect-Detection
pip install -r requirements.txt
python code/main.py
