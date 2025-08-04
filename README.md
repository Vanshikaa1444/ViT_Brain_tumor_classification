# ViT_Brain_tumor_classification
# Moltres Machine Learning Project

## Overview

Integrating Vision Transformers with fractal dimension analysis for interpretable, accurate brain tumor classification using MRI images, highlighting texture and structural insights


## Prerequisites

Before running this project, ensure you have the following installed:

- **Python 3.7+**
- **Jupyter Notebook** or **JupyterLab**
- **Required Python packages** (see requirements.txt if available)

## Installation

1. **Clone or download the project files**
   ```bash
   # If using git
   git clone <repository-url>
   cd <project-directory>
   ```

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

3. **Open the notebook**
   - Navigate to `moltres-903-908-911-065.ipynb` in the Jupyter interface
   - Click on the file to open it

## Usage

1. **Open the notebook** in Jupyter Notebook or JupyterLab
2. **Run cells sequentially** to execute the analysis
3. **Follow the notebook's instructions** for data processing and model training
4. **Review outputs and visualizations** as they are generated

## Project Components

Source: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
This dataset contains 7023 images of human brain MRI images which are classified into 4 classes: glioma, meningioma, no tumor and pituitary.
Using this dataset(train_multimodal_data.csv and test_multimodal_data.csv), we created a multimodal dataset( for each image by extracting both ViT embeddings (representing image context) and fractal dimension (indicating texture complexity) using the Vision Transformer.Key columns include:
image_name: Names of the images (e.g., Te-glTr_0000.jpg).
label: Numerical class labels (e.g., 0).
fractal_dimension: A float value representing the fractal dimension of the image.
vit_feature_0 to vit_feature_767: Numerical features extracted using a Vision Transformer (ViT).




## Troubleshooting

### Common Issues

1. **Missing dependencies**
   - Install required packages using `pip install <package-name>`
   - Check for version compatibility

2. **Data file not found**
   - Ensure data files are in the correct directory
   - Update file paths in the notebook if necessary

3. **Memory issues**
   - Reduce batch sizes or data sample sizes
   - Close other applications to free up memory

