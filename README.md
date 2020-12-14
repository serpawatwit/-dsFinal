# Deployed Data Science State Employee analyzer


## Introduction
The objective this project is to analyze traffic stop data and determine if there is any correlation between pullover offense and resulting penalty (fine, ticket, warning, etc.) based upon not only gender, but race as well. Given the current landscape of our legal system, My teammate and I were curious if this extended beyond arrests and further into every day police patrols. Also, a secondary objective of this project is using Heroku platform (similarly to the sample project) as a service to deploy the results of this project to a web app.

As briefly mentioned above, this project was inspired by the current landscape of the United States legal system. Our team didnt want to dive into any highly sensitive subjects such as police brutality and found this subject to be far more appropriate in the context of this class and this project. The motivation to deploy the data to a web app does admitedly come from the sample project which exposed me to how accessible creating this app could truly be. To analyze my dataset, I'll be utilizing numpy/panda and scikit.

Being able to reference a sample project truly helped our group. It helped give us an idea of how to expand upon the project we worked on. This also lead up to [Streamlit](https://www.streamlit.io/), an open source library that greatly assisted the web app development process.

## Selection of Data

The model processing and training were conducted using a Jupyter Notebook and are available [here](https://jupyter.cs.wit.edu/user/serpaw/notebooks/Untitled3.ipynb).

This data set originally had 1,018,635 data points within 35 columns. Due to this extensive size, we decided some munging was necessary. First of all, we minimized the number of columns within the dataset. Accomplishing this, however, was a harder task than previously thought. Some of data was influenced by extraneous factors during the traffic stop. Factors such as bring under the influence, not wearing a seatbelt, causing an accident, causing others to be in an accident, causing a fatality, etc. We decided that if any of these columns were true, that the entire data point was not to be used. Then, once all this was done to all necessary columns, the column itself was deleted. This was an attempt at normalizing the data. Our goal was to analyze the data of a traffic stop that did not result in any further complications. After conducting this data trimming, we were left 938,224 samples within 6 columns. These columns were; State, VehicleType, Violation, Charge, Gender and Race. 

We also decided to randomly sample 5,000 of these entries so we not only had a significant amount of data, but didn't overwhelm ourselves with too much information. In the future, I believe we will potentially work with the entire dataset, but that was unrealistic for us at the current time. 

The original data set can be found online at git (insert link). The modified dataset can be found online at git (insert link) as well. 

Data preview:
(Insert Image)

Our data set has categorical features in all 6 columns. As suggested in the sample project, we utilized OneHotEncoder/ColumnTransformer on these features.\

## Methods
Tools:
- 
- 
- 
- 

Inference Methods used with Scikit:
- 
- 
- 
- 

## Results
App is here
What it does
(Screenshot here)

## Discussion

## Summary

## References
