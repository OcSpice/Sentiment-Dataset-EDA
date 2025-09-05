# Sentiment-Dataset-EDA


---

# 📊 Sentiment Dataset EDA  

### Level 1 Task 2 – Exploratory Data Analysis (EDA) on Sentiment Dataset  

---

## 📌 Overview  
This project is part of my **Data Analysis Internship at Codveda Technologies**.  
The objective is to perform **Exploratory Data Analysis (EDA)** on a social media sentiment dataset, uncovering patterns in user mood, engagement, and activity across platforms and geographies.  

---

## 🗂 Dataset  
**File used:** `/content/Level 1/3) Sentiment dataset.csv`  

**Key Columns:**  
- **Text** → Social media post content  
- **Sentiment** → Label (Positive, Negative, Neutral, or fine-grained emotions later grouped)  
- **Timestamp** → Date & time of post  
- **User** → Anonymized username  
- **Platform** → Social media platform (Twitter, Facebook, Instagram, etc.)  
- **Hashtags** → Extracted hashtags  
- **Likes** → Number of likes  
- **Retweets** → Number of retweets/shares  
- **Country** → Geographic source of the post  
- **Year, Month, Day, Hour** → Extracted datetime features



---

🎯 **Objectives**

1. Clean and preprocess dataset (remove duplicates, handle missing values, drop irrelevant columns).


2. Analyze sentiment distribution (Positive, Negative, Neutral).


3. Explore engagement metrics (Likes, Retweets) across sentiments.


4. Compare platform-wise sentiment trends.


5. Identify time-based posting patterns (hour of day).


6. Explore geographic sentiment variations.


7. Visualize correlations among numerical features.




---

⚙️ **Tools & Libraries**

Python (Google Colab)

pandas → data manipulation

matplotlib, seaborn → visualizations



---

## 🔎 Steps in Analysis  

1. **Data Cleaning**  
   - Removed duplicate rows.  
   - Dropped irrelevant index columns.  
   - Stripped whitespace and standardized categorical values (e.g., Sentiment, Country).  

2. **Sentiment Distribution**  
   - The raw dataset had 175 unique emotion labels (e.g., *Joy, Anger, Celestial Wonder*).  
   - These were consolidated into **3 main categories**: Positive, Negative, and Neutral.  
   - Produced histograms to examine class balance.  

3. **Temporal Analysis**  
   - Extracted Year, Month, Day, and Hour from `Timestamp`.  
   - Plotted activity trends by time to see when users post most frequently.  

4. **Engagement Analysis**  
   - Used boxplots to compare **Likes** and **Retweets** across different sentiment categories.  
   - Observed which types of posts (Positive, Negative, Neutral) received more engagement.  

5. **Platform Analysis**  
   - Compared engagement (Likes, Retweets) across platforms (Twitter, Instagram, Facebook).  
   - Identified where user engagement tends to be higher.  

6. **Geographic Analysis**  
   - Cleaned country names (e.g., `" USA  "` → `"USA"`).  
   - Grouped results into **Top 5 countries** + "Other".  
   - Plotted Likes & Retweets by country group for international perspective.  

---

## 📊 Visualizations  
- Histogram: Sentiment distribution  
- Boxplots: Likes & Retweets by sentiment  
- Boxplots: Likes & Retweets by platform  
- Boxplots: Likes & Retweets by country group  
- Line plots: Posting trends by time

---

## 📑 Key Insights
- Positive posts received more Likes on average compared to Negative posts.  
- Twitter had the highest posting volume, but Instagram posts showed higher engagement.  
- Posts from the USA dominated in volume, while India and the UK showed higher spread in Retweets.


---

## 📂 **Project Structure**

Level1_Task2_EDA_Sentiment.ipynb   # Google Colab Notebook (main analysis)
README.md                          # Project documentation


---


## 🔗 Links  

- **Open in Google Colab**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OPYSF-NSzobsQF_XSG2PB8mheaqwFiEj?usp=sharing)  

- **LinkedIn Post:** Coming Soon  

- **Video Walkthrough:** Coming Soon
