## Carbon Cut

An open-source resource for making high-quality building decarbonization characteristic predictions from simple and common data points, found in the [NREL ResStock dataset](https://resstock.nrel.gov/datasets)

This repository serves as documentation for our project, and a guide for future work. This project was started as part of the WattCarbon Challenge at the [MIT Energy & Climate Hackathon](https://www.mitenergyhack.org/) in November 2023, where it won the second place prize.

-> savings_prediction.ipynb trains and evaluates a model to estimate the savings (in terms of carbon emissions, energy, and dollars) for each intervention in a given set, given only the hourly loadshape data for the building in question. 

-> metadata_prediction.ipynb aims to train a model to predict specific and relevant aspects of a building (eg. square footage, foundation type, appliance efficiency) given the hourly loadshape. 
