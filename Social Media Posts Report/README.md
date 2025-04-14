# Social Media Analytics Dashboard – Power BI Project 📊 

This Power BI dashboard merge social media data from multiple platforms to help marketers, analysts, and brands track performance, identify trends, and improve their content strategy based on real-time metrics.

---

## 🔍 Project Overview

With the growing importance of social media in marketing, it's essential to measure what works and what doesn’t. This dashboard provides a complete overview of social media performance across platforms like Twitter, TikTok, Instagram, YouTube.

By tracking key metrics such as impressions, engagement, follower growth, and content type performance, users can make smarter decisions or boost thier ad.

---

## 🎯 Goals of the Project
- Monitor key KPIs (engagement, reach, follower growth etc.)
- Compare post formats and posting times
- Highlight platform-specific strengths
- Provide real-time and actionable insights

---

## 📁 Dataset

- **File:** `social_media_posts.csv`  
- **Description:** Contains post-level data including platform, date, content type, reach, impressions, engagement, and more.
- **Data Source:** Simulated dataset for demonstration purposes
### 📊 Dataset Structure

| Column Name           | Data Type     | Description                                                  |
|------------------------|---------------|--------------------------------------------------------------|
| `post_id`              | `VARCHAR(10)` | Primary key uniquely identifying each post                   |
| `platform`             | `NVARCHAR(30)`| Social media platform where content was uploaded             |
| `post_date`            | `DATE`        | Date when content was uploaded (`YYYY-MM-DD`)                |
| `post_time`            | `VARCHAR(20)` | Time the content was uploaded                                |
| `content_type`         | `NVARCHAR(30)`| Format of content (e.g., video, story, text)                 |
| `post_length`          | `INT`         | Duration of the content (in seconds or minutes)              |
| `likes`                | `INT`         | Number of likes received                                     |
| `comments`             | `INT`         | Number of comments received                                  |
| `shares`               | `INT`         | Number of times the post was shared                          |
| `saves`                | `INT`         | Number of times the post was saved                           |
| `views`                | `INT`         | Total views on the content                                   |
| `reach`                | `INT`         | Number of unique users who saw the post                      |
| `impressions`          | `INT`         | Total number of times the post was displayed                 |
| `followers`            | `INT`         | Total followers at the time of posting                       |
| `clicks_on_links`      | `INT`         | Number of link clicks from the post                          |
| `engagement_rate`      | `DECIMAL(5,2)`| Engagement percentage calculated using (Likes + Comments + Shares) ÷ Total Followers × 100          |
| `audience_location`    | `NVARCHAR(30)`| Audience's geographic location                               |
| `audience_age_group`   | `NVARCHAR(10)`| Age group of the audience (e.g., 18-24, 25-34)               |

---

## 🔮 Future Improvements

- **Add Demographics:** Include age, gender, and location data for better audience analysis.
- **Competitor Analysis:** Benchmark metrics against industry standards.
- **Predictive Modeling:** Forecast future performance trends.
- **Sentiment Analysis:** Analyze comments to understand audience mood.
- **Cross-Correlation:** Link ad spend or post frequency with engagement for deeper insights.

---

## 🧰 Tools Used

- **Power BI:** For dashboard creation and visualizations
- **SQL:** For initial data formatting, cleaning and making ready for analysis
- **Python:** For creating dummy dataset

---

## 🧠 Skills Demonstrated

- Data Cleaning & Transformation
- DAX Calculations
- Interactive Dashboards
- Cross-platform Analysis
- Data Storytelling
- KPI Monitoring
- Visualization Best Practices

---

## 📈 Impact

This dashboard empowers social media teams to:

- Identify which content resonates best with the audience
- Adjust content strategy in real time
- Focus resources on the best-performing platforms
- Maximize engagement and follower growth
- Drive informed decision-making backed by data

---

## 📬 Contact

If you have any questions or want to collaborate, feel free to reach out!

📧 Email: nabintamanghai@gmail.com

🔗 [LinkedIn Profile](https://www.linkedin.com/in/nabintamanghai/)  

---

## 📌 License

This project is for learning and portfolio purposes only.
