# BRI_mentioned_retweet_followed

## Research Question 
What are the most frequently retweeted accounts?

How similar are the retweeted accounts between APAC datasets?

What are the most mentioned users?

Who are the most followed users?

Which politicians are getting amplified by users in this dataset

## File Overview

### mentioned_data
data for most mentioned users

### most_followed_data
data for most followed users

### politician_twittter_data
data for politician userids on twitter (twitterid_XXX.csv)

data for the results of politicians which were mentioned, followed, or retweeted by accounts in the dataset

### retweet_data
data for retweeted users
data for userid and twitterid dictionary (use new)

### TMRC14_followed.ipynb
code to extract most followed users in TMRC dataset

run this file by inputting your access_key_id and secret_access_key in cell 2

make sure to install all necessary libraries in cell 1

specify the right path for downloading the data in the last cell

### TMRC14_jaccard.ipynb

code to find the Jaccard's similarity of hashtags and retweets between APAC datasets

make sure to have data downloaded and specify the correct path in cell 2 (comment out hashtags data in cell 3 if unneeded)

### TMRC14_retweet_acounts.ipynb
code to extract most retweeted users in TMRC dataset

run this file by inputting your access_key_id and secret_access_key in cell 2

make sure to install all necessary libraries in cell 1

specify the right path for downloading the data in the last cell

### dict_adder.ipynb

adds more additional data to user_dict

specify paths for local computer and specify access key in cell 2

### twitterei_retweet_accounts.ipynb
code to extract most retweeted users in twitterei dataset

run this file by inputting your access_key_id and secret_access_key in cell 2

make sure to install all necessary libraries in cell 1

specify the right path for downloading the data in the last cell

### twitterid_searcher.ipynb
code to check for the existance of politicians in the retweet, followed, and mentioned data

specify correct paths in cell 2

