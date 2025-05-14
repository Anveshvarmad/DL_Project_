README.txt
==========

Project Title: Adversarial Robustness Evaluation on Image Classification Models

Overview:
---------
This project evaluates how adversarial attacks affect the performance of image classification models such as ResNet-34 and DenseNet-121. It includes adversarial image generation, visual analysis, performance comparison, and conclusions based on experimental data.

Repository Contents:
--------------------

1. code/
   └── Project3Notebook.ipynb
       - Complete implementation of:
         • Loading pretrained models and test datasets.
         • Applying FGSM, PGD, and Patch-based adversarial attacks.
         • Measuring accuracy drops post-attack.
         • Generating plots for visual analysis.
         • Summary and conclusions at the end.

2. images/
   ├── original_sample.png             → Sample of original unaltered image
   ├── fgsm_sample.png                → FGSM-perturbed adversarial example
   ├── pgd_sample.png                 → PGD-perturbed adversarial example
   └── patch_attack_sample.png        → Example image with a visible patch-based attack

3. Plots/
   ├── 1.png                          → ResNet-34 Accuracy by Attack
   ├── 2.png                          → DenseNet-121 Accuracy by Attack
   └── 3.png                          → Relative Top-1 Accuracy Drop by Attack

Adversarial Test Set:
---------------------
You can access the adversarial images used for evaluation via the following Google Drive link:

🔗 https://drive.google.com/drive/u/0/folders/1RugxPkkJcx47wv3hybuk-pYU712bOwEg

This folder includes:
• Images generated using FGSM, PGD, and Patch-based attacks.
• Subfolders organized by:
    - Attack Type (FGSM, PGD, Patch)
    - Original Class Labels

Instructions:
-------------
1. Open the file `code/Project3Notebook.ipynb` in Jupyter Notebook or JupyterLab.
2. Run all cells to:
   - Load models and test data.
   - Generate adversarial images.
   - Compute accuracy and generate visual plots.
3. To compare the impact of each attack, review the images in the `Plots/` directory.
4. Explore `images/` to view the effect of attacks on sample inputs.
5. For a full dataset of adversarial examples, download from the Google Drive link provided above.

Conclusion:
-----------
This study highlights the vulnerabilities of state-of-the-art models when exposed to even small adversarial perturbations. The performance degradation underscores the importance of incorporating adversarial training and robust model design in practical applications.

This repository can serve as a strong foundation for research or practical implementation of adversarial defenses and robustness evaluation strategies.
