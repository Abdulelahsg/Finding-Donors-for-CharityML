# Machine Learning Supervised Learning
## Finding-Donors-for-CharityML
### Install 
This project requires the following python libraries to be installed:<br />

*	NumPy 
*	Pandas 
*	Scikit-Learn
*	Matplotlip 

In this project, I have employed several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. 
The goal is to construct a model that accurately predicts whether an individual makes more than $50,000. 
This sort of task can arise in a non-profit setting, where organizations survive on donations.

Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with.
While it can be difficult to determine an individual's general income bracket directly from public sources, 
we can infer this value from other publically available features.

### Data
The dataset for this project originates from the [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income). 
Machine Learning Repository. 
#### Note 
The data we investigate here consists of small changes to the original dataset, 
such as removing the 'fnlwgt' feature and records with missing or ill-formatted entries.
