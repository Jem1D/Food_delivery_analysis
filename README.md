# Food Delivery Sentiment Analysis with Apache Spark

Analyze and compare customer reviews for popular food delivery platforms—**DoorDash**, **Uber Eats**, and **Grubhub**—using **Apache Spark**, **Databricks**, and **Big Data tools**. This project explores large-scale review data (1.6M+ rows) sourced from the Google Play Store to uncover sentiment trends, app performance, and customer satisfaction insights.

---

## 📁 Project Overview

- **Dataset**: 1.69 million Google Play Store reviews (Published: March 2, 2025)  
- **Platforms Analyzed**: DoorDash, Uber Eats, Grubhub  
- **Objective**: Extract and compare user sentiment, star ratings, and app-specific trends using distributed computing.  
- **Tech Stack**: Apache Spark, Databricks, AWS S3, SparkSQL, Matplotlib, Seaborn, VADER, AFINN

---

## 🚀 Why This Project?

This project was inspired by a real-world question:  
> “Which food delivery app offers the best customer experience?”

With the scale of the data too large for local machines, Spark and Databricks offered a robust solution to process, query, and visualize user feedback at scale.

---

## 🧠 Key Insights

| Metric                    | DoorDash     | Uber Eats    | Grubhub       |
|---------------------------|--------------|--------------|---------------|
| Avg. Star Rating          | ⭐ 4.0        | ⭐ 3.6        | ⭐ 3.8         |
| Positive Sentiment Share | High         | High         | Moderate      |
| Negative Themes          | Refund issues, delays | Incorrect orders | App glitches |

- **Uber Eats** had the **highest average rating**.
- **DoorDash** received the most reviews but had a higher percentage of **negative feedback**.
- **Grubhub** showed balanced sentiment, though rated slightly lower on **ease of use**.

---

## 📊 Visualizations

- ✅ Sentiment Distribution by App (Stacked Bar Chart)  
- ✅ Average Star Rating Comparison  
- ✅ Negative Review Percentage  
- ✅ Review Length vs. Sentiment Correlation (Scatter + Heatmap)  
- ✅ Data Pipeline Architecture (with AWS, Databricks, Spark)

---

## 🔧 Technologies Used

- **Apache Spark** – Distributed processing of large-scale datasets  
- **Databricks** – Cloud-based runtime for Spark  
- **AWS S3** – Remote data storage  
- **SparkSQL** – For querying structured datasets  
- **Matplotlib / Seaborn** – Data visualizations  
- **VADER & AFINN** – Lexicon-based sentiment scoring  
- **Python** – Scripting and analysis

---

## 📂 Project Structure

food-delivery-spark/ │ ├── notebooks/ │ └── food-delivery.ipynb # Spark-based analysis and visualizations ├── data/ │ └── food-delivery.csv # Source dataset (not included due to size) ├── pipeline_diagram.png # Data processing pipeline ├── sentiment_distribution.png # Chart: Sentiment per App ├── average_star_rating.png # Chart: Avg Star Rating per App └──



---

## 📌 Future Work

- Integrate app store (iOS) reviews  
- Build a dashboard using Plotly/Dash or Power BI  
- Train ML models to **predict sentiment** based on review text  
- Apply **topic modeling (LDA)** for keyword extraction

---

## 📜 Citation

> Dataset DOI: [10.17632/m5jk7wzyg7.1](https://data.mendeley.com/datasets/m5jk7wzyg7/1)  
> Contributors: Md Shamim Hossain, Le Li, Peng Sun, Kian Aun Law, Samrat Ray  
> *Dataset collected via Python web scraping from the Google Play Store*

---

## 🤝 Contributions & Feedback Welcome

Feel free to fork the repo, open issues, or contribute improvements. Let’s build better data products together!
