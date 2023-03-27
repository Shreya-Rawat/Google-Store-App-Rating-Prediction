# Google-Store-App-Rating-Prediction

## CONTEXT:
The Play Store apps data has enormous potential to drive app-making businesses to success. However, manyappsare being developed every single day and only a few of them become profitable. It is important for developers tobeable to predict the success of their app and incorporate features which makes an app successful. We can collect appdata and user ratings from the app stores and use it to extract insightful information. A machine learning model canbeused to predict rating for a given app, which can be used to estimate success and scope of improvement. 

## PROJECT OBJECTIVE:
The Goal is to predict the rating for an app based on the given input features like size, number of downloads etc.

## DATA DESCRIPTION: 
Web scraped data of 10k Play Store apps for analyzing the Android market. Each app(row) has values for category, rating, size, and more.

## Attributes:
(Total 13 feautres)
1. App: Application name
2. Category: Category the app belongs to
3. Rating: Overall user rating of the app
4. Reviews: Number of user reviews for the app
5. Size: Size of the app
6. Installs: Number of user downloads/installs for the app
7. Type: Paid or Free
8. Price: Price of the app
9. Content Rating: Age group the app is targeted at - Children / Mature 21+ / Adult
10.Genres: An app can belong to multiple genres (apart from its main category). For eg, a musical familygamewill belong to Music, Game, Family genres. 
11.Last Updated: Date when the app was last updated on Play Store
12.Current Ver: Current version of the app available on Play Store
13.Android Ver: Min required Android version

## Steps taken in the Project:
1. Data Cleaning and Pre-processing (Duplicate and missing values handeling, unwanted characters, invalid categories, handeling outliers, dropping redundant columns)
2. Label Encoding categorical variables and Standardizing the dataset
3. Model training, and testing:
Train a Decision tree, Random Forest, Bagging, Boosting, and Stacked Classifier
models and make predictions on test data and evaluate the models:

## Model comparision and Conclusion: 
Decision Tree, Random Forest and Bagging models show overfitting.
The best performing model is Gradient Boost having 88% accuracy without overfitting.
Number of Reviews and Size of the app contribute the most in predicting rating of an app followed by Genre, Number of downloads and Category
