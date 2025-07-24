# Assignment 5 – Machine Learning with R (and caret)

This repository contains a Jupyter notebook explaining how to perform a supervised classification problem, a simple  machine learning excercise, where the goal is to predict a label from known features. The notebook is based on a tutorial, see 'Source' below for details. This repository also contains environment.yml and requirements.txt files for easily recreating the R environment used to create and run the notebook with Conda and/or Pip, respectively. Lastly, the iris.csv file is the dataset utilized in the notebook to perform the supervised classification problem.

## Source

The tutorial used to create the notebook can be found at:

https://machinelearningmastery.com/machine-learning-in-python-step-by-step/

Author: Jason Brownlee

--

Iris data credit: R. A. Fisher

https://archive.ics.uci.edu/ml/datasets/Iris

## Contents

```
assignment_five_part_2-machine_learning_R/
├── README.md # This file
├── environment.yml # Conda environment definition
├── iris.csv # Dataset required for notebook functionality
├── machine_learning_R.ipynb # Notebook with tutorial walkthrough
└── requirements.txt # Pip-based environment definition
```

## Getting Started

### Clone the Repository and Set Working Directory

```
git clone https://github.com/leviduhaime/assignment_five_part_2-machine_learning_R.git
cd assignment_five_part_2-machine_learning_R
```

### Create the Python Environment

```
module load miniconda3/24.1.2-py310
conda env create -f environment.yml
conda activate r-caret-env
```

*Or use pip:*

```
pip install -r requirements.txt
```

### Launch Jupyter Lab

```
jupyter lab
```

### Interact With the Notebook

Open machine_learning_R.ipynb

Run each code cell from top to bottom and read the markdown cells for explanations of the code.

Running the notebook code requires access to the source data file iris.csv.

Find it in this repository or at the link in the header of this readme.

The notebook assumes that those files are located in the git repo clone directory.

## License

This repository is intended for educational use only.

## Acknowledgments

Iris data credit: R. A. Fisher

Based on tutorial from:
https://machinelearningmastery.com/machine-learning-in-r-step-by-step/
Author: Jason Brownlee
© 2025 Guiding Tech Media All Rights Reserved