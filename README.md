# Playstore-Analysis

## Context :
The Play Store apps data has enormous potential to drive app-making businesses to success. In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We'll look for insights in the data to devise strategies to drive growth and retention.

Let's take a look at the data, which consists of two files:

playstore data.csv: contains all the details of the applications on Google Play. There are 13 features that describe a given app. 

user_reviews.csv: contains 100 reviews for each app.

## Object :
Explore and analyze the data to discover key factors responsible for app engagement and success.

## Description :

### Playstore Data :

App: Application name

Rating: Overall user rating of the app

Reviews: Number of user reviews for the app

Size: Size of the app

Price: Price of the app

Installs: Number of user downloads/installs for the app

Type: Paid or Free

Content Rating: Age group the app is targeted at - Children / Mature 21+ / Adult

### User Data:
Genres: An app can belong to multiple genres (apart from its main category)

App: Name of app

Translated_Review: User review (Preprocessed and translated to English)

Sentiment: Positive/Negative/Neutral (Preprocessed)

Sentiment_Polarity: Sentiment polarity score (>0 - positive, <0 - nagative)

Genres: An app can belong to multiple genres (apart from its main category)

## Conclision :
By analyzing the data closely, we have inferred a few of the observations.

• Google PlayStore has 2 types of applications, mainly Free and Paid. Free apps (92.2%) are more than Paid apps (7.8%) considerably.

• There are various categories amongst which there are multiple applications- Three major apps are Family, Games and Tools.

• There are various gernes amongst which there are multiple applications- Three major apps are Tools, Entertainement and Education.

• Applications receive both Ratings and Reviews and can be respectively graded too.

• For the apps, Content rating also provided. Content Rating - Everyone rated apps has share of 81.8% in total apps.

• Business, Game, Family and Tools have the highest number of applications.

• Free applications make 98% of the total of Applications, with a total count of more than 8000.

• Communication, Games and Tools are the most installed Application category.

• Most of the apps with higher rating range of 4.0, 4.3 are having high amount of reviews and installs.

• From User data we can learn that, positive sentiment for apps is more compared to other 2 sentimants. Positive sentimant shares total of 64.1% in overall sentimant.

• After mergining both datas, we find put the sentimant share for both paid apps and free apps. For both types, Positive sentimant is high.

• We found the sentiment levels for both free and paid apps seperately for variables like category, genre, App, Rating, Content rating and Rating.

• We also checked sentiment levels for merged data for varials in the data.

Thus a lot of factors play an important role in the user usage and popularity of any application. It can be because of the price of the application, based of the rating and reviews, also because of the number of installs, which in turn also affects the decision making of any app.

