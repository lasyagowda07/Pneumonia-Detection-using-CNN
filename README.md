# Pneumonia-Detection-using-Convolutional-Neural-Network

What is Pneumonia?
Pneumonia is a common respiratory infection that affects the lungs. It is caused by bacteria, viruses, or fungi. Pneumonia can be mild or severe, and it can be fatal, especially in young children and the elderly.

Chest X-rays are the most common way to diagnose pneumonia. However, reading chest X-rays can be challenging, even for experienced radiologists. Convolutional neural networks (CNNs) are a type of deep learning algorithm that can be used to automatically detect pneumonia in chest X-rays.
![IM-0125-0001-min](https://github.com/k8wi/Pneumonia-Detection-using-Convolutional-Neural-Network/assets/95972832/68d76d30-7e8f-443a-a8bb-c1328a7c7f0f)


This project aims to develop a CNN model to detect pneumonia in chest X-rays. The model will be trained on a large dataset of chest X-rays that have been labeled by radiologists. Once the model is trained, it can be used to automatically detect pneumonia in new chest X-rays.

# The objectives of this project are to:

1.Develop a CNN model to detect pneumonia in chest X-rays with high accuracy and sensitivity.

2.Evaluate the performance of the model on a held-out test set.

# Dataset
The dataset is taken from kaggle and is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

# CNN Model metrics

Validation Loss: 0.19544562697410583

Validation Accuracy: 0.90625

Test Loss: 0.5251447558403015

Test Accuracy: 0.7756410241127014

![cc1](https://github.com/k8wi/Pneumonia-Detection-using-Convolutional-Neural-Network/assets/95972832/976d450e-34bb-4d40-a7ee-fac8f5012fdf)
![cc2](https://github.com/k8wi/Pneumonia-Detection-using-Convolutional-Neural-Network/assets/95972832/178ecbd5-7e03-403e-9700-a773ff8e4824)


<h3>The model has achieved a validation accuracy of 90.625% </h3>

<h3>The model has been saved at the end as pneumonia.h5</h3>
