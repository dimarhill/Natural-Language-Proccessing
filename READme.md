# Project 3: Web APIs & NLP
---
### Author: Matthew Hill
---

ESPN is the #1 sports broadcasting channel in the world. It goes without saying when it comes to sports and showcasing it nobody does it better than us. There is always challenges when being at the top to become content with were we are and that is understandable. As great as we are as a company and even though we are #1 there is always room for improvement.

At this point I bet you are wondering what could be better than #1. Obviously there is not much but there is one thing in mind... How about we crank up the efficiency is this place! There is one spot we are lacking in and that place is having and algorithym that correctly predicts were a subreddit comes from in regards to our different sports. And that has to improve because we do not want our users looking at NBA reddits when they want to look at NFL subreddits.

Lucky for you guys you have the #1 Data Scientist in the world to create that more efficient algorithm. With the help of the rest of my team we will test out a few different classifiers in combination with Naturual Language Processing to come up with the most efficient model that we can possibly come up with.

Here in the Data Science depart my team and I using Pushshift's API collected posts from two subreddits one being NBA and the other being the NFL. The first classifier model we used was a model called Naive Bayes with strengths in solving multi-class problems and assumption of independence that was our first pick. Our second classifier we just was Logistic Regression which was also great for categorical data and easy to implement style. Last but not least we used the Random Forest model which is great for large data and also good at building different ways to find the best model.

While using all the same parameters for each only one could come out on time. The model that predicted the best score was Random Forest. With an accuracy score of 99% I think we can all agree that this is very good for a model that is predicting the correct subreddit just off a couple of words. So the plan going forward is to implement this model in our database so we can be more efficient. We are #1 but this will definitely help us stay that way for a little while longer. So I say lets do it no harm in being even better than we were!
