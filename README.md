# CREDIT_CARD_LEAD_PREDICTION-JOB-A-THON


Problem Statement

Credit Card Lead Prediction Happy Customer Bank is a mid-sized private bank that deals in all kinds of banking products,like Savings accounts, Current accounts, investment products, credit products, among other offerings.

The bank also cross-sells products to its existing customers and to do so they use different kinds of communication like tele-calling, e-mails, recommendations on net banking, mobile banking, etc.

In this case, the Happy Customer Bank wants to cross sell its credit cards to its existing customers. The bank has identified a set of customers that are eligible for taking these credit cards.

Now, the bank is looking for your help in identifying customers that could show higher intent towards a recommended credit card, given: Customer details (gender, age, region etc.) Details of his/her relationship with the bank (Channel_Code,Vintage,'Avg_Asset_Value etc.)




Table of Content

Step 1: Importing the Relevant Libraries

Step 2: Data Inspection

Step 3: Data Cleaning

Step 4: Exploratory Data Analysis

Step 5: Building Mode





Conclusion: 

As a learner this is my first experience with this type of competition.Whatever I learned from analytics vidhya tried to apply here.

1.First of all I found that there are missing values in the data. The column which has missing value is categorical so filled with mode.Then I did visualization in that I found that except ID every column is important for our analysis.

2.Then I started model building first I chose DecisiontreeClassifier because it is a classification problem but I got poor results so I switched to logistic and linear regression. Linear regression gave me better result than logistic and decision tree.But this is not upto the mark.So I decided to use ensemble learnings In that I used catboost, random forest,Xgboost,Light bgm stacking and averaging from all of this cat boost and Xgboost gave better result. Finally I decided to use Xgboost over catboost because of better AUC. It was a great experience. Thank you........
