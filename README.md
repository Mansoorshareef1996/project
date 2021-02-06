# Predict articles that will generate negative impact(reactions on Facebook)

Social media data's growing ubiquity provides an enticing perspective for improving the quality of machine learning based models in many fields of computer science which could help people in many ways.

The enormity and high variance of the information that propagates through large users in the case of social media presents an interesting potential for harnessing societies by using their data in a way that allows specific predictions to be made. For the most famous like button an alternative has been released by Facebook in the year 2016 where users can react to an article. But in the starting years users were not keen to use these reaction buttons as they everyone use only the “Like” button very frequently. The like button was the primary choice for everyone. Users reactions to the Facebook posts have not just existed for every post but where very crucial part of the platform which impacts the algorithm of the newsfeed. Reacting with an emoji takes an extra step for the users to show their reaction to a particular post. Facebook are still considering as all the reactions are of same weight. If the reaction of the user is angry or love, the newsfeed algorithm is impacted the same. There is a very small but causes considerable statistical difference across countries in using the reactions. Users use Love reaction highest in the us and lowest in Germany, reaction ha-ha is the highest in Germany and lowest in UK and Angry highest used in France and lowest in UK (Naomi, 2009). Liking, commenting, and sharing are all approaches people can interact with the content material they discover on social media. As per the Quintly data, 70.2 percent of engagement came from Reactions, 18.2 percent came from shares and 11.6 percent came from comments.

What we aim to do in this project is that we would preprocess the data and remove all the unwanted information from it . Once that is done, we would then model our data to accurately predict the articles and classify them as either positive or negative impact article based on the reactions. We would also divide the reaction into positive reactions and negative reaction which lead us to the problem statement that we are trying to predict the articles that generate a particular type of reaction to the published articles. We have also implemented some methods which could be used to calculate the impact score on each of the articles that are posted. There are many approaches to model this type of data, but we have opted for the logistic regression model which is used to classify if a article is negative or positive.
