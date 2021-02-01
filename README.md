# AdverityDataChallenge
Adverity Data Challenge

This data challenge had two goals:
1. Aggregate click data into hour time bins, and calculate the click-through-rate (CTR)
2. Implement a simple outlier detection using a moving average

The notebook is split into three sections:
1. Loading, cleaning, inspecting data
2. Aggregating and calculating CTR
3. Finding outliers

Data challenge has been completed in a single Jupyter notebook file: AdveritfyDataChallenge.ipynb
Cleaned data for steps 2 and 3 has (while unusual) been included in directory for ease:
- Prepared data: ctrCleanData.csv

## Dependencies 
Dependencies are specified in the requirements.txt file, however this file was generated from the Conda environment that I was using. I inculuded it to be thorough. 

Non-verbose Dependencies:
- Python 3+
- pandas 1.2.1+
- seaborn 0.11.1+
- matplotlib 3.3.2+
