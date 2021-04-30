# ConcreteStrengthPredictionApp

## Description

An Application for Concrete Strength Prediction using:
+ Linear Regression
+ Lasso 
+ Ridge

This App is based on Pranay Modukuru's [Notebook](https://github.com/pranaymodukuru/Concrete-compressive-strength)
and got developed within the context of the Mat-O-Lab project.

## Installation

When not hosted on Aiidalab Plattform, this App needs to install some requirements.


Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the requirements.txt file.
Navigate to the Directory where you downloaded this Repository and execute this command in your Terminal.

### Python 3
```bash
pip3 install -r requirements.txt
```
### Python 2

```bash
pip install -r requirements.txt
```
After installing the requirements enable the ui elements

```bash
jupyter nbextension enable --py widgetsnbextension
```

## Usage

Navigate to the Directory where you downloaded this Repository and execute this Command in your Terminal

```bash
voila ConcreteStrengthPredictionApp.ipynb
```

A Window in your default browser should open now. The rest is pretty self explaining.