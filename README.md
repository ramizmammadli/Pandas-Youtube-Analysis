# Pandas-US-Youtube-Analysis

- This is a demo project of data analysis of a daily record of the top trending YouTube videos using Pandas module in Python

hr

### About dataset
- YouTube (the world-famous video sharing website) maintains a list of the top trending videos on the platform. According to Variety magazine, “To determine the year’s top-trending videos, YouTube uses a combination of factors including measuring users interactions (number of views, shares, comments and likes). Note that they’re not the most-viewed videos overall for the calendar year”. Top performers on the YouTube trending list are music videos (such as the famously virile “Gangam Style”), celebrity andor reality TV performances, and the random dude-with-a-camera viral videos that YouTube is well-known for.

- This dataset is a daily record of the top trending YouTube videos.
- For each video, the dataset basically includes (column names in paranthesis)
  - ID (video_id),
  - Trending date (trending_date),
  - Title (title),
  - Title of the channel which the video is shared. (channel_title),
  - ID of the region. Each ID represents a region (43 regions in total). (category_id),
  - Release date (publish_time),
  - Tags of each video (tags),
  - The number of views for each video (views),
  - The number of likes for each video (likes),
  - The number of dislikes for each video (dislikes),
  - The number of comments under each video (comment_count),
  - Thumbnail link (thumbnail_link),
  - Whether the comments are disabled (True) or not (False). (comments_disabled),
  - Whether the ratings are disabled (True) or not (False). (ratings_disabled),
  - Whether there is an error in the video or it is removed (True) or not (False) (video_error_or_removed),
  - Descriptions of each video (description).
  
 - Additionally, several columns are added to the dataset in the code. The columns are
    - The length of title (title_length),
    - The number of tags in each video (tag_count),
    - The ratio of likes to overall reactions and sorting it in descending order. This one is developed by 2 methods (likes_dislikes_ratio_method1 and 2)
 
hr

### About code
- The code basically does the premature analysis on the given dataset, such as
  - Dropping several not quite useful columns,
  - Finding the number of videos in the dataset,
  - Average number of all likes and dislikes,
  - Finding the title of most and least viewed video,
  - Grouping dataset according to categories and average of number of comments for each category,
  - Adding new columns which are shown above in dataset explanations.
  - and so on.
  
hr

### Source
 - Dataset is taken from Kaggle.com
