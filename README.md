This project will go through a process of using pre-trained model Resnet and deploy it by Flask. We use python 2.7 and tensorflow 1.14.0 in this project. If you have problems with the installation of tensorflow, please check your python version first.

# Introduction


# Folder structure


# How to run

## Step 1: Create virtual environment and install packages in the venv

```python
virtualenv --python=python27 venv
source ./venv/bin/activate
pip install -r requirements.txt

```

## Step 2: Create a helper function with a pre-trained model. This step is implemented by the `app_helper.py`

