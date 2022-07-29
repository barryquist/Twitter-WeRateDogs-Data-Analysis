# A Data Analysis on the tweet archive of Twitter user @dog_rates, also known as WeRateDogs
## By Barry Quist

## Introduction
The dataset that was wrangled was from the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. WeRateDogs has over 4 million followers and has received international media coverage. This report talks briefly about the steps taken to wrangle (gather, assess and clean) the dataset.

## Insights
The master dataset was looked through for insights. It was first realized that the maximum rating of dog was 1776/10 and the lowest rating being 2/10. 25% of the ratings were 10/10, 50% were 11/10 and 75% of ratings were 12/10. Also using histograms it was realized that tweet id, ratings, img_num, retweet_count and favorite count were all skewed to the left. But most importantly there were a lot of confidence in predition of breeds by the algorithm less than 0.1. This could mean that the algorithm needed more testing in order to predict right images. Lastly, a scatter plot was developed for retweet_count and favorite_count columns. We wanted to test if there was a relationship between the two. After plotting the scatter plot, it was realized that there was a positive relationship between retweet count and favorite count. Meaning that the more people retweeted tweets, the more people also liked the tweets.

## Visualization
A bar graph was plotted to discover the most popular rating. According to the graph, it could be concluded that 1.2 or 12/10 was the most popular rating. A lot more dogs were rated a 12/10 more than any other rating. The second most popular rating was 11/10 and the third was a 10/10.
