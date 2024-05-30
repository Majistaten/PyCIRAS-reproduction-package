# Reproduction Package for "Measuring What Matters: Software Engineering and its Role in Scientific Software Popularity"

## Contributors
  - [Tobias Hansson](https://github.com/Majistaten)
  - [Samuel Thand](https://github.com/SamuelThand)

## Overview
This is the reproduction package for the study "Measuring What Matters: Software Engineering and its Role in Scientific Software Popularity". 

The repository for PyCIRAS can be reached at: https://github.com/Majistaten/PyCIRAS

## Contents
1. `2024-03-29_11-30.zip/2024-03-29_11-30` - This directory contains the results of the mining process.
   1. `lint.csv` - Contains processed code quality data
   2. `stargazers.csv` - Contains processed github stargazer data
   3. `test.csv` - Contains processed unit testing data
   4. `git.csv` - Contains processed git process data
   5. `metadata.csv` - Contains github metadata
   6. `database.db` - Database containing all raw data

## How to Reproduce the Results
1. Clone this repository:
```bash
git clone https://github.com/Majistaten/PyCIRAS-reproduction-package
```
3. Clone [PyCIRAS](https://github.com/Majistaten/PyCIRAS):
 ```bash
 git clone https://github.com/Majistaten/PyCIRAS
 ```
5. Unzip the content of `2024-03-29_11-30.zip` to `out/data` (must be created) in PyCIRAS.
6. Enter the PyCIRAS directory:
 ```bash
 cd PyCIRAS
 ```
7. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
  ```
8. Install the required dependencies:
```bash
pip install -r requirements.txt
```
9. Start JupyterLab:
```bash
jupyter lab
```
10. Open and interact with the provided notebook `notebooks/thesis.ipynb` to conduct the data analysis and visualization.
