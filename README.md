Twitter Dataset for Cloned Account Detection
Introduction
This dataset is generated from Twitter API v2 for experiments in the paper "CADIF-OSN: Detecting Cloned Accounts with Missing Profile Attributes on Online Social Networks" accepted in CIKM 2024. The dataset was created using the account with the largest number of followers on Twitter at the time (@Cristiano Ronaldo).

Dataset Description
The dataset contains public information of 70,000 random accounts from the followers list of @Cristiano Ronaldo. Each account record includes the following attributes:

username
id
screen_name
location
description
protected
verified
followers_count
friends_count
tweets_count
favorites_count
created_at
default_profile
has_profile_image
listed_count
profile_image_url_https
label
Additionally, we have crawled a dataset of cloned accounts in the form of pairs from Impersonator Study. These accounts have an extra attribute compared to the common accounts:

counterpart: This attribute represents the genuine account and its corresponding impersonated account.
label: This attribute is used to classify if the account is real or cloned.
Citation
If you use this dataset in your research, please cite the following reference in your paper:

