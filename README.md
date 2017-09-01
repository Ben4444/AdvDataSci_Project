# AdvDataSci_Project
Final Project for Advanced Data Science I
# I will be completing the project focused on pulling social media data to identify times and areas hardest hit by Hurricane Harvey.
# Scraping Data #
# I will be using Twitter as my social media platform, and will rely on a combination of the Twitter API and online tutorials to 
# help me with scraping the data.
# The first step is to gain access to the Twitter API, which I have done by following the tutorial found at this link:
# http://adilmoujahid.com/posts/2014/07/twitter-analytics/
# Note: The above link is a super useful tutorial for scraping Twitter data, and I will definitely go back to it later.
# Here is the link to my Twitter app page: https://apps.twitter.com/app/14193250
# Next, I need to download and install the Python library Tweepy, in order to connect to Twitter Streaming API and download data.
# I have done this by following the installation instructions here (Python and pip must be installed first for this to work)
# (Note on pip: Must type 'python -m pip XXXX' (without quotes) in order for the command to work):
# https://github.com/tweepy/tweepy
# Next, I created a Python program called twitter_streaming.py, based off of the instructions found at
# http://www.mikaelbrunila.fi/2017/03/27/scraping-extracting-mapping-geodata-twitter/, and have started my stream searching for the 
# hashtags 'hurricane', 'harvey', and 'hurricane harvey'. I am exporting the output to a JSON file, twitter_data.json, which I will 
# later have to parse for relevant data.
# I began the Twitter data stream at 7:17AM on 9/1/2017.
# The link http://www.mikaelbrunila.fi/2017/03/27/scraping-extracting-mapping-geodata-twitter/ referenced above also gives useful
# instructions for extracting geodata from tweets, and I will follow this tutorial once my data is collected.
# Analyzing Data #
# Once my twitter data is collected and geocoded, I will import this into ArcGIS for visualization, and import into R for analyses
# Using spatial statistics. With spatial stats I will be able to quantify the spatial intensity and degree of clustering of tweets
# With my chosen hashtags, and this can be used to make heatmaps and identify the areas where the most tweets about Hurricane Harvey
# are coming out of, which will be used as a proxy to identify the hardest hit areas
# (assume the people living in worst hit areas are also tweeting the most about the hurricane).