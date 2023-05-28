# Classifying Bees using Deep Learning

This repository contains my work carried out during my second-year internship at ENSEEIHT. 

## Tutorial

The `res` directory includes the utilized database, which is further divided into the following subdirectories: `/res/cap500/train`, `/res/cap500/val`, and `/res/cap500/test`. 

The `/res/cap500/cap500-heatmaps` directory contains the heatmaps obtained from the images in the database. These heatmaps represent the areas where the network focused to make its decision. These heatmaps are generated using GradCAM.

The `/src` directory contains the training notebooks (`/src/training`) and result analysis notebooks (`/src/analysis`). These notebooks allow you to execute the code on Google Colab.

## Results

During my internship, I achieved the following results using a hierarchical loss :

| Metric               | Value    |
|----------------------|----------|
| Categorical Accuracy | 0.9317   |
| Validation Accuracy  | 0.86245  |
| Test Accuracy        | 0.8493   |

To run the `results_analysis.ipynb` notebook, you will need the weights, which you can download from the following link: [Weight Download Link](https://drive.google.com/drive/folders/1CeB3HN4um440ntiKXXqzJeWZtUuz-elw?usp=sharing).
