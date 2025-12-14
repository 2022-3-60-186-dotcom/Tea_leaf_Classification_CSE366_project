# Tea_leaf_Classification_CSE366_project

📝 Project Overview

This project focuses on developing an automatic tea leaf classification system using deep learning techniques. The goal is to explore, compare, and analyze multiple CNN-based approaches to identify the most effective and generalizable model for tea leaf disease and quality classification.

This work was completed as part of the CSE366 – Artificial Intelligence course project.

🎯 Objective

- The main objective of this project is to:

- Explore different supervised learning strategies for image classification

- Compare pre-trained, custom, and attention-enhanced CNN models

- Identify the best-performing and most generalizable model through structured experimentation, evaluation, and explainability analysis

📂 Datasets

**Dataset 1: TeaLeaf Dataset**

- Provided by course instructor

- Binary classification:

Structure:

dataset/

├── class_1/
│   └── Leaf that not to be used to make tea

├── class_2/
│   └── Leaf that uses to make tea

**Dataset 2: Tea Leaf Disease Dataset**

- Collected from Kaggle within the same domain

- Multi-class dataset used for generalizability testing

- Contains multiple tea leaf disease categories
dataset_2/

├── algal_spot/        (Class 0)

├── brown_blight/      (Class 1)

├── gray_blight/       (Class 2)

├── healthy/           (Class 3)

├── helopeltis/        (Class 4)

├── red_spot/          (Class 5)


🧩 Project Tasks Breakdown

**Task 1: Exploratory Data Analysis (EDA) & Related Work**

- Analyzed class balance and dataset bias

- Visualized sample images and intra-class variations

- Investigated image properties (resolution, aspect ratio, color distribution)

- Conducted augmentation probe (flip, crop, color jitter)

- Summarized related work from reputable journals and conferences (IEEE, Springer, Elsevier, ACM)

**Task 2: Supervised Pre-trained Baselines**

Implemented and fine-tuned:

-ResNet

-VGG

-MobileNetV2

Used transfer learning with frozen backbone layers

Maintained consistent hyperparameters across models

Performed paired t-test for statistical comparison

**Task 3: Custom CNN Model** 

- Designed and trained a CNN model from scratch

- Multiple convolutional and pooling layers

- ReLU activations and Batch Normalization

- Applied data preprocessing and augmentation

- Used early stopping to prevent overfitting

- Evaluated using the same metrics as Task 2

**Task 4: Attention-Enhanced CNN Model**

Integrated CBAM (Convolutional Block Attention Module) into the CNN

Enhanced feature extraction using channel and spatial attention

Compared performance with:

- Pre-trained models

- Custom CNN


**Task 5: Explainability & Generalizability Testing**
Explainability using Grad-CAM

- Applied Grad-CAM to the best-performing model

Visualized activation maps for:

- Correct predictions

- Incorrect predictions

- Analyzed model focus on disease-relevant regions

- Generalizability Testing

- Selected a second tea leaf dataset from the same domain

- Retrained the best-performing Custom CNN

- Compared performance across datasets

- Analyzed robustness and performance variations

**🧠 Key Techniques Used**

- Convolutional Neural Networks (CNN)

- Transfer Learning

- Attention Mechanisms (CBAM)

- Grad-CAM Explainability

- Early Stopping

- Data Augmentation

- Statistical Evaluation

**👩‍💻 Team Members**

- Riya Akter (2022-3-60-176)

- Ishrat Jahan Anika (2022-3-60-195)

- Asifa Akter Liya (2022-3-60-186)

- Benazir Meem (2022-3-60-169)
  

**🏫 Instructor** 

Dr. Raihan Ul Islam

East West University

Department of Computer Science & Engineering


**📌 Notes**

- Full notebooks contain detailed experiments and visualizations

- This repository summarizes implementation, evaluation, and findings

- Results demonstrate strong performance, interpretability, and generalizability


