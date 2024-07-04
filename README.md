# Youtube_Songs_Analysis
## Problem Statement:
This internship project aims to conduct a comprehensive analysis of YouTube songs data using Power BI.
The dataset contains key attributes such as video ID, channel title, title, description, tags, published date,
view count, like count, favorite count, comment count, video duration, video definition, and caption
details. The goal is to utilize Power BI to create insightful visualizations and reports that provide a deeper
understanding of YouTube songs' performance, popularity, and user engagement. The analysis aims to
uncover trends, preferences, and patterns in the data to aid content creators and stakeholders in
optimizing their YouTube song content.
## Dataset Description:
1. video_id: Unique identifier for each YouTube video.
2. channelTitle: Title of the YouTube channel publishing the song.
3. title: Title of the YouTube song video.
4. description: Description provided for the YouTube song video.
5. tags: Tags associated with the YouTube song video.
6. publishedAt: Date and time when the YouTube song video was published.
7. viewCount: Number of views received by the YouTube song video.
8. likeCount: Number of likes received by the YouTube song video.
9. favoriteCount: Number of times the YouTube song video has been marked as a favorite.
10. commentCount: Number of comments posted on the YouTube song video.
11. duration: Duration of the YouTube song video.
12. definition: Video definition or quality (e.g., HD, SD).
13. caption: Availability of captions for the YouTube song video.
## Project Objectives:
## 1. Data Cleaning and Preparation:
 - Clean and preprocess the dataset, handling missing values or outliers.
 - Convert relevant columns to appropriate data types.
## 2. Exploratory Data Analysis (EDA):
 - Explore patterns and distributions in view counts, like counts, and comments.
 - Identify trends in the popularity and engagement of YouTube song videos.
## 3. Content and Channel Analysis:
 - Analyze the distribution of videos across different channels
- Identify popular tags and their correlation with view counts.
## 4. Temporal Trends:
 - Explore how YouTube song video metrics vary over time.
 - Identify peak publishing times and their impact on engagement.
## 5. User Engagement Insights:
 - Investigate relationships between likes, comments, and views.
 - Identify factors influencing user engagement with YouTube song videos.
 - # YouTube Songs Data Analysis Project

## Data Cleaning and Preparation
1. Load Data:
   - Connect to `songs.xlsx`.
   - Use `Sheet1`.

2. Data Cleaning:
   - Handle missing values.
   - Convert data types:
     - `published_date` to Date.
     - `view_count`, `like_count`, `comment_count` to Integer.

3. Field Calculations:
   - Create calculated fields as needed.

## Exploratory Data Analysis (EDA)
1. View Counts Analysis:
   - Drag `view_count` to Rows, `video_ID` to Columns.
   - Create bar charts.

2. Like Counts and Comments Analysis:
   - Drag `like_count` and `comment_count` to Rows.
   - Create histograms and box plots.

3. Trend Identification:
   - Drag `published_date` to Columns.
   - Drag `view_count`, `like_count`, and `comment_count` to Rows.
   - Create line charts.

## Content and Channel Analysis
1. Video Distribution Across Channels:
   - Drag `channel_title` to Columns, `video_ID` to Rows.
   - Create bar charts.

2. Popular Tags Analysis:
   - Drag `tags` to Columns, `view_count` to Rows.
   - Create a word cloud and scatter plot.

## Temporal Trends
1. Metrics Over Time:
   - Drag `published_date` to Columns.
   - Drag `view_count`, `like_count`, and `comment_count` to Rows.
   - Create line charts.

2. Peak Publishing Times:
   - Extract hour and day from `published_date`.
   - Create a heatmap.

## User Engagement Insights
1. Relationships Between Metrics:
   - Create a scatter plot with `like_count` and `view_count`.
   - Add `comment_count` as detail.

2. Factors Influencing Engagement:
   - Use `caption_details` and `video_definition` as filters.
   - Create bar or line charts.

## Deliverables
1. Interactive Dashboards:
   - Combine visualizations.
   - Use filters and actions.

2. Reports:
   - Summarize findings.
   - Highlight key insights.

3. Recommendations:
   - Provide actionable insights for content creators and stakeholders.

