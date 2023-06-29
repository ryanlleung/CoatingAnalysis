# Coating Analysis

The purpose of this repository is to model and predict the thickness profile of coatings done by plasma sputtering and electron-beam physical vapour deposition based on machine-learning tools from experimental data.

## Method

...

## Application to tape targetry coating jig

The tape targetry coating jig is a device that allows the efficient coating of 180 micron-thick targets on a 3.6 m Kapton tape. 

Based on thickness profile modelling, the corresponding thickness factor of each target can be estimated. A csv file is generated with the thickness factor of each target. This csv file can be used for quality control purposes.

# Installation

Anaconda is recommended for installing the necessary packages for this project. Anaconda is a free and open-source distribution of the Python programming languages for scientific computing, that aims to simplify package management and deployment. 

## Download and install Anaconda
Visit the [Anaconda website](https://www.anaconda.com/products/individual) and download the installer for your operating system.

## Setting up the environment
After installing Anaconda, open the Anaconda Prompt from start menu of your computer. You may use Anaconda Navigator as well, but Anaconda Prompt is recommended for this project.

Create a new environment with the following command:

```
conda create -n coating-analysis python=3.9
```
Activate the environment with the following command:

```
conda activate coating-analysis
```
You should see the name of the environment in the beginning of the command line.

## Installing the necessary packages
Install the necessary packages with the following commands.

```
pip install numpy
pip install pandas
pip install scipy
pip install matplotlib
pip install tensorflow==2.10
...
```


