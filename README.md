# HBV-BMI-numpy

Looks like https://github.com/Daafip/HBV-data-assimilation but uses numpy indexing rather than pandas.

## Overview of code: 

- `Forcing.txt` contains the real observational data
- `HBV_bmi.py` contains the actual BMI model
- `Weigfun.py` contains a weighting function to add lag to the model
- `Forward model.ipynb` old version of forward model - timestep based - running but not OOP
- `Forward model BMI.ipynb` Newer version: Object Oriented Programming, where the model state is a class instance. running model.update() advances the model timestep according to the Basic Model Interface (BMI).
- `bmi.py` file explain what each function should do
- `empty_bmi.py` file which raises exceptions for not implemented BMI's 