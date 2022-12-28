## Udacity - Starbucks Capstone project 

This repository contains my work in the scope of the Udacity Nanodegree Programm *Data Scientist* for the starbucks capstone project.

This project works with simulated data that mimics the beahvior of customers on the *Starbucks reward* app. The challenge of this project is to figure out which customer should receive which offer type. Results are also documented in this medium blog-post: https://medium.com/@lenarubeni/make-people-buy-more-in-the-starbucks-app-e27ba06d825


Table of Contents

- Installation
- Description of Datasets
- Project Motivation
- Results
- Acknowledgments

This repository contains the jupyter notebook with relevant code as well as the datasets. 

## Installation

For running the project yourself, you have to run the jupyter notebook with the according datasets. Furthermore, the following packages are necessary:

- pandas
- numpy
- math
- seaborn
- sklearn
- matplotlib
- json


## Description of datasets

The project includes three datasets

The portfolio dataset contains information about different offer types with information about the duration and reward of a specific offer.

The profile dataset contains information about users of the starbucks reward app. Including information about the age, income and gender of the user.

The transcript datasets contains event information (four different event types) for certain users. It also gives information about wether a certain offer has been completed or not. 


## Project Motivation

The goal of this project is to get an understanding of users of the Starbucks reward mobile app in order to send effective offers to customers.
Questions that are of interest in the scope of the project are:

Which users are more likely to respond to an offer?

Which offers have been effective in the past and what characterizes an effective offer?

How can we predict the effectivenes of an offer for a certain user?

## Results

From the dataset I generated the following insights:

1. Which users are more likely to respond to an offer?

It seems that female customers have a tendency to respond to offers more often than males. From the data I can retrieve that age and income have a sort of influence on offer completion. 
2. Which offers have been effective in the past and what characterizes an effective offer?

Effective offers of the past have been of type disocunt and bogo (discount being more effective than bogo). Offers with type discount have a 64% chance of being comlpeted when a customers receives such an offer. For bogo this is true for "only" 57% of customers.
Also, the offer type most often completed has a duration and difficulty of 10 with a reward of 2.

3. How can we predict the effectivenes of an offer for a certain user?



# Acknowledgments

All data and project idea was provided by Udacity. 
