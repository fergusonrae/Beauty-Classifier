[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/raferguson/Beauty-Classifier/master)
# Predicting Beauty

## The Model

Consists of a binary classifier. Model is a convolutional neural network which has been pre-trained using Tensorflow Transfer Learning on AADB dataset.

__Takes:__ An image hosted locally

__Outputs:__ A classification of Beautiful or Ugly along with probability

To run, you have a couple options.
1. Launch the Binder version. This will open the repo in your browser and allow for interaction. Downside, it may take a bit. To do this, push the Launch Binder button on the top of the ReadMe.
2. Run locally. See setup instructions below.

## Initial Setup Commands

### Install miniconda
https://conda.io/miniconda.html

### Create a virtual environment
Mac Terminal or Windows Anaconda Prompt
```
$ conda create -n beauty_classifer
```

### Activate it
Mac Terminal
```
$ source activate beauty_classifer
```

Windows Anaconda Prompt
```
$ activate beauty_classifer
```

### Install packages
```
(beauty_classifer) $ conda install pip
(beauty_classifer) $ pip install -r requirements.txt
```


### Run it
```
(beauty_classifer)$ jupyter notebook
```
This will open the active directory in your browser. Navigate to the directory with the repo and select 'Image Processing Hands On.ipynb'. This will open the notebook.

## When finished

Head back to the command line and push CTRL-C. This will close the notebook. Then, close the browser tabs that were opened.

### Close the virtual environment
Mac Terminal
```
(beauty_classifer)$ source deactivate
```

Windows Anaconda Prompt
```
(beauty_classifer)$ deactivate
```

## References

Transfer Learning: https://www.tensorflow.org/hub/tutorials/image_retraining

AADB Dataset Reference: https://github.com/aimerykong/deepImageAestheticsAnalysis

AADB Dataset (Not needed to run code): https://drive.google.com/drive/folders/0BxeylfSgpk1MOVduWGxyVlJFUHM
