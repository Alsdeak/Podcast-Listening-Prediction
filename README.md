#  Podcast Listening Time Prediction

##  Overview
This project predicts the **actual listening time** of podcast episodes. By analyzing features like episode duration, host popularity, and sentiment, we can estimate user engagement more accurately.
#**Dataset Link:** [Kaggle - Podcast Listening Time Prediction](https://www.kaggle.com/competitions/playground-series-s5e4)

##  Project Steps
1. **Data Cleaning:** Handled missing values in `Guest_Popularity` and `Episode_Length`.
2. **Exploratory Data Analysis (EDA):** Used Seaborn and Matplotlib to find correlations between ads, popularity, and listening time.
3. **Feature Engineering:** - Handled categorical data using Label Encoding.
   - Cleaned `Episode_Title` to extract episode numbers.
4. **Modeling** Built a regression model to predict the target variable `Listening_Time_minutes`.

##  Key Insights
- The dataset contains over **750,000 records**.
- Episode length and host popularity are the strongest predictors of engagement.

##  Libraries Used
- Pandas & NumPy
- Scikit-Learn
- Matplotlib & Seaborn
