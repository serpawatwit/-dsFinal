# Deployd Data Science State Employee analyzer


## Introduction
The objective this project is to analyze traffic stop data and determine if there is any correlation between pullover offense and resulting penalty (fine, ticket, warning, etc.) based upon not only gender, but race as well. Given the current landscape of our legal system, My teammate and I were curious if this extended beyond arrests and further into every day police patrols. Also, a secondary objective of this project is using Heroku platform (similarly to the sample project) as a service to deploy the results of this project to a web app.

As briefly mentioned above, this project was inspired by the current landscape of the United States legal system. Our team didnt want to dive into any highly sensitive subjects such as police brutality and found this subject to be far more appropriate in the context of this class and this project. THe motivation to deploy the data to a web app does admitedly come from the sample project which exposed me to how accessible creating this app could truly be. To analyze my dataset I'l be utilizing numpy/panda and scikit.

Being able to reference a sample project truly helped our group. It helped give us an idea of how to expand upon the project we worked on. This also lead up to [Streamlit](https://www.streamlit.io/), an open source library that greatly assisted the web app development process.

## Selection of Data

The model processing and training are conducted using a Jupyter Notebook and is available [here](https://jupyter.cs.wit.edu/user/serpaw/notebooks/Untitled3.ipynb).

This data set, after extensive grunging and normalization, has over 938,224 sample. Due to this extensive size, we decided to randomly sample 5,000 of these entries so we not only had a significant amount of data, but didn't overwhelm ourselves with too much information. In the future I believe we potentially work with the entire dataset, but that was unrealistic for us at this current time. The original data set can be found online at git (insert link). The modified dataset can be found online at git (isnert link) as well. 
