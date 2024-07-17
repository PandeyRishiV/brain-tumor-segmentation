# MSc Data Science project 2022-23   |  University of Glasgow

## Brain Tumor Segmentation using low computing resources

> By Rishikesh Pandey


## Sumary
We will use MICCAI's Brain tumor segmentation dataset for this project, this data was provided by Synapse.org for FeTS challenge. The goal here is to prepare a model that can train and predict brain tumors on low computing resources. The dataset had around 8000 scans with each subject containing 4 scans and a mask. We will first preprocess our data to simply input and reduce computation.

---
We will be using pytorch for our model implementation which will be a 3D Unet model made from scratch using pytorch's neural network library. This model needs to be efficient enough to run in google colab where it was created and tested.
