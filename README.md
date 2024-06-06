# RR_project_HHRPTeam
reproducible-research Project for UW

# Paper: Credit Risk Assessment based on Gradient Boosting Decision Tree
# Machine Learning Project Setup Guide

This guide will walk you through setting up your Python environment, installing necessary dependencies, and running the code for a machine learning project.

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Access to a command-line interface (CLI)

## Installation

Follow these steps to set up your project environment:

### 1. Install Python

1. Download the latest version of Python from the official website: [Python Downloads](https://www.python.org/downloads/)
2. Run the installer. Ensure you check the option to **"Add Python to PATH"** before clicking **"Install Now."**
3. Follow the on-screen instructions to complete the installation.

### 2. Set Up a Virtual Environment

Using a virtual environment for your Python projects is recommended to manage dependencies efficiently:


# Navigate to your project directory
cd path/to/your/project

# Create a virtual environment named 'env' (you can choose any name)
python -m venv env

# Activate the virtual environment
# On Windows:
.\env\Scripts\activate
# On macOS or Linux:
source env/bin/activate

### 3. Install Required Packages

Install all necessary Python packages using pip:


# Make sure your virtual environment is activated
pip install numpy pandas scikit-learn matplotlib xgboost

Running the Code
### 1. Prepare Your Code
Use a text editor to write your code and save it as a .py file, or use an IDE like PyCharm, Visual Studio Code, or Jupyter Notebook for interactive coding.

If using Jupyter Notebook, you need to install and run it:
pip install notebook
jupyter notebook

Deactivating the Virtual Environment
When you are done working, deactivate the virtual environment to return to your system’s default settings:
deactivate