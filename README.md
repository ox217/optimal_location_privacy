# optimal_location_privacy
Here are the codes of the algorithm presented in the paper "Optimal privacy protection of mobility data: a predictive approach (accepted in IFAC World Congress), with Mirko Fiacchini, Sophie Cerf and Bogdan Robu (2023)"
https://hal.science/hal-04040962
# Instructions for running simulations and analysis

## Installation (only the first time)

The simulation and analysis uses Python version 3.8 or later.

The dependencies of the data extraction code are listed in the pip-format file `requirements.txt`.

We recommand using a virtual environment [venv](https://packaging.python.org/tutorials/installing-packages/#creating-virtual-environments) to install the dependencies. 

A new virtual envirnoment named `optipriv-venv` can be created with the following command:
```
$ python -m venv .optipriv-venv
```

To activate it:
```
$ source .optipriv-venv/bin/activate
```

The installation of the dependencies within the venv is done with the following command:
```
$ pip install -r requirements.txt
```

## Launch

To launch the notebook, the virtual environment should be first activated.

Activate the venv:
```
$ source .optipriv-venv/bin/activate
```

To open the notebook optipriv.ipynb:
```
$ jupyter notebook Privacy_modelling_Real_Data_V5.ipynb

```
