# FaceGeneration_usingGANs

In this project, I have defined and trained a Deep Cycle GAN(DCGAN) on a dataset of faces. The goal was to get a generator network to generate new images of faces that look as realistic as possible!

The project is broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, we can visualize the results of your trained Generator to see how it performs; generated samples looks like fairly realistic faces with small amounts of noise.

## Getting the Data
I have used the CelebFaces Attributes Dataset (CelebA) to train my adversarial networks.

This dataset is more complex than the number datasets (like MNIST or SVHN), and so, I had defined deeper networks and train them for a longer time to get good results. It is suggested to use a GPU for training.

## Pre-processed Data
I've done some of the pre-processing like each of the CelebA images has been cropped to remove parts of the image that don't include a face, then resized down to 64x64x3 NumPy images. Some sample data is show below.

## Instructions
1. You can download this data by clicking [here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)

2. Extract the data in the home directory of this notebook for further loading and processing. After extracting the data, you should be left with a directory of data processed_celeba_small/

3. The ipynb notebook is well documented with each and every steps explained properly.

4. Enjoy :)
