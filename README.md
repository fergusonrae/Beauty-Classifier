# Predicting Beauty

## The Model

Consists of a binary classifier. Model is a convolutional neural network which has been pre-trained using Tensorflow Transfer Learning on AADB dataset.

__Takes:__ An image hosted locally

__Outputs:__ A classification of Beautiful or Ugly along with probability

## Initial Setup Commands

### Install miniconda
https://conda.io/miniconda.html

### Create a virtual environment
Mac Terminal or Windows Anaconda Prompt
```
$ conda create -n toolbox
```

### Activate it
Mac Terminal
```
$ source activate toolbox
```

Windows Anaconda Prompt
```
$ activate toolbox
```

### Install packages
```
(toolbox) $ conda install pip
(toolbox) $ pip install -r requirements.txt
```

### Define AWS credentials locally
Complete Quick Start portion at https://github.com/boto/boto3.
Email rferguson@laughlin.com for AWS credentials for now.

### Close the virtual environment
Mac Terminal
```
(toolbox)$ source deactivate
```

Windows Anaconda Prompt
```
(toolbox)$ deactivate
```

## Run Commands

### Activate it
Mac Terminal
```
$ source activate toolbox
```

Windows Anaconda Prompt
```
$ activate toolbox
```

### Run it
```
(toolbox)$ python run.py
```

### Close the virtual environment
Mac Terminal
```
(toolbox)$ source deactivate
```

Windows Anaconda Prompt
```
(toolbox)$ deactivate
```

## References

Transfer Learning: https://www.tensorflow.org/hub/tutorials/image_retraining

AADB Dataset Reference: https://github.com/aimerykong/deepImageAestheticsAnalysis

AADB Dataset (Not needed to run code): https://drive.google.com/drive/folders/0BxeylfSgpk1MOVduWGxyVlJFUHM
