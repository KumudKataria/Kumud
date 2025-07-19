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
•	To analyze Netflix and YouTube datasets to extract meaningful trends and insights.
•	To compare the content characteristics and popularity patterns between Netflix and YouTube.
•	To visualize the data for better understanding and presentation.

 DATASET OVERVIEW
Netflix Dataset
•	Consists of titles available on Netflix.
•	Includes columns like type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, and description.
•	Total rows: Approx. 8,000+ entries (based on common Netflix datasets).
YouTube Dataset
•	Contains trending video data for the US region.
•	Includes fields like video_id, title, channel_title, category_id, publish_time, tags, views, likes, dislikes, comment_count, etc.
•	Total rows: 40,949 and 16 columns (as observed).

4. DATA CLEANING (Phase 2)
Netflix
•	Removed rows with missing values.
•	Standardized column names.
•	Converted date_added to datetime and extracted year_added.
•	Removed duplicates and formatted text columns.
YouTube
•	Replaced '[none]' with empty strings in the tags column.
•	Converted title and tags to lowercase.
•	Converted publish_time to datetime format.
•	Extracted publish year and month.

5. EDA & VISUALIZATIONS (Phase 3-4)
Netflix
•	Content Type Count: Count of Movies vs TV Shows.
•	Year-wise Additions: Number of shows/movies added per year.
•	Rating Distribution: Popular content ratings (TV-MA, PG-13, etc.).
•	Top Countries: Countries with highest content production.
•	Genre Count: Most common genres listed.
YouTube
•	Top Channels: Channels with most trending videos.
•	Most Viewed Videos: Top 10 videos by view count.
•	Likes vs Views: Scatter plot to show correlation.
•	Publish Month Trend: Distribution of trending videos across months.

6. INSIGHTS (Phase 5)
Netflix
•	Dominance of Movies: Movies constitute the majority of content.
•	Content Surge in 2019-2020: Notable rise in content addition during these years.
•	Major Genres: Drama, International, and Action are the leading categories.
•	Rating Trends: TV-MA is the most frequent rating, indicating mature content.
YouTube
•	Few Channels Dominate: A small number of channels consistently appear in trending lists.
•	Engagement Peaks for Top Videos: High view count videos also exhibit high likes.
•	Trending Peaks Around Festive Months: Most videos trend around October–December.
•	Short Titles and Tags are Common: Indicates a preference for concise metadata.


7. CONCLUSION
The analysis reveals platform-specific behaviors: Netflix trends toward mature and drama-heavy content, while YouTube thrives on channel branding and viewer engagement. Data visualization helped uncover valuable insights that can be used for content strategy, marketing, and user targeting.

8. TOOLS AND TECHNOLOGIES USED
•	Netflix Data Source: [Netflix Kaggle Dataset]
•	YouTube Data Source: [USvideos.csv Kaggle Dataset]
•	Python Libraries: Pandas, NumPy, Seaborn, Matplotlib
•	Platform: Jupyter Notebook

AUTHOR
Kumud Kataria




