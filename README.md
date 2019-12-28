# dataWranglingTweepy
Wrangle and Analyse Data: Using Twitter Archive for @WeRateDogs account  - Twitter’s tweepy API </br>
# Introduction
(as provided by Udacity)</br>
The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. 

## Goal
Wrangle `@WeRateDogs` Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.

## The Data 
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." (here 'twitter-archive-enhanced.csv')

## Tasks
- Data wrangling, which consists of:
  - Gathering data
  - Assessing data
  - Cleaning data
- Storing, analyzing, and visualizing your wrangled data
- Reporting on 1) your data wrangling efforts and 2) your data analyses and visualizations

### Gathering Data
- The 3 parts of data were gathered into the `wrangle_act.ipynb` file.</br>
  1. The WeRateDogs Twitter archive. (twitter_archive_enhanced.csv)
  2. The tweet image predictions. (image_predictions.tsv) This file was downloaded from Udacitys's server using the `requests` library 
  3. Each tweet's retweet count and favorite ("like") count at minimum using Twitter's `tweepy` API
  
### Assessing Data
- Visual and Programmatic assessment of data was done to detect the data cleanliness issues.
- These issues were further documented into two categories `Quality` and `Tidiness` issues.

### Cleaning Data
- The issues detected above were tackled as following:
  - Defining the issue
  - Cleaning the issue using python `pandas` and `numpy` libraries
  - Testing to check whether the issue has been solved.
  </br>
The cleaned Data was stored in the `twitter_archive_master.csv` file.</br>
Further the data was analysed and visualized by drawing insights and conclusions which can also be found in `wrangle_report.md` and `act_report.md` 
