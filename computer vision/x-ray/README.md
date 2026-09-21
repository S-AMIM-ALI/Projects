# 🫁 Pneumonia Detection from Chest X-Ray Images

A deep learning project for detecting **Pneumonia from chest X-ray images** using **PyTorch**.

The model classifies chest X-ray images into two categories:

* 🟢 **Normal**
* 🔴 **Pneumonia**

## 📊 Dataset

| Details         | Information      |
| --------------- | ---------------- |
| Training Images | 5,232            |
| Test Images     | 624              |
| Classes         | 2                |
| Input Size      | 224 × 224 pixels |

### Classes

```text
1. Normal
2. Pneumonia
```

## 🔄 Data Preprocessing

The images were resized to **224 × 224 pixels** and data augmentation techniques were applied to improve model generalization.

Augmentation included:

* Rotation
* Color variation
* Contrast adjustment

These transformations help the model learn relevant **textures, edges, and visual patterns** from chest X-ray images.

## 🧠 Framework

* **PyTorch**
* Deep Learning
* Image Classification

### Training Configuration

```text
Epochs: 50
Image Size: 224 × 224
Task: Binary Classification
```

## 📈 Results

The model achieved:

> **88.78% Test Accuracy**

on the test dataset.


```


