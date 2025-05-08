# Running Jupyter Notebook Files

This repository contains Jupyter Notebook files (`.ipynb`) for various data science and machine learning tasks. Follow the instructions below to set up your environment and run these notebooks locally.

## Prerequisites

To run Jupyter notebooks, you will need Python and Jupyter installed on your local machine. You can install them using either `conda` (recommended) or `pip`. 

### Option 1: Using Conda (Recommended)

1. **Install Anaconda**: Download and install [Anaconda](https://www.anaconda.com/products/individual) (which includes Python and Jupyter Notebook).

2. **Create a new environment (Optional but recommended)**:
   ```bash
   conda create -n myenv python=3.x
   conda activate myenv
### Option 2: Using Pip
1. **Install Python**: Download and install [Python](https://www.python.org/downloads/) (if not already installed).
2. **Install Jupyter Notebook**:
   ```bash
   pip install notebook

## Running jupyter notebooks

1. **Install Jupyter Notebook**:
   ```bash
   conda install jupyter
2. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
3. **After running the above command, Jupyter will open in your default web browser. Navigate to the (`.ipynb`) file you want to run and click on it to open.**
4. **You can run individual cells by selecting the cell and clicking the (`Run`) button at the top, or by pressing (`Shift + Enter`). Run all cells sequentially to execute the code in the notebook.**
