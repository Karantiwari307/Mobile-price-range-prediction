# Mobile-price-range-prediction
![minimal-abstract-background-4k-f2-1920x1080 copy](https://github.com/Karantiwari307/Mobile-price-range-prediction/assets/111437123/ecc8f79c-a922-4d72-8a2c-cd6deb3051f4)

## Abstract
Various aspects like as memory, display, battery, camera, and so on are examined while purchasing a mobile phone. People make incorrect judgments because the required resources to cross-validate the pricing are unavailable. To overcome this issue, a machine learning model is created utilizing data from the mobile phone's main attributes. The model that has been constructed is then utilized to anticipate the price range of the new mobile phone. To train the model and forecast the output as low, medium, high, or very high, machine learning methods such as Logistic Regression, Decision Tree Classifier, Random Forest Classifier, XGBoost Classifier, K-Nearest Neighbor Classifier, and hyper parameter tuning using GridsearchCV are employed.

## Problem Statement
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.


## Attribute Information:
● Battery_power: Total energy a battery can store in one time measured in mAh.

● Blue: Has bluetooth or not

● Clock_speed: Speed at which the microprocessor executes instructions

● Dual_sim: Has dual sim support or not

● Fc: Front camera megapixels

● Four_g: Has 4G access or not

● Int_memory: Internal memory in gigabytes

● M_dep: Mobile depth in cm

● Mobile_wt: Weight of mobile phone

● N_cores: Number of cores of processor

● Pc: Primary camera megapixels

● Px_height: Pixel resolution height

● Px_width: Pixel resolution width

● Ram: Random Access Memory in megabytes

● Sc_h: Screen height of mobile in cm

● Sc_w: Screen width of mobile in cm

● Talk_time: Longest time that a single battery charge will last when you are talking over phone

● Three_g: Has 3G access or not

● Touch_screen: Has touch screen or not

● Wifi: Has wifi or not

● Price_range: This is the target variable with values of 0(low cost), 1(medium
cost), 2(high cost) and 3(very high cost).


## Steps Involved

1. Loading the data into data frame

2. Cleaning the data

3. Extracting statistics from the dataset

4. Exploratory analysis and visualizations

5. Train Test Split

6. Logistic Regression

7. Decision Tree

8. Random Forest

9. XG Boost

10. KNN

## Conclusion
That's all! We had completed our exercise.
So far, we have done EDA, data modeling, and model construction, beginning with data loading.
In all of these models, our accuracy ranges from 76 to 93%.
Even after hyperparameter adjustment, there is no improvement in accuracy score. So our best model's accuracy is 93%, which is considered decent.
