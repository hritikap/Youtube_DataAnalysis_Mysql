# Youtube_DataAnalysis_Mysql

In this two csv datasets are taken from kaggle and are converted into sql tables using different commands 

click here to view: https://github.com/hritikap/Youtube_DataAnalysis_Mysql/blob/main/csv_to_sql_setup.ipynb


Then the tables are loaded into a new jupyter file and are manipulated using different sql queries.

click here to view: https://github.com/hritikap/Youtube_DataAnalysis_Mysql/blob/main/youtubedata_analysis.ipynb


## About the Dataset
### Content

#### videos_stats.csv
 - > Title: Video Title.
 - > Video ID: The Video Identifier.
 - > Published At: The date the video was published in YYYY-MM-DD.
 - > Keyword: The keyword associated with the video.
 - > Likes: The number of likes the video received. If this value is -1, the likes are not publicly visible.
 - > Comments: The number of comments the video has. If this value is -1, the video creator has disabled comments.
 - > Views: The number of views the video got.
 
 #### comments.csv:

 - > Video ID: The Video Identifier.
 - > Comment: The comment text.
 - > Likes: The number of likes the comment received.
 - > Sentiment: The sentiment of the comment. A value of 0 represents a negative sentiment, while values of 1 or 2 represent neutral and positive sentiments respectively.
