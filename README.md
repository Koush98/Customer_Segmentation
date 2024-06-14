# Toyota CSV Data Analysis

This repository contains Python scripts and Jupyter notebooks for analyzing Toyota vehicle data from CSV files.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data](#data)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to analyze various aspects of Toyota vehicle data such as mileage, fuel efficiency, and sales trends using Python and data analysis libraries.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn (install via `pip install -r requirements.txt`)

## Data Source

### Data Description
Column1 : Price of the cars.
Column2: Age of the car.
Column3: Total KM Driven.
Column4: What kind of Fuel Types it uses.
Column5: The Hp of the cars.
Column6: The Car has metalic colour or not.
Column7: Gear Transmission type automatic or manual.
Column8: CC of the car.
Column9: Available Doors.
Column10: Weight of the cars.
...
## Problem Statement
These are the problem statements provided.
1) load the data set with replacing the special characters by NAN.
2) What is the shape of the Data set?
3) What are the columns in the data set?
4) What is the Dimension of data set.
5) Count the number of int , float and object columns in the data set.
6) Print the unique values in "KM" column.
7) Replace "three","four" as 3,4,5 in the "Doors" column.
8) How many missing values are there?
9) Fill the missing values by their mean, median, mode whatever is applicable.
10) Create a scatter plot betwwen "Age" and "Price".
11) Plot a histogram of "KM" with appropriate title and labels which will show thw values of "KM" in X axis with corresponding frequencies in Y axis.
12) Construct a density plot of "Age".
13) Create a box plot of "price" column.
14) Create a count plot between "Fuel Type" and "Automatic" and study about what kind of Fueltype cars are having manual Gear Box.
15) What type of Fueltype is working on most of the cars. 

## Analysis Approach
Exploratory Data Analysis (EDA) and Visualization.
### Tools
Python
Jupyter Notebooks
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Techniques
Data cleaning and preprocessing
Visualization
