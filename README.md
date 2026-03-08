# Crop Water Stress Detection using Multimodal RGB and Thermal Imagery

## Overview

This repository contains the implementation for a research project investigating **crop water stress detection using multimodal deep learning**. The study explores whether combining **RGB (visible-spectrum) imagery** and **thermal imagery** improves detection of crop water stress compared to single-modality approaches.

The project focuses on **multimodal feature fusion using convolutional neural networks (CNNs)** and evaluates the performance of RGB-only, thermal-only, and fusion-based models.

This work is part of a graduate research project in **Data Science / Artificial Intelligence applied to Precision Agriculture**.

---

## Research Objective

The main objective of this project is to investigate whether **multimodal fusion of RGB and thermal imagery improves crop water stress detection** compared with single-modality deep learning models.

Specifically, the project evaluates:

* RGB-only CNN models
* Thermal-only CNN models
* Multimodal fusion CNN models

---

## Problem Motivation

Water stress significantly affects crop productivity and irrigation management. Early detection of water stress can improve irrigation scheduling and increase agricultural efficiency.

RGB imagery captures **visual plant features** such as color, texture, and morphology, while thermal imagery captures **physiological signals**, particularly canopy temperature changes associated with reduced transpiration.

By combining these modalities, multimodal deep learning models may detect crop water stress **more effectively than single-modality approaches**.

---

## Methodology

The project follows a multimodal deep learning pipeline:

1. Crop selection and dataset acquisition
2. Dataset inspection and preprocessing
3. Training of baseline models
4. Development of multimodal fusion models
5. Performance evaluation and comparison

Three model types are implemented:

* **RGB baseline model**
* **Thermal baseline model**
* **Multimodal fusion model**

Feature-level fusion is used to combine representations from RGB and thermal images.

---

## Project Structure

```
crop-water-stress-multimodal-detection/
│
├── data/              # datasets (not uploaded to GitHub)
│
├── notebooks/         # exploratory data analysis and experiments
│
├── src/               # source code for models and preprocessing
│
├── models/            # trained model checkpoints
│
├── results/           # evaluation outputs, plots, and metrics
│
├── figures/           # images used in documentation
│
├── requirements.txt   # Python dependencies
│
└── README.md
```

---

## Technologies Used

* Python
* PyTorch / TensorFlow
* OpenCV
* NumPy
* Scikit-learn
* Matplotlib

---

## Evaluation Metrics

Model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

These metrics allow comparison between single-modality and multimodal models.

---

## Expected Contribution

This project contributes to the field of **precision agriculture and AI-based crop monitoring** by providing:

* Comparative evaluation of RGB and thermal imagery for crop water stress detection
* Investigation of multimodal deep learning fusion techniques
* Insights into practical implementation under secondary dataset constraints

---

## Limitations

This study uses **secondary datasets** and does not involve primary field data collection. Therefore, results are limited to comparative model performance under available dataset conditions.

Future work may include:

* field data acquisition using UAV sensors
* real-time irrigation monitoring systems
* deployment on edge devices for precision agriculture

---

## Author

Michael Agbenyegah

Graduate Research Project – Data Science / AI in Agriculture

---
