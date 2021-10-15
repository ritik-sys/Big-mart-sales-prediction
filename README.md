# Big-mart-sales-prediction 💰💰


### Project Link ->  https://big-mart-sales-prediction1.herokuapp.com/ 🌐🌐

![enter image description here](https://miro.medium.com/max/624/1*LXEEUY5Vf3tTCMFC41llJQ.png)

This Repository is on the BigMart’s sale prediction proposed by Analytics Vidhya.According to the information provided, Bigmart is a big supermarket chain, with stores all around the country and its current board set out a challenge to all Data Scientist out there to help them create a model that can predict the sales, per product, for each store. BigMart has collected sales data from the year 2013, for 1559 products across 10 stores in different cities. With this information the corporation hopes we can identify the products and stores which play a key role in their sales and use that information to take the correct measures to ensure success of their business.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://sars-covid19-xray-detection.herokuapp.com/)&nbsp;[![Build passing](https://img.shields.io/badge/Build-Passing-brightgreen.svg?style=flat-square)](https://sars-covid19-xray-detection.herokuapp.com/)&nbsp;[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://foodeazy.herokuapp.com/)&nbsp;[![License](https://img.shields.io/badge/license-MIT-brightgreen)](https://sars-covid19-xray-detection.herokuapp.com/)&nbsp;![Made with Love in India](https://madewithlove.org.in/badge.svg)

**Project Link** - ***https://big-mart-sales-prediction1.herokuapp.com/***




![enter image description here](https://miro.medium.com/max/875/1*DjdHeBOiO0-Pv-8-ylqHaA.png)

 ## Flowchart
![enter image description here](https://github.com/ritik-sys/Big-mart-sales-prediction/blob/main/Blank%20diagram.png)

## Data Exploration🚀
In this phase useful information about the data has been extracted from the
dataset. That is trying to identify the information from hypotheses vs available
data. Which shows that the attributes Outlet size and Item weight face the
problem of missing values, also the minimum value of Item Visibility is zero
which is not actually practically possible. Establishment year of Outlet varies
from 1985 to 2009. These values may not be appropriate in this form. So, there is a 
need to convert them into how old a particular outlet is. There are 1559 unique
products, as well as 10 unique outlets, present in the dataset. The attribute
Item type contains 16 unique values. Where as two types of Item Fat Content
are there but some of them are misspelled as regular instead of ’Regular’ and
low fat, LF instead of Low Fat. It was found that the response
variable i.e. Item Outlet Sales was positively skewed. So, to remove the skewness
of response variable a log operation was performed on Item Outlet Sales

## Data Cleaning 🚀
It was observed from the previous section that the attributes Outlet Size and
Item Weight has missing values. In our work in case of Outlet Size missing
A Comparative Study of Big Mart Sales Prediction .Univariate distribution of target variable Item outlet sales. The Target variable
is positively skewed towards the higher sales.
value we replace it by the mode of that attribute and for the Item Weight
missing values we replace by mean of that particular attribute. The missing
attributes are numerical where the replacement by mean and mode diminishes
the correlation among imputed attributes. For our model we are assuming that
there is no relationship between the measured attribute and imputed attribute

 ## Methodology
![enter image description here](https://github.com/ritik-sys/Big-mart-sales-prediction/blob/main/Blank%20diagram(1).png)

## Model Building 🚀
After completing the previous phases, the dataset is now ready to build proposed
model. Once the model is build it is used as predictive model to forecast sales
of Big Mart. In our work, we propose a model using Xgboost algorithm and
compare it with other machine learning techniques like Linear regression, Ridge
regression , Decision tree etc.

## Tech Stack and Tools 💻

 - [Python]
 - [Google Colab]
 - [Anaconda]
 - [Flask]
 - [Keras]

## Installation :zap:

 **1. Clone this repo by running the following command :-**
 ```bash
  git clone https://github.com/ritik-sys/Big-mart-sales-prediction.git
  cd Big-mart-sales-prediction
 ```
 
 **2. Now start the  server  by running the following command :-**
 ```bash
 python app.py
 ```
 
 **4.** **🎉  Open your browser and go to  `https://localhost:3000`**
 
## Contributors 🤝
 - [**Ritik Kumar**](https://github.com/ritik-sys)  

 
 
## 🤩 Don't forget to give this repo a ⭐ if you like this repo and want to appreciate our efforts
 

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)


## References
<a id="1">[1]</a> 
https://www.semanticscholar.org/paper/A-Two-Level-Statistical-Model-for-Big-Mart-Sales-Punam-Pamula/c3df505b92b6586055259a067c3d9a1d8a1d26f0

<a id="1">[2]</a> 
https://www.researchgate.net/publication/336530068_A_Comparative_Study_of_Big_Mart_Sales_Prediction

<a id="1">[3]</a> 
https://medium.com/diogo-menezes-borges/project-1-bigmart-sale-prediction-fdc04f07dc1e

<a id="1">[4]</a> 
https://www.kaggle.com/hiralmshah/bigmart-sales-prediction


