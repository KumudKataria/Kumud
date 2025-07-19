 Data Analysis of Netflix and YouTube

This repository contains my Summer Internship Project focused on **Exploratory Data Analysis (EDA)** of two major entertainment platforms: Netflix and YouTube. The goal of this project is
to extract meaningful insights, visualize key trends, and understand content performance using Python-based data analysis tools.



 NOTEBOOKS

1. Netflix Data Analysis  
   `MyNotebook (2).ipynb`  
   - Conducted data cleaning and EDA on the Netflix dataset.  
   - Analyzed content type distribution, release year trends, duration insights, and country-wise content availability.

2. YouTube Trending Data Analysis 
   `notebook 2 (2).ipynb`  
   - Performed detailed analysis on the trending YouTube videos dataset.  
   - Studied most viewed videos, top channels, likes vs. views correlation, and publishing time patterns.

  OBJECTIVE
1.	To analyze Netflix and YouTube datasets to extract meaningful trends and insights.
2.	To compare the content characteristics and popularity patterns between Netflix and YouTube.
3.	To visualize the data for better understanding and presentation.

 DATASET OVERVIEW
Netflix Dataset
1.	Consists of titles available on Netflix.
2.	Includes columns like type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, and description.
3.	Total rows: Approx. 8,000+ entries (based on common Netflix datasets).
YouTube Dataset
1.	Contains trending video data for the US region.
2.	Includes fields like video_id, title, channel_title, category_id, publish_time, tags, views, likes, dislikes, comment_count, etc.
3.	Total rows: 40,949 and 16 columns (as observed).

 DATA CLEANING (Phase 2)
Netflix
1.	Removed rows with missing values.
2.	Standardized column names.
3.	Converted date_added to datetime and extracted year_added.
4.	Removed duplicates and formatted text columns.
YouTube
1.	Replaced '[none]' with empty strings in the tags column.
2.	Converted title and tags to lowercase.
3.	Converted publish_time to datetime format.
4.	Extracted publish year and month.

 EDA & VISUALIZATIONS (Phase 3-4)
Netflix
1.	Content Type Count: Count of Movies vs TV Shows.
2.	Year-wise Additions: Number of shows/movies added per year.
3.	Rating Distribution: Popular content ratings (TV-MA, PG-13, etc.).
4.	Top Countries: Countries with highest content production.
5.	Genre Count: Most common genres listed.
YouTube
1.	Top Channels: Channels with most trending videos.
2.	Most Viewed Videos: Top 10 videos by view count.
3.	Likes vs Views: Scatter plot to show correlation.
4.	Publish Month Trend: Distribution of trending videos across months.

 INSIGHTS (Phase 5)
Netflix
1.	Dominance of Movies: Movies constitute the majority of content.
2.	Content Surge in 2019-2020: Notable rise in content addition during these years.
3.	Major Genres: Drama, International, and Action are the leading categories.
4.	Rating Trends: TV-MA is the most frequent rating, indicating mature content.
YouTube
1.	Few Channels Dominate: A small number of channels consistently appear in trending lists.
2.	Engagement Peaks for Top Videos: High view count videos also exhibit high likes.
3.	Trending Peaks Around Festive Months: Most videos trend around October–December.
4.	Short Titles and Tags are Common: Indicates a preference for concise metadata.


 CONCLUSION
The analysis reveals platform-specific behaviors: Netflix trends toward mature and drama-heavy content, while YouTube thrives on channel branding and viewer engagement. Data visualization helped uncover valuable insights that can be used for content strategy, marketing, and user targeting.

 TOOLS AND TECHNOLOGIES USED
1.	Netflix Data Source: [Netflix Kaggle Dataset]
2.	YouTube Data Source: [USvideos.csv Kaggle Dataset]•	Python Libraries: Pandas, NumPy, Seaborn, Matplotlib
3.	Platform: Jupyter Notebook

AUTHOR
Kumud Kataria




