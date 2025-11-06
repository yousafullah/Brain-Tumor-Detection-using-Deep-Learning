# Brain-Tumor-Detection-using-Deep-Learning
 Project Overview
This project focuses on building a robust and accurate Convolutional Neural Network (CNN) to automatically detect brain tumors from Magnetic Resonance Imaging (MRI) scans. The goal is to assist medical professionals by providing a fast, preliminary diagnostic tool that can classify MRI images into categories like "Tumor" and "No Tumor".

Early and accurate detection of brain tumors is critical for effective treatment and improved patient outcomes. This deep learning model aims to streamline the initial screening process, reducing the time and potential for human error.

# Dataset
The model is trained and evaluated on a publicly available MRI dataset.

Dataset Link: Brain Tumor MRI Dataset on Kaggle https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

Dataset Description:

Source: The dataset is curated and hosted on Kaggle by Masoud Nickparvar.

Structure: The dataset is organized into two main folders:

Training: Contains subfolders for glioma_tumor, meningioma_tumor, pituitary_tumor, and no_tumor.

Testing: Follows the same subfolder structure for evaluation.

Classes: The project can be approached in two ways:

Binary Classification (Tumor vs. No Tumor): This is the primary focus of the provided notebooks.

Multi-class Classification (Glioma vs. Meningioma vs. Pituitary vs. No Tumor): An advanced task to identify the specific tumor type.

Volume: The dataset contains over 7,000 MRI images, providing a substantial foundation for training a deep learning model.

# Tech Stack & Dependencies
Programming Language: Python 3.8+

Deep Learning Framework: TensorFlow 2.x, Keras

Libraries:

Data Handling & Computation: NumPy, Pandas

Image Processing: OpenCV, Pillow (PIL)

Visualization: Matplotlib, Seaborn

Model Training & Evaluation: Scikit-learn
