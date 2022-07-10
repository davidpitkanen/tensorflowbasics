This repository contains basic examples for using tensorflow in python and javascript.

The directory contains a environment.yml file for building the conda environment. To install all of the
conda dependencies just run the command from the terminal
conda env create -f environment.yml.
If extra dependencies are added just update the yaml file using the command conda env export > environment.yml

Once all of the dependencies are installed run the jupyter notebook with the conventional command
jupyter-lab

Included Files
helloworld.ipynb - this is linear regression implemented in tensorflow 3 times. It's implemented once with the keras functional api, once with the keras sequential api and once using gradient tape.
