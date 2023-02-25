# EDA-1-Google_playstore_analysis

i got two different dataset having name as playstore data and user review data.
playstore data has 13 columns which is 'App', 'Category', 'Rating', 'Reviews', 'Size', 'Installs', 'Type',
'Price', 'Content Rating', 'Genres', 'Last Updated', 'Current Ver','Android Ver'.
User review data has 5 columns which is 'App', 'Translated_Review', 'Sentiment', 'Sentiment_Polarity' and 'Sentiment_Subjectivity'.
I started with the playstore data and first cleaned it and done data preprocessing.
and then did the same steps on User review dataset.
Then I proceeded with Exploratory Data Analysis where i tried Answering certain business problems.
Following are the conclusion of the Analysis:

Family is the most popular category in the playstore followed by Games and tools.
User tends to install Games more than any other type of apps. Games and communication has the maximum numbers of installs.
when we compare rating with category, we can say that almost all the categories has similar rating.
Next we come to the average rating of the app, and we saw that most of the people have given top ratings of between 3.5 and 4.8.
From the analysis, we can saw that 92% (8896) of apps in google play store are free and 8% (753) are paid.
When it comes to paid app , minecraft has generated the maximum revenue of $69900000
Most of the applications are belongs to “Everyone” which means not restricted to age.Focusing more on content available for Everyone will increase the chances of getting the highest installs.
we can imply that majority of the free apps are small in size and having high rating. While for paid apps, we have quite equal distribution in term on size and rating.So we concentrated on free apps and sizes that are compatible with every Android device
We can conclude that "Facebook", "WhatsApp Messenger", "Instagram" are the top three apps have highest reviews.
We also found any correlation between all the columns and we found that installs and reviews are highly correlated, which concludes that a high number of installs has the highest number of reviews.
After analysis of user's sentiments, we found that the Positive reviews are large in number while negative and neutral reviews has lower number.

when we analysed the sentiments based on categories we got to know most of the reaction are from 'Game' catagory and very less from 'Comics', 'Events', 'Maps_And_Navigation' and 'Weather'. i.e. it shows that people take more interest in Game catagory app as compare to other apps.

From the scatter plot of sentiments it can be concluded that sentiment subjectivity is not always proportional to sentiment polarity but in maximum number of case, shows a proportional behavior, when variance is too high or low
