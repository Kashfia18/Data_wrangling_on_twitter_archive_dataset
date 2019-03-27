# Data_wrangling_on_twitter_archive_dataset

## Overview
Real-world data rarely comes clean. Using Python and its libraries, data was gathered from a variety of sources and in a variety of formats. Next its quality and tidiness was assessed and cleaned. This is called data wrangling. The wrangling efforts was documented in a Jupyter Notebook, and showcased through analyses and visualizations using Python.

## Tasks involved
The tasks involved in this project are as follows:
* Data wrangling which consists of:
  1) Gathering data
    * download the ```twitter_archive_enhanced.csv``` file manually.
    * download the ```image_predictions.tsv``` file programatically.
    * query the twitter API for each tweets JSON data and store each of the JSON data in ```tweet_json.txt``` file. Next we extracted the name, stage, rating, retweet count, favorite count and number of images from the json file of each tweet using the proper attributes.
  2) Assessing data
  3) Cleaning data
* Storing, analyzing, and visualizing the wrangled data
* Reporting on 
  1) the data wrangling efforts 
  2) the data analyses and visualizations
  
## Files
* ```act_report.pdf```: documentation of analysis and insights into final data
* ```image_predictions.tsv```: file downloaded manually using requests library
* ```tweet_json.txt```:file constructed via API
* ```twitter_archive_enhanced.csv```: file downloaded from Udacity
* ```twitter_master_dataset.csv```: csv file containing the combined and cleaned data
* ```twitter_we_rate_dogs.db```: SQLite database containing the combined and cleaned data
* ```wrangle_act.ipynb```: Jupyter workbook containing code for gathering, assessing, cleaning, analyzing, and visualizing data
* ```wrangle_report.pdf```:documentation for data wrangling steps: gather, assess, and clean

