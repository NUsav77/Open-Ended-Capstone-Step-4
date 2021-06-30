# Open Ended Capstone Step 4
This repository is the fourth step in the capstone which contains exploratory data analysis (EDA) on capstone datasets. Datasets include NEXRAD Level 2 data, TDS metadata for NEXRAD enrichment, and Twitter data.

EDA steps are conducted using Jupyter Notebooks.

## NEXRAD EDA
This Jupyter notebook consists of exploratory data analysis of the NEXRAD dataset. The EDA takes several different approaches to accessing the NEXRAD data using several different Python modules, libraries, and packages.
#### Installation
For the NEXRAD EDA, in terminal run the following commands:
- run `!conda install --yes cartopy`
- run `pip install nexradaws`
- run `pip install boto3`
- run `pip install metpy`
- run `pip install boto3`
- run `pip install numpy`
    
## TDS EDA
This Jupyter notebook consists of exploratory data analysis of the Thredds Data Server (TDS). Thredds Data Server provides enrichment metadata to compliment NEXRAD data. This allows different views and angles of NEXRAD data, including animated storm plotting.
#### Installation
For the TDS EDA, in terminal run the following commands:
- run `pip install siphon`
- run `pip install numpy`
- run `pip install matplotlib`
- run `!conda install --yes cartopy`

## Twitter EDA
This Jupyter notebook consists of exploratory data analysis of Twitter data by utilizing tweepy, pandas, and matplotlib. This data will be used to enhance the NEXRAD data set with Twitter sentiments of affected people.
#### Installation
For the Twitter EDA, in terminal run the following commands:
- run `pip install tweepy`
- run `pip install pandas`
- run `pip install spacy`
- run `pip install matplotlib`
