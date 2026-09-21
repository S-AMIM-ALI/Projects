#skin cancer classification 
classes type 1.Malignant 2.Benign
Dataset downloaded from kaggle repository
Total size =3237 images used here in Testion,Training,Validation
#keras library used here 
#Data Augmentation
#Grad-CAM
Accuracy=86%


# 🩺 Skin Disease Classification Using Transformer-Based Deep Learning

<p align="center">

**Transformer-Based Skin Disease Classification on DermNet**

*23-Class • 9-Class • Binary Classification*

</p>

<p align="center">

<img src="https://img.shields.io/badge/Domain-Medical%20AI-red?style=for-the-badge" />
<img src="https://img.shields.io/badge/Computer%20Vision-Transformers-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Dataset-DermNet-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/Framework-PyTorch-orange?style=for-the-badge" />

</p>

--

---

# 🗂️ Dataset

The project uses a **DermNet-derived skin disease image dataset**.

DermNet provides a large dermatology image library covering numerous skin conditions and categories. Its current AI-oriented dataset offering is a separate, licensed dataset, so the exact source/version and licensing terms should be documented for any dataset used in this project.

A publicly available DermNet-derived dataset on Hugging Face is listed with **23 classes** and thousands of image records, illustrating the commonly used 23-class formulation of this dataset family.

### Dataset Tasks

#### 1. 23-Class Classification

Fine-grained classification across 23 dermatological categories.

#### 2. 9-Class Classification

A reduced classification problem designed to investigate model behavior with fewer target categories.

#### 3. Binary Classification
Class 0 → Healthy
Class 1 → Ringworm / Tinea


# 📦 Requirements
torch
torchvision
transformers
timm
numpy
pandas
scikit-learn
matplotlib
seaborn
Pillow
opencv-python

# 📊 Visualization

The repository can include:

* Training vs validation loss
* Training vs validation accuracy
* Confusion matrices
* ROC curves
* Precision-recall curves
* Per-class F1 scores
* Transformer attention visualizations
  
# 🔬 Explainability

For medical-image classification, understanding **where the model is focusing** is important.

Future/optional explainability experiments can include:

* Attention maps
* Grad-CAM where compatible with the architecture
* Occlusion analysis
* SHAP-based analysis
* Saliency maps

The goal is to investigate whether the model is using clinically relevant image regions rather than irrelevant artifacts.

# ⚠️ Limitations
Important limitations include:

* Dataset bias
* Class imbalance
* Image-quality variation
* Limited representation of real-world clinical populations
* Possible domain shift between training images and real-world smartphone photographs
* Potentially different performance across skin tones, acquisition devices, and clinical settings
* High accuracy on one dataset does not guarantee generalization to unseen populations

# 👨‍💻 Author

**SAMIM ALI**

If you found this project useful, consider giving the repository a ⭐.

---

<p align="center">

### 🩺 AI for Dermatology Research

**23 Classes • 9 Classes • Ringworm vs Healthy • Transformer-Based Vision**

</p>

