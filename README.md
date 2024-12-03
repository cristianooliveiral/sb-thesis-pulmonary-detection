# Pulmonary Disease Detection using Computer Vision

This repository contains the code, data, and documentation for my undergraduate thesis (*SB Thesis*) focused on leveraging computer vision techniques to detect pulmonary diseases from medical images, such as chest X-rays and CT scans.

## Project Overview
Lung diseases remain a major global health concern, with early detection being crucial for effective treatment. This project employs deep learning models to analyze medical images and identify patterns indicative of pulmonary conditions.

### Objectives
1. Develop a computer vision pipeline for preprocessing and analyzing medical images.
2. Implement and compare the performance of state-of-the-art deep learning models.

---

## Repository Structure


---

## Key Components
### 1. Data
The datasets used for this project include:
- **[NIH Chest X-ray Dataset](https://www.kaggle.com/nih-chest-xrays)**: A large dataset of chest X-ray images.
- **[LIDC-IDRI](https://wiki.cancerimagingarchive.net/)**: A publicly available CT scan dataset.

### 2. Models
The project utilizes the following deep learning architectures:
- Convolutional Neural Networks (*ResNet*, *EfficientNet*)
- Transfer learning techniques for improved accuracy.

### 3. Results
Key performance metrics include:
- Accuracy
- Sensitivity
- Specificity

---

## Installation
### Prerequisites
- Python >= 3.8
- TensorFlow >= 2.5 or PyTorch >= 1.8

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sb-thesis-pulmonary-detection.git
   ``` 
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ``` 

--- 

## Usage
### 1. Data Preprocessing:
    ```bash
    python src/data/preprocess.py
    ```
### 2. Model Training:
    ```bash
    python src/models/train.py --config configs/default.yaml
    ```
### 3. Evaluation:
    ```bash
    python src/models/evaluate.py --model models/best_model.pth
    ```

--- 

## Acknowledgments
This project is guided by Prof. Igor Valente and inspired by recent advancements in deep learning for medical imaging.