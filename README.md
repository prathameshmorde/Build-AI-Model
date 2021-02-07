# Build-AI-Model
In this project I built four models using Google Cloud AutoML. I used four different variations on a medical imaging dataset. This dataset will help doctors to identify cases of pneumonia in children.

Four variants of dataset include -
1. The binary classifier to detect pneumonia using chest x-rays: Model trained on balanced data using 100 images from the “normal” class and 100 images from the   “pneumonia”.
2. The model trained on unbalanced data using 100 images from the “normal” class and 200 "pneumonia" class images for a total of 300 images in the “pneumonia” class.
3. The model trained on dataset of 100 "normal" and 100 "pneumonia" images; then switched the labels of 30 images in each class in which 30% of the data mislabeled
4. The model trained on three different classes - 100 "normal" images, 100 "bacterial pneumonia" images, and 100 "viral pneumonia" images. 

I used an open source data from Kaggle Chest x-ray
(https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

Evaluation- 
The model evaluated based on split/dirty/mislabeled and unbalanced classes. I also provided the results of confusion matrix, precision, recall, F1 score to highlight the performance.

