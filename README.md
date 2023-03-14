# Fine-tuning Text-to-Image Diffusion Models with DreamBooth

This project focuses on fine-tuning text-to-image diffusion models with DreamBooth, a powerful neural network architecture developed for subject-driven image generation. With DreamBooth, you can generate stunning images based on natural language descriptions, allowing you to visualize your ideas and concepts with unprecedented detail and realism.

## Getting Started

To use this project, you will need to have ```Python```, ```Tensorflow``` and ```Keras``` installed on your machine. 

## Inital Imports 

```import math
import keras_cv
import matplotlib.pyplot as plt
import numpy as np
import tensorflow as tf
from imutils import paths
from tensorflow import keras
```
## Usage

Once you have cloned the repository from the original keras Dreambooth page 

```git clone http://github.com/keras-team/keras-io/blob/master/examples/generative/dreambooth.py```

you can download the pre-trained weights for the text-to-image diffusion model and the DreamBooth architecture, and then run the provided script to finetune the model on your own subject-driven data. After that, you can use the `generate_images()` function to create images based on your text prompts.


This project demonstrates how researchers, designers, and artists to explore the possibilities of text-to-image generation and advance the state-of-the-art in AI-generated images.

Read more about Dreambooth ![here](https://keras.io/examples/generative/dreambooth/).
