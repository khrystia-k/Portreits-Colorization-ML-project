# Portreits-Colorization-ML-project

## Aim

The aims of this project was to colorize grayscale portrets.

## Data

The data used in this project is the CelebA dataset. You can download the zip file from this site: https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html. In the file 'data_preprocessing.ipynb,' you can find ways to process this data and generate datasets in LAB and RGB color spaces.

## Methods

In this project, three architectures of CNN were used:
- Sequential CNN ('sequential.ipynb')
- An Autoencoder ('autoencoder.ipynb')
- CNN and Inception-ResNet-v2 (Deep Koalarization) ('inception.ipynb')
About the third architecture, you can read more here: https://arxiv.org/abs/1712.03400

## Results
The best result was received with the CNN + Inception-ResNet-v2 model. You can find the code in 'best_model.ipynb'.

<img width="952" alt="image" src="https://github.com/tania5496/Image-Colorization-ML-project-/assets/116711583/7bda0aae-106c-4256-8409-59bc80ea2440">
