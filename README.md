# Aerial Cactus Identification

## Competition Description from Kaggle

To assess the impact of climate change on Earth's flora and fauna, it is vital to quantify how human activities such as logging, mining, and agriculture are impacting our protected natural areas. Researchers in Mexico have created the VIGIA project, which aims to build a system for autonomous surveillance of protected areas. A first step in such an effort is the ability to recognize the vegetation inside the protected areas. In this competition, you are tasked with creation of an algorithm that can identify a specific type of cactus in aerial imagery.

## Data Format

- A folder containing 32x32 images.
- Files train.csv and test.csv containing name of file as key, and a binary column has_cactus, which is 0 if no cactus in image and 1 if there is cactus in image.

Data Available at :

https://www.kaggle.com/c/aerial-cactus-identification/data

### Files

- train/ --> the training set images
- test/ --> the test set images (you must predict the labels of these)
- train.csv --> the training set labels, indicates whether the image has a cactus (has_cactus = 1)
- sample_submission.csv --> a sample submission file in the correct format

## Target

Take images and classify whether the image contains cactus or not.

## Informations

Notebook originally taken from : https://www.kaggle.com/bonhart/simple-cnn-on-pytorch-for-beginers

Conversion from Pytorch to TensorFlow based on : https://www.kaggle.com/divyanshshekhar/aerial-cactus-identification-by-cnn-tensorflow
