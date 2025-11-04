# Computational Theory - SHA-256 Implementation

## Overview

This repository contains implementations of SHA-256 functions in Python.  
The assessment is divided into 5 different problems covering logical functions, mathmatical constant generation, message padding, hashing and passwords.

## Repository Structure

- `README.md` Provides an overview of the project and installation & usage guide
- `requirements.txt` List of Python dependencies provided
- `.gitignore` List of file types to be ignored in repo
- `problems.ipynb` Jupyter Notebook of problem implementations

## Requirements

- Python 3.9+ (for type hints)

### Dependencies

Install required packages using:  
`pip install -r requirements.txt`

## How To Run

### Using Jupyter Notebook

1. Clone this repo
2. Install dependencies as above - `pip install -r requirements.txt`
3. Launch Jupyter: `jupyter notebook`
4. Open `problems.ipynb`
5. Run cells top to bottom sequentially

## Problems Implemented

### Problem 1: Binary Words & Operations

Implementation of seven logical functions used in SHA-256, as defined in the Secure Hash Standard.

- Parity, Choose(ch), Majority(maj)
- Big Sigma 0 & 1, Small Sigma 0 & 1
- Helper functions: ROTR, SHR

### Problem 2: Fractional Part of Cube Roots

Generation of cubes roots of (x) prime numbers, first 64 used in SHA-256.  
Compared against constants listed in SHA-256 Secure Hash Standard as proofing.

### Problem 3: Padding

Using a generation function to provide message padding according to SHA-256 specification.

### Problem 4: Hashes

[To be completed]

### Problem 5: Passwords

[To be completed]

## References

- [FIPS 180-4: Secure Hash Standard](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)
- [PEP 257: Docstring Conventions](https://peps.python.org/pep-0257/)
- [NumPy Documentation](https://numpy.org/doc/stable/)

## Author

Eric Murray - G00423903
