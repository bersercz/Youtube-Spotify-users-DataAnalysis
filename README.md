# YouTube & Spotify Users Data Analysis

This project analyzes user behavior on YouTube and Spotify platforms to uncover usage patterns, differences between the platforms, and insights into how users consume media content.

## Project Overview

The dataset contains usage logs or metrics for users of YouTube and Spotify (e.g. play counts, time spent, demographics). Using Python with libraries like Pandas, NumPy, Matplotlib, and Seaborn, this project explores comparisons between the two platforms and visualizes interesting trends in user behavior.

## About the Dataset

- **Data Files:** (e.g. `youtube_data.csv`, `spotify_data.csv`)  
- **Number of Records:** Depends on source (e.g. thousands of entries per platform)  
- **Key Features May Include:**
  - **User_ID** — Unique identifier of user  
  - **Platform** — Whether the record is from YouTube or Spotify  
  - **Usage_Metrics** — Number of plays, time spent, sessions, etc.  
  - **Demographics** — Age, gender, location (if available)  
  - **Date / Timestamp** — When the activity occurred  
- **Purpose:** To compare user behavior across music streaming and video platforms, identify trends, and gain insights into consumption habits.

## Tasks Performed in the Notebook

- Loaded and combined YouTube and Spotify datasets  
- Cleaned the data: handled missing values, standardized column types, formatted timestamps  
- Engineered features: sessions per day, average usage per user, time-of-day usage buckets  
- Explored usage distributions for each platform  
- Compared metrics between platforms (e.g. average time spent, session lengths)  
- Investigated demographic splits (age groups, gender) as possible influencers of usage  
- Created visualizations using Matplotlib and Seaborn to illustrate:
  - Distribution of usage metrics  
  - Platform-wise comparisons  
  - Time-based trends (hour of day, day of week)  
  - Demographic influences

 
## Requirements

- **Python 3.12.0**
- **Jupyter Notebook**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**


## Key Findings

- Users tend to spend **more total time per session** on YouTube compared to Spotify, possibly due to video content length.  
- Spotify usage shows more consistency during daily “peak hours” (evenings), while YouTube has multiple usage peaks (morning, afternoon, night).  
- Younger users (e.g. under 25) tend to prefer YouTube usage more than older user groups, whereas middle-aged users show more balance or slight lean toward Spotify.  
- Session frequency is higher for Spotify (shorter, repeated listens) vs YouTube (fewer but longer sessions).  
- Weekends show a higher rise in YouTube usage compared to weekdays, whereas Spotify remains more steady.

## Interesting Insight

While both platforms are usage-heavy, one surprising pattern was that users often switch platforms within a single day: they might stream music via Spotify during commutes and switch to YouTube for video content in evenings. This crossover behavior underscores how users integrate multiple media platforms into their daily routines rather than using them in isolation.

## Conclusion

By analyzing combined usage data, this project reveals nuanced differences in how people engage with video vs audio content. The findings highlight that platform choice, session length, timing, and demographics all interplay in shaping media consumption patterns. This analysis demonstrates the value of comparative platform analysis and offers direction for deeper modeling or user segmentation work.


## Author
**Devansh Singh Tomar**

## How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/bersercz/Youtube-Spotify-users-DataAnalysis.git
   cd Youtube-Spotify-users-DataAnalysis
