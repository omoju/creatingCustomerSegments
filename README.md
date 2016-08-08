# Creating Customer Segments

## Project Overview

A wholesale distributor recently tested a change to their delivery method for some customers, by moving from a morning delivery service five days a week to a cheaper evening delivery service three days a week. Initial testing did not discover any significant unsatisfactory results, so they implemented the cheaper option for all customers. Almost immediately, the distributor began getting complaints about the delivery service change and customers were canceling deliveries — losing the distributor more money than what was being saved. 

The goal of this project is to find what types of customers the distributors have to help them make better, more informed business decisions in the future. The task is to use unsupervised learning techniques to see if any similarities exist between customers, and how to best segment customers into distinct categories.

## Analysis

An analysis of determining customer segment is found in the [report/report.pdf](report/report.pdf)

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Matplotlib](http://matplotlib.org/)
- [Scikit-learn](http://scikit-learn.org/stable/)
- [Scipy](https://www.scipy.org/)

### Code

Template code is provided in the notebook `customerSegments.ipynb` notebook file. Additional supporting code can be found in `renders.py`. 

### Run

In a terminal or command window, navigate to the top-level project directory `creatingCustomerSegments/` (that contains this README) and run one of the following commands:

```jupyter notebook customerSegments.ipynb```


## Data

The dataset used in this project is included as `customers.csv`. You can find more information on this dataset on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers) page.
