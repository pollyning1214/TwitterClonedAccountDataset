# Twitter_dataset_clonedAccount
Here is the dataset generated from Twitter API v2 for experiments in "CADIF-OSN: Detecting Cloned Accounts with Missing Profile Attributes on Online Social Networks" accepted in CIKM 2024.

The dataset is generated with the help of Twitter API v2 with the account who has largest amount of followers at that time in twitter (@ Cristiano Ronaldo). 

The dataset crawls the public information of 70,000 random accounts from the followers list, which includes username id screen_name location description protected verified followers_count friends_count	tweets_count favorites_count created_at default_profile hast_profile_image listed_count profile_image_url_https label.

we also crawl the cloned accounts dataset which is in the form of pairs from https://impersonatorstudy.mpi-sws.org/. There is one more attribute in these accounts than the common accounts which is counterpart. This attribute represents the geniuned account and corresponding impersonated account. And also, the attribute "label" is used to classify if the account is real one or cloned one.

If you would like to use this dataset please cite the reference in your paper:


