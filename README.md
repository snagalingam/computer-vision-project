# Bird Species Identification Using Deep Learning
## Project Overview
This repository hosts the code and documentation for our deep learning project aimed at accurately identifying bird species from images. Leveraging the comprehensive "Birds 525 Species" dataset, our model is trained on 89,885 images, encompassing 525 distinct bird species. Each image in the dataset is a 224 x 224 x 3 color image in JPG format, standardized for input into our models.

## Model Description
We employed and compared three different neural network architectures: VGG16, EfficientNetB0, and AlexNet, each adapted for the task of bird species classification. The project involved detailed customization of these models, including adjustments in the final output layer to match the number of bird species in the dataset. We employed techniques like Batch Normalization and Dropout to enhance model accuracy and generalizability.
