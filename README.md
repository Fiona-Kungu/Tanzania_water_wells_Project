## TANZANIA WATER WELLS
DrivenData has launched the "Pump It Up" challenge to draw attention to Tanzania's lack of potable water. Worked on this data set as my module 3 project.

Challenge:
According to worldometers.info, Tanzania is the largest nation in East Africa with a 59,353,795 people. Of this population, 25 million do not have access to clean water, and 40 million do not have access to better sanitation. For humans, water is a basic requirement. In agreement with Taarifa, the Tanzanian Water Ministry sought to address this issue by enhancing access to clean water sources. There are currently many water wells in place, however some of them require maintenance or repair.


Aim:

Building a model that forecasts water point functionality is the aim of this research. Authorities can identify which water points are functional, non-functional, and functional but in need of repair using this prediction model. The Tanzanian government can use this model to identify wells that are likely to require maintenance or to provide helpful information for new wells. With the aid of this model, we can show Tanzanian officials how to effectively utilize their water resources. Additionally, it supports the government's well investment.

Solution:

The  model created can forecast the operation of wells with an accuracy of 80%. With accurate functionality predictions, potential solutions include;

prioritizing repairs for healthy running wells that produce clean water and concentrating repairs on well clusters in particular

Data:

The initial data came from the DrivenData challenge, "Pump it Up: Data Mining the Water Table." There are basically four separate types of data: submission format, training set, test set, and train labels set, which comprises well status. Competitors are asked to create a predictive model with the training set and labels provided, apply it to the test set to ascertain the wells' state, and then submit it.

I used a train set and train label set with 59400 water point data and 40 features for this project.

What I did:

Data Understanding

Data Cleaning and Exploration

Getting Data Ready for Modeling

Baseline

Data Modelling

More exploration on the notebook often contain more thorough findings.

Future Developments:

The first challenge will be handled by feature selection and feature engineering on categorical columns.
A more effective solution will be found for an unbalanced target problem.
To address the overfitting issue, parameter optimization for the XGBoost Model will be improved.
According to more precise and recent data, wells can be monitored effectively and models can be improved.
Climate, rainfall season, and other variables vary by region. Therefore, using the primary model, various models can be constructed for each region.