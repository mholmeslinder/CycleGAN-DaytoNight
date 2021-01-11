# CycleGAN Day <-> Night

This repo is an adaptation of the work in [this blog post](https://machinelearningmastery.com/how-to-develop-cyclegan-models-from-scratch-with-keras/), which is then applied to the field of image dataset augmentation. In autonomous drive, training data can be limited and expensive, so having the ability to augment that data - in this case, transforming daytime images into night and vice versa - is very valuable.

## Environment/Requirements
This repo contains an environment.yml file that you can use with your package manager of choice to reproduce the environment/download the necessary packages.

## How to use this repo
Since this project is built on a proprietary dataset that's not publicly available, there are a couple of options:

1. Get in touch with me, and I can share the dataset. At that point, you'll be able to run everything in the .ipynb file, tweak the model/hyperparameters, and really do whatever you want.

2. Just look. The .ipynb walks through all the steps for building these models from scratch and shows results, so you can see the entire step-by-step process there.

## Models
![generator](https://github.com/mholmeslinder/CycleGAN-DaytoNight/blob/main/generator_model_plot.png)
![discriminator](https://github.com/mholmeslinder/CycleGAN-DaytoNight/blob/main/discriminator_model_plot.png)