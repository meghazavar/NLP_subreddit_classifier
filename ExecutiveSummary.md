##  Lost Subreddit Classifier ,
> Author:Megha Zavar

### Summary
###### About Reddit
For a long time, it felt that nothing could disturb the Internet world order. Google was number 1, followed by YouTube and 
Facebook. Yet, it happened, Reddit managed to dethrone Facebook. Yet in happened in december of 2018 ,  
Reddit surpassed facebook as  3rd most popular website in 2018 behind google and youtube based on Alexa ranking,
which is a measure of website popularity. Reddit has over 330 million active users aka redditers and  138,000 active communities aka subreddits , which are growing
daily. 
It’s a online social media website for sharing news, content similar to facebook, where facebook is geared towards sharing  
content  with friends and people  you might already know. Reddit is more or a world stage with focus on your interest.
Reddit has over 330 million active users aka redditers and  138,000 active communities aka subreddits , which are growing
daily. 

One can share thoughts on any topic on any community, they have choice to  disclose  or not disclose their identity.
It has become a platform for open and  honest conversation with out fear of judgement and backlash. To some it has
become a platform for free speech. They can be themselves - write  pretty much anything that’s on their mind. That’s 
pretty powerful !! Almost  anything.....

This is where moderators come in - moderators are users that are either drafted by other moderators or users who have created
their own communities.They are volunteers unlike admins who are paid employees of Reddit. Moderators are really the 
gatekeepers or sheriffs for their communities. Their set the tone for community, they can ban users, remove posts  
when they are not in alignment with the community.

###### THE PROBLEM  & OBJECTIVE :
With massive number of communities   and  newer redditors joinging , overlapping topic interest it is  not uncommon for people
to accidently post  to a wrong subreddit. Moderators who are passionate voluteers for the reddit communities who
day in day out read through these post to maintain the health of the subreddits among other things  also need to deals
with simply wrong submissions in to the subreddit.

The goal and hope with 'Lost Subreddit Classifier' is help the moderator community, by having a machine learning classifier
classify the incoming submissions to verify if user had posted a submission to a appropriate subreddit and flag the 
incorrect ones.

### Classifier Approach
We can sketch out the data science process as follows:
1. Define the problem.
2. getting data.
3. Explore the data.
4. Model the data.
5. Evaluate the model.
6. Answer the problem.

######   MVP
The initial scope of the classifier is to classify a submissions for two subreddits ,in to the appropriate subredit with
accuracy higher than baseline score. The two subreddits chosen are Travel and food.

######  Getting data.
A sample of 10,0000 recent posts was obtained from Reddit API portal,using
![Pushshift.io](https://pushshift.io/api-parameters/) API Wrapper for reddit.com search endpoints.
The data comprised of submission post titles which is headting of the post around 120 charcters and  subreddit name
it self was the target y variable. 

### Exploratory Analysis
While every reddit post has several attributes  title , description ,author  etc.  There was a lot missing data except title.
![col](https://git.generalassemb.ly/mzavar/project_3/blob/master/eda.png)

We looked at the most frequently used words and most relevant words .
![most frequent words](https://git.generalassemb.ly/mzavar/project_3/blob/master/bag%20of%20words.png)
### Modeling the data





