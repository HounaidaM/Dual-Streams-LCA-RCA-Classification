# Dual-Streams-LCA-RCA-Classification
Left and Right Coronary Angiograms Classifiation using Dual Streams Deep Learning models.

This is the official repository for the paper "Exploiting Pre-trained Architectures for Dual-Stream Classification of LCA-RCA in a Private AngioData" accepted in INISTA'2023 conference. it will happen in September 2023.

# usefulness :

This project can be used to automatically classification of medical images. It was tested on a sample of coronary frames extracted from angiographic videos. It will be useful to classify a large dataset ensuring better performance.

# Authors: 
Hounaida Moalla & Aiman Ghrab

# Environment
Python, Keras, Kaggle cloud

# Dataset
The full dataset was collected from exams performed by a single catheterization laboratory during the period between January 2018 and December 2021.
Dataset consisted of 3159 angiographic study: a total of 37209 coronary angiograms was extracted. We used a sample of 45 angiograms to extract a total of
1434 frames of size 512 x 512 pixels.
A sample of the dataset is put in the "RCA_LCA_dataset" section above.

# Simple classification
"classification_with_pre_trained_models.ipynb" is used to do fine-tunes on unique models like as VGG19, InceptionV3, ...

# Dual-Streams classification
"dual-streams.ipynb" is used to train dual-streams models that used in Simple classification code. "sample_dualStream_arch.png" depicts image of a dual architecture that includes VGG19 and Inception_V3.
