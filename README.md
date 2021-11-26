# Char-rnn Demo
![Python Version](https://img.shields.io/badge/Python-3.8-green.svg)

Simple implementation of a char-rnn based on [tensorflow turorial](https://www.tensorflow.org/text/tutorials/text_generation)

## Requirements

- anaconda
- pip3
- the collected dataset in a file called 'dataset.txt'

## Setup

```bash
# create and activate environment to install tensorflow
conda create --name tf
conda activate tf

# install dependencies
pip install -r requirements.txt
./manage.py migrate
```

## Recommendations
- Install GPU support for tensorflow for better performance: [guide](https://towardsdatascience.com/installing-tensorflow-gpu-in-ubuntu-20-04-4ee3ca4cb75d)
- Start training the model with a small number of epochs and gradually increaser to improve results.

## Usage

```bash
# run jupiter notebook
jupyter notebook
```
