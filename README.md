# Capstone-1-Play-Store-App-Review-Analysis
Google Play, formerly known as Android Market, is the official distribution storefront for Android applications and other digital media, such as music, movies and books, from Google. It is available on mobile devices and tablets that run the Android operating system (OS), supported Chrome OS devices and on the web. Users can access Google Play to browse, purchase and download software applications from Google and third-party developers.

In this project, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. We’ll look for insights in the data to devise strategies to drive growth and retention. This data set have two csv file:
• Play store apps.csv: contains all the details of the applications on Google Play. There are 13 features that describe a given app.
• user_reviews.csv: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.

Discussion of Google play store dataset will involve various steps such as:
• loading the data into data frame, cleaning the data, extracting statistics from the dataset, exploratory analysis and visualizations, questions that can be asked from the dataset, Conclusion.

Data cleaning is the foremost step in any data science project. Cleaner the data, better are the results. We handled the missing values in some of the columns by either dropping the rows or imputing them with the median values, depending on the percentage of nulls in each feature. Then we remove duplicates values from the columns. We also remove special characters like (‘+’,’$’, ‘,’) in our dataset. We transformed some of the columns like Installs, Size and Price to numeric type for ease of analysis.

Data visualization is the graphic representation of data. It involves producing images that communicate relationships among the represented data to viewers of the images.

Conclusion

In the Sports category FIFA Soccer and 3D Bowling has the highest number of installations.
• Percentage of free apps = 92.20%
• Maximum apps in the play store are from Family category
• Category with the highest number of installs: Game
• Most popular app in the Play Store based on the number of reviews: Facebook
• I am Rich Premium app is the most expensive app in the play store.
• Overall percentage of review sentiment in which Positive sentiment count is 64%, Negative 22% and Neutral 14%.
• Helix Jump has the highest number of positive reviews
• Angry Birds Classic has the highest number of negative reviews
