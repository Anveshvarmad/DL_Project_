# Adversarial Robustness Evaluation on Image Classification Models

## Overview
This project explores how adversarial attacks affect the performance of image classification models such as **ResNet-34** and **DenseNet-121**. It includes generating adversarial examples, visual analysis, performance evaluation, and a summary of results.

---

## Repository Structure

### 📁 `code/`
- `Project3Notebook.ipynb`: Main notebook that includes:
  - Loading pretrained models and test data
  - Applying adversarial attacks (FGSM, PGD, Patch)
  - Measuring model accuracy before and after attacks
  - Generating plots and visual summaries
  - Final summary and conclusions

### 📁 `images/`
-   Sample of the original input image  
- Image after FGSM attack  
- Image after PGD attack  
- Image with patch-based adversarial attack  

### 📁 `Plots/`
- `1.png` – ResNet-34 Accuracy by Attack  
- `2.png` – DenseNet-121 Accuracy by Attack  
- `3.png` – Top-1 Accuracy Drop Comparison  

---

## 📦 Adversarial Image Dataset

You can download the full set of adversarial images from the link below:  
[🔗 Google Drive Folder](https://drive.google.com/drive/u/0/folders/1RugxPkkJcx47wv3hybuk-pYU712bOwEg)

Contents:
- Adversarial images generated using **FGSM**, **PGD**, and **Patch-based** attacks
- Subfolders categorized by:
  - Attack Type
  - Original Class Labels

---

## 🚀 How to Run

1. Open `code/Project3Notebook.ipynb` in **Jupyter Notebook** or **JupyterLab**
2. Run all cells to:
   - Load models and test data
   - Generate adversarial examples
   - Compute accuracy and generate visual plots
3. View attack results in the `images/` and `Plots/` folders
4. Download the full dataset from the Google Drive link above for more examples

---

## 🧠 Conclusion

This project highlights how even small perturbations in images can significantly reduce the accuracy of state-of-the-art classifiers. These results demonstrate the importance of adversarial training and developing more robust machine learning models.

---
