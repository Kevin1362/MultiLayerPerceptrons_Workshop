# Multi-Layer Perceptrons Workshop
# Student Information
Kevinkumar Patel - 8998612
Prajesh Bhatt - 9046277
Muthuraj Jayakumar - 9084570 
## Overview
This repository contains the completed **notebook-only** version of the Multi-Layer Perceptrons workshop. The work is kept inside Jupyter Notebook files, so there are **no separate `.py` files** in this package.

The workshop focuses on understanding how multi-layer neural networks work through:
- forward propagation
- loss calculation
- gradient descent
- backpropagation
- model training and evaluation

## Files Included
- `MultiLayerPerceptrons_Workshop.ipynb` – main workshop notebook with completed exercises and explanations
- `MultiLayeredPerceptrons.ipynb` – second notebook with multilayer perceptron training, preprocessing, and evaluation
- `requirements.txt` – required Python packages for running the notebooks
- `README.md` – setup and running instructions

## Recommended Python Version
Use **Python 3.11**.

Python 3.14 is not recommended for this workshop because some machine learning libraries, especially TensorFlow, may not install correctly on that version.

## Requirements
Install the packages listed in `requirements.txt`:
- numpy
- matplotlib
- scikit-learn
- tensorflow
- torch
- torchvision
- notebook
- ipykernel

## How to Run the Workshop

### 1. Extract the ZIP file
Download and extract the workshop ZIP into a folder on your computer.

### 2. Open Command Prompt in the extracted folder
In Windows:
- open the folder
- click the address bar
- type `cmd`
- press **Enter**

### 3. Check installed Python versions
Run:
```bash
py -0p
```

### 4. Create a virtual environment using Python 3.11
Run:
```bash
py -3.11 -m venv venv
```

### 5. Activate the virtual environment
Run:
```bash
venv\Scripts\activate
```

After activation, you should see `(venv)` at the beginning of the command line.

### 6. Upgrade pip
Run:
```bash
python -m pip install --upgrade pip
```

### 7. Install all required packages
Run:
```bash
pip install -r requirements.txt
```

### 8. Start Jupyter Notebook
Run:
```bash
jupyter notebook
```

A browser window should open.

### 9. Open a notebook
Open either:
- `MultiLayerPerceptrons_Workshop.ipynb`
- `MultiLayeredPerceptrons.ipynb`

### 10. Run all cells
Inside Jupyter:
- click **Kernel**
- choose **Restart & Run All**

Or run cell by cell using:
- **Shift + Enter**

## Notes
- Make sure you run the notebooks inside the activated virtual environment.
- If `jupyter` is not recognized, install it again using:
```bash
pip install notebook
```
- If one deep learning library fails to install on your system, confirm that you are using **Python 3.11** and try again.

## Learning Outcomes
By completing this workshop, you should be able to:
- explain the idea of a perceptron and multilayer perceptron
- compute outputs from a neural network
- calculate and interpret loss
- understand gradient descent and backpropagation
- compare neural-network implementations across different frameworks





