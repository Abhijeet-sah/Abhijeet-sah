📊 Social Media Sentiment Analysis

Sentiment Analysis of Twitter, Facebook, and Instagram data using Python, Pandas, Matplotlib, and Seaborn in Google Colab.

The goal of this project is to analyze user sentiments across multiple platforms to help organizations better understand public opinion and engagement.

🖼️ Workflow Diagram
flowchart TD
    A[Dataset Import (Kaggle)] --> B[Data Cleaning & Preprocessing]
    B --> C[Exploratory Data Analysis (EDA)]
    C --> D[Platform-wise Analysis]
    D --> E[Visualization & Insights]

    A1[Twitter Data] --> A
    A2[Facebook Data] --> A
    A3[Instagram Data] --> A

    B1[Drop Nulls, Rename Columns] --> B
    B2[Datetime Conversion & Feature Extraction] --> B

    C1[Sentiment Distribution] --> C
    C2[Top Hashtags, Users, Countries] --> C

    D1[Facebook: Likes & Retweets Trend] --> D
    D2[Twitter: Hashtags & Engagement] --> D
    D3[Instagram: Popular Users & Hashtags] --> D

🚀 Features

✅ Dataset integration from Kaggle

✅ Data Cleaning (drop unused columns, rename, strip whitespaces)

✅ Exploratory Data Analysis (EDA)

✅ Visualization:

Sentiment Distribution (Positive, Negative, Neutral)

Platform Comparison (Twitter, Facebook, Instagram)

Country-wise engagement

Hashtag popularity

Top users by likes

Yearly trends of Likes & Retweets

✅ Platform-wise segmentation (Facebook, Twitter, Instagram)

📂 Project Structure
social-media-sentiment-analysis/
│── data/
│   └── sentimentdataset.csv      # Kaggle dataset
│── notebooks/
│   └── Social Media Sentiments Analysis - Colab.ipynb
│── results/
│   ├── sentiment_distribution.png
│   ├── platform_percentages.png
│   ├── top_hashtags.png
│   ├── country_likes.png
│   ├── facebook_trends.png
│   ├── twitter_trends.png
│   └── instagram_trends.png
│── README.md

🔑 Setup (Google Colab)

Upload the dataset from Kaggle
.

Mount Google Drive (optional):

from google.colab import drive
drive.mount('/content/drive')


Install dependencies:

!pip install pandas matplotlib seaborn


Run the notebook Social Media Sentiments Analysis - Colab.ipynb.

📊 Key Results
1. Sentiment Distribution

Shows the balance of Positive, Negative, Neutral posts.


2. Platform-wise Contribution

Instagram: 258 posts

Twitter: 243 posts

Facebook: 231 posts


3. Top Hashtags

Popular hashtags driving engagement across platforms.


4. Country Insights

Top 10 countries with most activity.


5. Facebook Trends

Likes and retweets trend across years.


6. Twitter Trends

Engagement analysis on hashtags and likes.


7. Instagram Trends

Most popular hashtags and users.


📌 Future Enhancements

Real-time streaming data via APIs (Twitter API, Facebook Graph API, Instagram Scraper).

Advanced NLP models (BERT, RoBERTa) for deeper sentiment accuracy.

Deployment as an interactive dashboard with Streamlit/Dash.

👨‍💻 Author

Abhijeet Sah
Internship Project – Brainwave Matrix Solution
