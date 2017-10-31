# kaggle_music_rec
kaggle kkbox music recommendation code. 
https://www.kaggle.com/c/kkbox-music-recommendation-challenge/l
Overview:
I intentionally train-test split based on the location of data within the csv, as the data is time series. I do custom feature extraction based on the index location. 
Then I ensemble lgb, xgb and some keras neural nets for a classifier. 
All data for this code will need to be downloaded from kaggle due to github size requirements. 