# 📊 Social Media Viral Content & Engagement Analysis

## 📌 Project Overview

Social media platforms generate massive amounts of content every day, but not all posts perform equally well. Some posts go viral, attract high engagement, and reach wider audiences, while others barely get noticed. The goal of this project is to **understand what drives engagement on social media** by analyzing content performance across platforms, topics, regions, and posting times.

This project focuses on answering **practical, real-world questions** that content creators, marketers, and businesses actually care about:

* Which social media platforms generate the most engagement?
* What type of content and topics receive the most likes?
* When is the best time to post to maximize views and likes?

Rather than building complex machine learning models, this analysis emphasizes **clear insights, patterns, and data-driven recommendations**.

---

## 🎯 Research Questions

The analysis is guided by the following research questions:

1. **Platform Popularity & Engagement**

   * Which social media platforms are the most popular based on views and likes?
   * How does engagement differ across platforms?

2. **Content, Topic & Region Performance**

   * Which content topics receive the highest number of likes?
   * How does engagement vary by region?
   * What combinations of topic and region perform best?

3. **Best Time to Post**

   * Which time of day receives the most views and likes?
   * When should users post content to maximize engagement?

These questions aim to help users make **data-backed decisions** about where, what, and when to post.

---

## 🧾 Dataset Description

The dataset contains social media post-level data with **12 key features**, covering metadata, timing information, sentiment, and engagement metrics.

### 🆔 Post Metadata

* **post_id** – Unique identifier for each post
* **platform** – Social media platform name (e.g., Instagram, YouTube, TikTok)
* **content_type** – Type of content (video, image, carousel, text)
* **topic** – Content category (Entertainment, Tech, Sports, etc.)
* **language** – Language of the post (EN, UR, HI, ES, FR)
* **region** – Geographic region where the post was published

### ⏰ Time & Trend Signals

* **post_datetime** – Date and time when the post was uploaded
  Used to analyze posting patterns, peak engagement hours, and time-based trends.

### #️⃣ Hashtags & Sentiment

* **hashtags** – List of trending hashtags used in the post
* **sentiment_score** – Emotional tone of the post (-1 = negative, +1 = positive)

### 📈 Engagement Metrics

* **views** – Total number of views
* **likes** – Number of likes received
* **comments** – Number of comments
* **shares** – Number of times the post was shared

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas & NumPy** – Data cleaning and manipulation
* **Matplotlib & Seaborn** – Data visualization
* **Jupyter Notebook** – Exploratory data analysis

---

## 🔍 Analysis Approach

1. **Data Cleaning & Preprocessing**

   * Handling missing values and inconsistent entries
   * Converting date-time fields into usable formats (hour, day)

2. **Exploratory Data Analysis (EDA)**

   * Platform-wise engagement comparison
   * Topic and region-based engagement trends
   * Time-of-day analysis for views and likes

3. **Visualization & Insights**

   * Bar charts and trend plots to highlight key findings
   * Clear interpretation of results rather than just numbers

---

## 📈 Key Outcomes (Expected)

* Identification of the **most engaging social media platforms**
* Insights into **which topics perform best in different regions**
* Clear recommendations on **optimal posting times** to maximize reach and engagement

---

## 🚀 Why This Project Matters

This project reflects a **realistic data analyst workflow**, starting from problem formulation to insight generation. It demonstrates the ability to:

* Translate raw data into meaningful business questions
* Analyze engagement patterns across multiple dimensions
* Communicate insights clearly and effectively

The findings from this analysis can help:

* Content creators plan their posting strategy
* Social media managers improve engagement rates
* Businesses optimize their content marketing efforts

---

## 📌 Future Improvements

* Deeper hashtag-level analysis
* Sentiment vs engagement correlation study
* Predictive modeling for engagement estimation

---

## ✍️ Author

**Mayuri Mamdi**
MSc Data Science | Aspiring Data Analyst / Data Scientist

---

Feel free to explore the notebook and visualizations to gain deeper insights into social media engagement patterns.

