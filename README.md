# brain-tumor-detection-with-2-dataset

---

# Brain Tumor Detection using MRI Images

This repository contains a Jupyter Notebook that implements brain tumor detection using MRI images, leveraging two different datasets for training and evaluation. The model employs **EfficientNetB3** and **DenseNet201** architectures for classification into four categories: **Non Tumor, Glioma Tumor, Meningioma Tumor, and Pituitary Tumor**.

## Datasets

We have used two different MRI brain tumor datasets from Kaggle:

1. **[Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/data)**
   - This dataset contains labeled MRI images for brain tumor detection.

2. **[Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)**
   - This dataset provides MRI images categorized into three classes of brain tumors and non-tumor cases.



## Model Architectures

### EfficientNetB3
EfficientNetB3 is employed for feature extraction. The layers are fine-tuned to extract the relevant features from the MRI images.

### DenseNet201
DenseNet201 is another deep learning model utilized in this notebook. It is also fine-tuned and used for feature extraction and classification.

## Results

The notebook trains and evaluates the models on the MRI datasets, and you can view the training process, accuracy, and model architecture directly in the notebook.


