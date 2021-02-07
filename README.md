# Build-AI-Model
In this project I built four models using Google Cloud AutoMl with four different variations on a medical imaging dataset. This dataset will help doctors quickly to identify cases of penuomina in children.

Four variants of dataset include -

1. The binary classifier to detect pneumonia using chest x-rays: Model trained on balanced data using 100 images from the “normal” class and 100 images from the   “pneumonia”. It was evaluated based on train/test split for data used; confusion matrix, precision & recall.
2. The model trained on unbalanced data using 100 images from the “normal” class and 200 "pneumonia" class images for a total of 300 images in the “pneumonia” class. It was evaluated based on confusion matrix, precision & recall, and unbalanced classes.
3. The model trained on dataset of 100 "normal" and 100 "pneumonia" images; then switched the labels of 30 images in each class in which 30% of the data are mislabeled. Model was evaluated based on confusion matrix, precision & recall, and dirty data.
4. The model trained on total of 3 classes - 100 "normal" images, 100 "bacterial pneumonia" images, and 100 "viral pneumonia" images. It was evaluated based on confusion matrix, precision & recall, and additional data used.
