# File Organization

A. File structure
- codes
- datasets\input      (all raw files came here first)
- datasets\poi        (cleaned/processed data of points of interest)  
- datasets\macro      (cleaned/processed data of macro data)
- datasets\hdb        (cleaned/processed data of flats)
- datasets\combined   (combined data of flats, points of interest and macro)
- datasets\final      (final datasets before modeling)
- datasets\tableau    (image files from tableau)
- assets              (executive summary, problem statement)

B. Notebooks (8 of them) 
1. 1_data_extraction.ipynb
- initial processing of data 

2. 2_eda.ipynb
- EDA
- visualization

3. 3_map.ipynb
- map of flats and points of interest
- need a separate notebook because it runs in separate environment

4. 4_geocoding.ipynb
- convert physical addresses to geocodes

5. 5_feature_engineering.ipynb
- calculate distances between flats and points of interest
- combine all features together (flats, distances, macro data)

6. 6_preprocessing.ipynb
- Remove non-numeric features
- Remove highly correlated features
- Check for for Homoscedasticity, skewness and outliers

7. 7_keras.ipynb
- evaluate keras neutral network

8. 8_xgboost.ipynb
- evaluate XGBoost 

C. Data files
There are many data files because
- data came from many sources
- data processed at various stages were saved

Due to the file sizes, I uploadded them to gogole drive at https://drive.google.com/drive/folders/1_hZysJMyDKO7xDfXbwwFsT31HYWmBy6_

D. Deployed Price Predictor
https://hdbprice.herokuapp.com/


