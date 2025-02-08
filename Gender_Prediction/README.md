# Gender Prediction From name 
## Objective 
This project aims to predict the gender from the name entered by user.This prediction in done in excel without using any advanced language like python, Later on for checking accuracy, I have done this in python too.This Gender prediction project was a part of my fellowship at DataPlay.<br>
## Overview
The dataset used consist of two columns name and Gender.For human beings its easy to listen a name and say whether it's male or female,but for machine we need to train it with certains rules .When we humans listen a name we often check by its prounciation,using this idea model trains machine using the last letter of given names and finding name ending with a certain letter is majorly male or Female. <br> **Steps performed in Excel** : <br>
- Extracting Last Letter
- Spliting the Data into stratified Split : Training Data (70%) , Validation Data (30%)
- Make Pivot table of training data to know the count of males and females for all last letters.
- Predicting Gender on Validation data using Pivot table.
- Checking the Accuracy and F1 Score of Prediction.
- **F1 Score Achieved**: ~ 80% <br>
**Steps Performed in Python:** <br>
All these steps were perfomed in python using python script. Main Libraries and techniques used in python are : <br>
- **sklearn Library**
- train_test_split
- Multinomial Naive Bayes for prediction <br>
  **LinkedIn Post**: <link>https://www.linkedin.com/posts/jasbir-k-2464ab24b_gender-prediction-activity-7291487254106058752-_JYr?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD3U1ZYBGj8Nnr47v7A1stE4ItAGzqGjufc</link>
Thanks for checking. Any suggestions are welcomed. <br>
