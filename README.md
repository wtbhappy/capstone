# Problem Statement

For most people, purchasing a property is their biggest investment and so it is important for buyers to know if they can afford the downpayment and the mortage payment. In Singapore, the government gives generous subsidies for first-time home buyers of public housing flats built by Housing and Development Board (HDB). Singaporeans that meet the criteria (there is an income ceiling) took advantage of this policy to own their homes, resulted in 80% of the residents living in HDB flats.
The private property market is for local high income earners and HDB flat upgraders. Many foreigners also see Singapore as a safe haven to park thier monies here.
The price of a property is determined by many factors. Beside the condition, size and location of the house, it is also affected by the state of the economy, government policy and supply and demand.
I will compare different regression models to predict the prices of HDB flats, based on the propertys' attributes, their proximity to points of interest, market supply and demand and macroeconomic factors. 
I will be using RMSE to measure model performance, and the model should at least improve upon baseline by 10%. Baseline will be the RMSE from Ordinary Least Square.

# Summary
A. Notebooks

I have created 4 notebooks 
1. capstone_data for processing initial data (100% completed)
- data for hdb flat resale transactions from 2015 to 2020 collected
- data for macroeconomic factors, supply and demand collected
- data for points of interest collected
- fetched all necessary geocodes

2. capstone_eda for visualization
- plotted for macroecnomic factors
- more visualizations to be added

3. capstone_feature_engineering
- added macroeconomic factors as features (completed)
- added distances from points of interest as features (completed)

The dataset has 89 columns

4. capstone_modeling for modeling
- facing some problems with the keras due to tensorflow (moving to colab to try out)


B. File Directories for datasets
1. datasets/input
- raw data files

2. datasets/output folder
- for processed data files after cleaning

3. datasets/final
- for datasets with features added
- due to github's file size limitation the combined file has been uploaded in zip format

C. Outstanding Issues
- keras/tensorflow problem (moving to colab to try out)

