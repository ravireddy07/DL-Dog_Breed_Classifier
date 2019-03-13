# [DLND] Project: Dog-Breed Classifier

Project code for Udacity's DeepLearning Nanodegree program 2018.
In this project, I develop an algorithm for a Dog Identification Application, a Dog-Breed-Image-Classifier.

## Getting Started

In this notebook, I will make the first steps towards developing an algorithm that could be used as part of a mobile or web app. At the end of this project, I code will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling. The image below displays potential sample output of your finished project.

![Sample Dog Output](./assets/sample_dog_output.png)

In this real-world setting, I'll need to piece together a series of models to perform different tasks; for instance, the algorithm that detects humans in an image will be different from the CNN that infers dog breed.

### Prerequisites

Thinks you have to install or installed on your working machine:

* Python 3.7
* Numpy (win-64 v1.15.4)
* Pandas (win-64 v0.23.4)
* Matplotlib (win-64 v3.0.2)
* Jupyter Notebook
* Torchvision (win-64 v0.2.1)
* PyTorch (win-64 v0.4.1)

### Environment:
* [Miniconda](https://conda.io/miniconda.html) or [Anaconda](https://www.anaconda.com/download/)

### Installing

Use the package manager [pip](https://pip.pypa.io/en/stable/) or
[miniconda](https://conda.io/miniconda.html) or [Anaconda](https://www.anaconda.com/download/) to install your packages.  
A step by step guide to install the all necessary components in Anaconda for a Windows-64 System:
```bash
conda install -c conda-forge numpy
conda install -c conda-forge pandas
conda install -c conda-forge matplotlib
pip install torchvision
conda install -c pytorch pytorch
```

## Jupyter Notebook
* `dog_app.ipynb`

This jupyter notebook describe the whole project from udacity, from the beginning to the end.

## Download the Datasets

To train and test the model, you need to download these 2 datasets:

* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).
Unzip the folder and place it in this project's home directory, at the location `/dog_images`.
* Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).
Unzip the folder and place it in the home directory, at location `/lfw`.


## Running the project

The whole project is located in the file `dog_app.ipynb` and it's include the training and the prediction part.


## License
[MIT](https://choosealicense.com/licenses/mit/)
