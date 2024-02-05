
## Mobile_Price_Range_Prediction

## Problem Statement
In the competitive mobile phone market, companies aim to analyze the sales data of mobile phones and identify the key factors that influence the prices of these devices. The objective of this analysis is to establish a relationship between various features of a mobile phone, such as RAM, Internal Memory, etc., and its selling price. Instead of predicting the exact price of a mobile phone, the goal is to categorize the prices into price ranges, indicating the relative price level of each device. By applying Data Analysis and Modeling techniques, the aim is to understand which features have a significant impact on the price range of a mobile phone. This information will help companies make informed decisions about their product offerings, pricing strategies, and market positioning to remain competitive in the dynamic mobile phone industry.
## Variable Description
Battery_power - Total energy a battery can store in one time measured in mAh

Blue - Has bluetooth or not

Clock_speed - speed at which microprocessor executes instructions

Dual_sim - Has dual sim support or not

Fc - Front Camera mega pixels

Four_g - Has 4G or not

Int_memory - Internal Memory in Gigabytes

M_dep - Mobile Depth in cm

Mobile_wt - Weight of mobile phone

N_cores - Number of cores of processor

Pc - Primary Camera mega pixels

Px_height - Pixel Resolution Height

Px_width - Pixel Resolution Width

Ram - Random Access Memory in Mega Bytes

Sc_h - Screen Height of mobile in cm

Sc_w - Screen Width of mobile in cm

Talk_time - longest time that a single battery charge will last when you are

Three_g - Has 3G or not

Touch_screen - Has touch screen or not

Wifi - Has wifi or not

Price_range - This is the target variable with value of

0(low cost),

1(medium cost),

2(high cost) and

3(very high cost).

Thus our target variable has 4 categories so basically it is a Multiclass classification problem.
## Project Summary
This project aims to analyze a dataset comprising crucial features associated with mobile phones and their corresponding prices, with the primary objective of identifying factors that influence mobile phone prices and categorizing them into distinct price ranges.

The project commences with thorough data exploration and analysis, encompassing tasks such as data cleaning, outlier detection, and treatment to ensure the data's quality and reliability.

To enhance the predictive capabilities, feature engineering techniques are applied, creating meaningful predictors such as the RAM to Internal Memory ratio and combined scores for Camera Quality and Battery Capacity.

Subsequent to feature engineering, exploratory data analysis (EDA) is conducted to visually represent relationships between various features and selling prices, unveiling patterns and correlations that can guide the subsequent modeling phase.

The final stage involves constructing a predictive model utilizing machine learning algorithms to effectively categorize mobile phone prices into specific ranges. Rigorous evaluation of the model's performance is carried out to ensure precise predictions of price ranges.

By identifying key price drivers and developing a robust predictive model, this project aims to furnish mobile phone companies with actionable insights, enabling them to optimize their product offerings and thrive in the competitive market.
## Models Used

1) Random Forest Classifier
2) K-Nearest Neighbour
3) Support Vector Machine
## Result
With a test accuracy of 96% after hyperparameter tuning, the Support Vector Machines (SVM) outperforms the other models, making it the best performing model.
## Output

## 

![output](https://github.com/ady909/Mobile_Price_Range_Prediction/assets/57126736/21e01113-fbb8-4847-a243-2f17f1fc924f)

