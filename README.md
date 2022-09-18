# MAST30034 Project 1 README.md
- Name: Chaitanya Chandrika Raghuvanshi
- Student ID: 1117645

**Research Goal:** My research goal is tip analysis to increase profitability for drivers

**Timeline:** The timeline for the research area is 2018-19.
Please note all work has been done on jupyter notebooks and not on .py scripts. They can be run in the following order:
1. `Loading_datasets.ipynb`: This downloads the raw data into the `data/raw` directory. Two folders will be created train_data and test_data
2. `preprocessing.ipynb`: This notebook details all preprocessing steps and outputs it to the `data/curated` directory. Please note here you will have to
get the external datasets. I have provided a google drive link to download the weather files for training and testing: https://drive.google.com/drive/folders/121CJW-qvliT26RUK_LWXhoO972Bbrzae?usp=sharing  It has been taken from the following link:  https://www.ncei.noaa.gov/cdo-web/search The second dataset was manually entered from the website as it only has 5 records regarding median household income off each borough. The link for it is: https://www.census.gov/data/developers/data-sets/acs-5year.html The taxi zone shapefile is also in the raw folder. This notebook is my main one with all the analysis and relevant plots.
4. `modelling.ipynb`: This notebook is used to conduct analysis on the curated data.
