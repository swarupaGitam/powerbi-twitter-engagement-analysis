# Twitter Engagement Analytics Dashboard

## Project Overview

This project presents an interactive Power BI dashboard designed to analyze Twitter engagement metrics and user interaction patterns. The dashboard evaluates tweet performance using various engagement indicators such as likes, retweets, media views, media engagements, and engagement rate.

The objective of the project is to identify high-performing tweets, understand engagement trends, analyze audience interaction behavior, and derive actionable insights through data visualization.

---

## Tools Used

* Power BI Desktop
* Microsoft Excel
* DAX (Data Analysis Expressions)

---

## Dataset Information

The dataset contains tweet-level information including:

* Tweet Text
* Tweet Date
* Tweet Category
* Likes
* Retweets
* Replies
* Impressions
* Media Views
* Media Engagements
* Engagement Rate
* App Opens
* Tweet Hour
* Tweet ID

---

## Dashboard Tasks Completed

### Task 1: Tweet Interaction Breakdown by Category

Analyzed tweet interactions across categories using multiple filtering conditions.

**Note:** The task required tweets with a word count greater than 40. During validation, the dataset was found to have a maximum tweet word count of 36. Therefore, no records satisfied the condition and the visual correctly returned no data.

---

### Task 2: Impact of App Opens on Tweet Engagement Rate

Compared average engagement rates based on App Opens categories to understand the influence of app interactions on tweet performance.

---

### Task 3: Media Views vs Media Engagements Analysis

Created a combined visualization to compare media views and media engagements across different days of the week.

---

### Task 4: Replies, Retweets and Likes Comparison

Compared overall user engagement metrics using aggregated likes, retweets, and replies for the selected period.

---

### Task 5: Monthly Engagement Rate Trend

Analyzed monthly engagement rate trends by separating tweets into:

* With Media
* Without Media

This visualization highlights how media content influences engagement performance over time.

---

### Task 6: Top 10 Tweets by Engagement

Identified the top-performing tweets based on total engagement (Likes + Retweets) while applying the required filtering conditions:

* Weekend tweets excluded
* Even tweet impressions
* Odd tweet dates
* Word count less than 30
* Visibility restricted to the specified IST time window

---

## Key Insights

* Tweets containing media generally achieved higher engagement rates than tweets without media.
* Likes contributed significantly more to total engagement compared to replies and retweets.
* Media engagement patterns varied across weekdays.
* A small number of tweets generated disproportionately high engagement.
* Filtering and conditional analysis helped isolate high-performing content segments.

---

## Conclusion

The dashboard demonstrates the use of Power BI for social media analytics by combining data transformation, DAX calculations, conditional filtering, and interactive visualizations. It provides a structured approach to evaluating tweet performance and understanding engagement behavior through data-driven insights.
