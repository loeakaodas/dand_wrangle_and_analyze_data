# Wrangling @dog_rates (WeRateDogs) tweets and related data

### Overview

Project consisted of gathering data from multiple disparate sources to be cleaned and combined into a single tidy dataset.

**Required steps:**

* Gather data from a variety of sources and in different formats
  - Import provided twitter-archive-enhanced.csv file from disk
  - Download the image-predictions.tsv file from Udacity using requets library
  - Call Twitter API to get full JSON objects for each tweet_id in the provided archive and store to a single txt file
  - Read in the generated tweet_json file from the API call
  
* Assess and fix quality and tidiness of data
      -  Find issues w/ the data
      -  Fix them
      
* Showcase/analyze the complete, clean, and tidy dataset
  - Analyze the dataset to find any interesting relationships
     * Ratings over time
     * Ratings by type/name (doggo, floofer, pupper, puppo)
     * What are the most common breed predictions 
  -  Visualize the findings
