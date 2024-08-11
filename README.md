# MrBeast YouTube Channel Data Analysis

## Overview

This project analyzes data from MrBeast’s YouTube channel using the YouTube API. The analysis covers several aspects, including video performance, view distribution, engagement metrics, video duration, and video title trends. Additionally, the project includes an analysis of the upload schedule to visualize how frequently videos are posted on different days of the week.

## Objectives

### Best Performing Videos
- Identify the videos with the highest performance metrics, such as views, likes, and comments.

### Worst Performing Videos
- Analyze the videos with the lowest performance metrics to identify potential areas for improvement.

### View Distribution per Video
- Examine how views are distributed across different videos to understand viewership patterns.

### Views vs. Likes and Comments
- Compare views with likes and comments to assess engagement and interaction levels.

### Video Duration
- Analyze the duration of videos and its correlation with performance metrics.

### Wordcloud for Video Titles
- Generate a word cloud visualization to highlight common themes and keywords in video titles.

### Upload Schedule
- Analyze and visualize the frequency of video uploads on different days of the week.

## Data Sources

- **YouTube Data API**: Used to retrieve data on video metrics, including views, likes, comments, duration, and upload dates.

## Analysis

### Best Performing Videos
- **Output**: Bar chart displaying videos with the highest number of views.
  <div style="text-align: left;">
    <img src="best_performing_videos.png" alt="Best Performing Videos" style="width: 400px;"/>
  </div>

### Worst Performing Videos
- **Output**: Bar chart displaying videos with the lowest number of views.
  <div style="text-align: left;">
    <img src="worst_performing_videos.png" alt="Worst Performing Videos" style="width: 400px;"/>
  </div>

### View Distribution per Video
- **Output**: Distribution chart showing views per video.
  <div style="text-align: left;">
    <img src="view_distribution.png" alt="View Distribution per Video" style="width: 400px;"/>
  </div>

### Views vs. Likes and Comments
- **Output**: Scatter plots and correlation analysis comparing views with likes and comments.
  <div style="text-align: left;">
    <img src="views_vs_likes_and_comments.png" alt="Views vs. Likes and Comments" style="width: 400px;"/>
  </div>

### Video Duration
- **Output**: Analysis of video duration and its correlation with performance metrics.
  <div style="text-align: left;">
    <img src="video_duration.png" alt="Video Duration" style="width: 400px;"/>
  </div>

### Wordcloud for Video Titles
- **Output**: Word cloud visualization representing common keywords and themes in video titles.
  <div style="text-align: left;">
    <img src="wordcloud_for_video_titles.png" alt="Wordcloud for Video Titles" style="width: 400px;"/>
  </div>

### Upload Schedule
- **Output**: Graph showing the number of videos uploaded on each day of the week.
  <div style="text-align: left;">
    <img src="upload_schedule.png" alt="Upload Schedule" style="width: 400px;"/>
  </div>

## Getting Started

1. **Setup**: Ensure you have access to the YouTube Data API and necessary libraries (e.g., `google-api-python-client`, `pandas`, `matplotlib`, `wordcloud`).
2. **Data Acquisition**: Collect data from MrBeast’s YouTube channel using the YouTube Data API.
3. **Analysis**: Follow the objectives outlined to perform the analysis and generate insights.
