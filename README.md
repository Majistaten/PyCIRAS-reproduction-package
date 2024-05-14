# Reproduction Package for "Measuring What Matters: Software Engineering and its Role in Scientific Software Popularity"

## Contributors
  - Tobias Hansson
  - Samuel Thand

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

## How to Reproduce the Results
If the data is used with PyCIRAS:
1. Clone this repository
  ```git clone https://github.com/Majistaten/PyCIRAS-reproduction-package```
2. Clone PyCIRAS
   ```git clone https://github.com/Majistaten/PyCIRAS```
3. Unzip the content of `2024-03-29_11-30.zip` to `out/data` in PyCIRAS.

If the data is used in another way:
1. Clone this repository
  ```git clone https://github.com/Majistaten/PyCIRAS-reproduction-package```
2. Unzip the content of `2024-03-29_11-30.zip`.