# Intel Image Classification using CNN (PyTorch)

## 1. Project Overview
This project aims to classify natural scenes into six categories: **Buildings, Forest, Glacier, Mountain, Sea, and Street**. It demonstrates the complete machine learning workflow, including data preprocessing, Exploratory Data Analysis (EDA), CNN architecture design, and performance evaluation.

## 2. Dataset Structure
The dataset is organized into categorical folders:
- `/dataset/buildings`
- `/dataset/forest`
- ... (and so on)

The code implemented in the notebook performs a random **80/20 train-test split** to ensure robust evaluation.

## 3. Requirements
To run this project, you need Python 3.8+ and the following libraries:
- PyTorch & Torchvision
- Matplotlib & Seaborn
- Scikit-learn
- Pandas & Numpy

Install them via:
```bash
pip install -r requirements.txt