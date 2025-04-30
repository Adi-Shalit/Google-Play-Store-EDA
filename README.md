# 📊📈🔍 Google Play Store EDA

The **Google Play Store** is one of the largest platforms for Android applications, offering millions of apps across categories like **Games**, **Productivity**, **Health**, and more. It serves as the primary distribution channel for Android developers to **publish**, **promote**, and **monetize** their applications to a global audience.

This dataset provides detailed information about a wide range of apps available on the store. Each row represents a unique app and includes attributes such as:

- App name  
- Category  
- Rating  
- Number of reviews  
- Size, installs, type, price  
- Last updated version, Android compatibility  
...and more.

The data was originally scraped from the Google Play Store. Without access to this platform and the efforts involved in compiling it, such analysis would not be possible.

---

## 🔍 Project Objective

The purpose of this project is to perform **Exploratory Data Analysis (EDA)** on the dataset in order to uncover patterns and insights about app performance and trends.

This analysis can help:

- Identify what makes successful apps stand out  
- Support app development and feature prioritization  
- Inform marketing strategies and user engagement approaches  
- Explore relationships between variables such as rating, installs, and price

---

## 📁 Files Included

- `EDA-GooglePlayStore.ipynb` – Jupyter Notebook containing all the EDA steps, visualizations, and insights  
- `googleplaystore.csv` – The raw dataset used for the analysis

---

## 🛠 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

---

## 🧠 Insights Summary

### 1. Category Insights
- **FAMILY** is the largest category (18.76%), highlighting strong demand for family-friendly apps.
- **GAMES** rank second (10.83%) and show consistently high popularity, downloads, and user engagement.
- **TOOLS** and **BUSINESS** categories are also significant, emphasizing utility and productivity-focused apps.

### 2. Game Apps
- Games have the **highest storage requirements**, due to rich graphics and complex features.
- They lead in **median installs**, reflecting high user interest.
- They receive **many reviews** and maintain **stable, high ratings (~4.3)**.
- However, **competition is intense** — not all games succeed despite the demand.
- Games typically support a wide range of Android versions, indicating broad compatibility goals.

### 3. App Types
- **92.7% of apps are free**, relying heavily on in-app purchases and ads.
- **Paid apps are rare** (7.3%) and tend to target users with newer Android devices.
- Pricing is generally consistent among paid apps, with a narrow range.

### 4. Content Rating
- **80.93% of apps are rated "Everyone"**, suggesting a market focus on accessibility and inclusivity.
- Family and Game apps strongly contribute to this trend.

### 5. Genres
- **Tools, Entertainment, and Education** are leading genres.
- Some apps belong to **niche or combined genres** (e.g., Lifestyle;Pretend Play), offering potential for differentiation.

### 6. Key Correlations & Trends
- Strong correlation between **installs and reviews**: more downloads = more reviews.
- **Price** does not correlate with installs, reviews, or app size — most apps are free.
- **Apps are getting larger** over time and increasingly target newer Android versions.
- Still, many apps maintain support for **older Android versions**, balancing innovation with accessibility.

### 7. General Observations
- Most apps in the dataset were **last updated between 2017–2018**.
- The **average rating is consistent (~4.3)** across categories.
- The trend toward **larger, content-rich apps** continues as device capabilities evolve.

---

## 🌟 Acknowledgments

The dataset was sourced through web scraping from the Google Play Store and made publicly available for educational purposes.
The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps).
Special thanks to the original data contributors who compiled and shared the Google Play Store data, enabling this analysis.
