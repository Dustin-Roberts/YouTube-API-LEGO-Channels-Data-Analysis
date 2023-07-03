# Exploratory Data Analysis using YouTube Video Data
**Exploring the niche market of LEGO / LEGO reselling YouTube channels**

# Aims and Objectives

This project is being used as a means to explore the following:
* Learning about the YouTube API as a means of collecting video data
* Analyzing the data collected:
    * Does the level of interaction on a video (i.e. number of likes and comments) have any correlation to the number of views?
    * Does the length of the video contribute to the number of views?
    * Does the length of the title have any relation to the number of views?
    * Does the number of tags correlate to the number of views? Likewise, what are the most common used tags in this niche market?

# Steps Needed
* Obtain video data via the YouTube API for a select number of channels related to LEGO and/or LEGO reselling
    * Create a new developer key
    * Request data
    * Clean and transform the data into a more usable format
* Pre-process the data
* Enhance / Enrich the data
* Exploratory Data Analysis (EDA)
* Conclusions

# Dataset

**Data Selection**

While there are numerous datasets on sites such as Kaggle dealing with LEGO, most of those datasets are focused on LEGO Sets, parts, and minifigures, and not YouTube video data. As such, I needed to create my own dataset using the [Google YouTube Data API version 3.0](https://developers.google.com/youtube/v3), details of which can be found below.

**Data Limitations**

This dataset is a real-world dataset, suitable for analysis. However, the selection of channels used was at my own discretion, based on my own viewership of LEGO related YouTube channels. As noted in the Conclusions section below, expanding this list to include other channels would likely result in a broader dataset to be used.

**Ethics of Data Source**

According to [Youtube API's guide](https://developers.google.com/youtube/v3/getting-started), the usage of Youtube API is free of charge given that your application send requests within a quota limit. "The YouTube Data API uses a quota to ensure that developers use the service as intended and do not create applications that unfairly reduce service quality or limit access for others. " The default quota allocation for each application is 10,000 units per day, and you could request additional quota by completing a form to YouTube API Services if you reach the quota limit.

Since all data requested from Youtube API is public data (which everyone on the Internet can see on Youtube), there is no particular privacy issues as far as I am concerned. In addition, the data is obtained only for research purposes in this case and not for any commercial interests.
