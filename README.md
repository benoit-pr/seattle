# seattle

Data :  '2016 Building Energy Benchmarking', collected by the city of Seattle (https://data.seattle.gov/Permitting/2016-Building-Energy-Benchmarking/2bpz-gwpy/about_data).

The goal of this project is to use the data collected to be able to predict the Energy Use of a building, and its greenhouse gases emissions.
Those are the two targets.

Notebooks : 

1_Cleaning : cleaning + analysis of the data

2_Modeling_EnergyUse             : different models are tried in this notebook, from simpler ones to more complex. The goal is to predict the target EnergyUSe

3_Modeling_GHG                   : different models are tried in this notebook, from simpler ones to more complex. The goal is to predict the target GHGEmissions

4_Modeling_GHG_with_EnergyScore  : different approaches are tried in this notebook, from simpler ones to more complex. The goal is to predict the target GHGEmissions, by also taking into account the feature 'EnergyStarScore'.


Best predictions are found in Notebook 4.
