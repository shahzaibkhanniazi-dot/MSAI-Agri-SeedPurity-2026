# MSAI-Agri-SeedPurity-2026
Seed Purity Analysis &amp; Weed Classification using Custom CNN An AI-powered agricultural diagnostic tool designed to automate the identification of seed quality and invasive weed species. Developed for the MSAI program (Fall 2025) and aligned with SDG 15 to promote sustainable terrestrial ecosystems

### 🌾 Project Overview

This repository contains a from-scratch implementation of a Convolutional Neural Network (CNN) aimed at enhancing agricultural productivity and biodiversity. By automating the purity analysis of seed lots, this project helps farmers avoid the planting of invasive weeds and defective seeds, ensuring higher yields and protecting local "Life on Land."

###  Key Objectives
Seed Quality Grading: Classify seeds into 4 categories: Pure Seed, Weed Seed, Broken Seed, and Inert Matter.

From-Scratch CNN: Zero reliance on pre-trained models (No Transfer Learning).

Performance Benchmark: Target accuracy of 75%+ for clinical/field reliability.

SDG 15 Alignment: Combatting land degradation and the spread of invasive species through precision agriculture.

### 🛠 Technical Implementation
Model Architecture (Custom CNN)The architecture is optimized for small-scale texture recognition (seed surfaces)
Convolutional Blocks: Multiple layers with Batch Normalization to stabilize training on a custom dataset.
Regularization: Integrated Dropout (0.3) to prevent overfitting and ensure the model generalizes to new seed batches.
Optimization: Utilized Adam Optimizer and a StepLR Scheduler to fine-tune accuracy in final epochs.

### 📥 Data PipelineSource: 
Curated dataset of 400+ images per class synced via Kaggle API.Preprocessing: Standardized images to $128 \times 128$ with Random Augmentation (flips/rotations) to maximize data utility.

## 🛠 Technical Implementation 🧠
### Model Architecture (Custom CNN)
The architecture is optimized for small-scale texture recognition (seed surfaces):
* **Convolutional Blocks:** 3 Layers with **Batch Normalization** to stabilize mathematical training on the custom dataset.
* **Activation:** **ReLU** functions for non-linearity in feature extraction.
* **Regularization:** Integrated **Dropout (0.5)** to prevent overfitting and ensure the model generalizes to new seed batches.
* **Optimization:** Utilized **Adam Optimizer** and a **StepLR Scheduler** to break past the 70% accuracy plateau.



---

## 📥 Data Pipeline
* **Source:** Curated dataset of 400+ images per class.
* **Preprocessing:** Standardized images to 128x128.
* **Augmentation:** Random flips and rotations to maximize the utility of the custom dataset.

---

## 📊 Experimental Results & Diagnostics
The training process demonstrated a smooth learning curve, successfully overcoming the 70% accuracy plateau.

### 1. Training History

* The model stabilized at **91.53%**, proving the robustness of the custom architecture.

### 2. Evaluation Metrics
* **Confusion Matrix:** High diagonal density confirms accurate classification between Rumex and Soybean.
* **Classification Report:** Detailed F1-Score, Precision, and Recall metrics are provided in the documentation to ensure agricultural reliability.


---

### Contributors
SHAHZAIB KHAN | Student ID: SU92-MSAIW-S25-019

TALHA BIN ASLAM | Student ID: SU92-MSAIW-F25-043

Program: MS-AI (Fall 2025) Submission Date: January 31, 2026 (Extended)

