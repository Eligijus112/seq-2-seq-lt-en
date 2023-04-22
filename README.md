# Lithuanian to English translation 

A model that explains in depth how to create a translation model using attention and encoder -> decoder architecture.

# The tutorial 

The code is based on the awesome tutorial of https://www.tensorflow.org/text/tutorials/nmt_with_attention. The tutorial is in depth and explains the code in detail.

# The analysis 

The code to create the model is in the `LT2EN.ipynb` file. 

# Virtual environment 

All the necessary packages are in the `env.yml` file. To install the packages using anaconda, run the following command:

```
conda env create -f env.yml
```

To update the environment, run the following command:

```
conda env update -f env.yml --prune
```

# Dataset 

The dataset is extracted via the link http://www.manythings.org/anki/lit-eng.zip

The .zip file should be placed in the input directory. 