# The Cat Pedigree Model for Classifying and Predicting Breeds of the Cats.

The CatPedigree - Cat Dating App uses Machine Learning to classify and predict Cat Breeds. The model were build using TensorFlow Convolutional Neural Network.

End Goal: Take a photo of a cat and gain their respective breed and information about them also to predict their crossbirth (currently supports only color pedigree prediction). 
.

## The Team 
#### Project Team Members:
* Bugi Sulistiyo (M7269J2321) - Machine Learning - Universitas Mulawarman
* Zahrizhal Ali (M2272J2364) - Machine Learning- Universitas Muslim Indonesia
* Wardatun Sayyidah (M2208K1922) - Machine Learning - Universitas Hasanuddin
* Robby Ramadhan Anshory (A2152G1665) - Android Learning - Sekolah Tinggi Teknologi Bandung
* Budi Setiawan (A7314F2733) - Android Learning - Universitas Singaperbangsa Karawang
* Fina Enno Rizki Oktavia (C7312F2682) - Cloud Computing - Universitas Sebelas Maret

## What's in this repo?

* images/ (soon) - folder with sample of cat images
* cp_preprocessing_data.py - Python script that collects the photos from the post-cleaned dataset and split them into train/test directories automatically respective to their train/test split proportion.

* requirements.txt - A text file with the dependency requirements for this project.

## Dataset
The dataset were gathered from 2 resources publicly available on the internet.
- Kaggle Dataset. URL:
- Robots. URL:

1. Kaggle Dataset.
by ___
Description


2. Robots. URL:
Description

## Classification Workflow
On progress

## Timeline and Master Plan

As of: 24 May 2022 (Since this documentation is written)
Note: might likely to change.

### Stage 1 - Gathering and Cleaning Dataset (done)
Gathering the dataset. We also clean the dataset for each breeds to remove unrelated or corrupted images to avoid overfit/underfit or even worst model performance. We need to store images at large scale, using Google Storage and Google Drive to store the dataset and accessible to the CatPedigree ML Team.

### Stage 2 - Image Preprocessing and data augmentation (done)
Perform Feature Engineering to remove unwanted noise from images. Perform Image Augmentation to avoid overfit and slightly improve the model from only 20% to 80% of accuracy.

### Stage 3 - Build the model prototype (done)
Build simple model architecture using Tensorflow Sequential, apply some of the Transfer Learning Model from TensorflowHub like MobileNet, ResNet, and InceptionV3 and perform Fine Tuning to retrain the model to the spesific cases of cats classification.

### Stage 4 - Convert to TFLite and ready for deployment (done)
Model already converted to TFLite and can be used by the Mobile Devs Team.

### Stage 5 - Optimizing model performance (on progress)
Hyperpareter Tuning to gain optimized model. If have to, we need to reduce the variance of the images.

### Stage 6 
Repeat the process untill we can get the desired performance