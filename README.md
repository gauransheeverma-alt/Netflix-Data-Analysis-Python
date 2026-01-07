# 🎬 Netflix Exploratory Data Analysis (EDA)

## 📊 Project Overview  
This project performs an in-depth **Exploratory Data Analysis (EDA)** on the **Netflix dataset**, aiming to uncover patterns, trends, and insights about the content available on the platform.  
It explores relationships between variables such as content type, ratings, release year, and country, complemented by visual charts and text-based insights.

---

## 🎯 Objectives  
The primary objectives of this analysis are:  
- To explore the distribution of **Movies vs TV Shows**.  
- To analyze **ratings**, **genres**, and **release trends** over time.  
- To study **country-level contributions** to Netflix’s content library.  
- To compare **release years** with **addition years** to understand licensing delays.  
- To visualize the most common **keywords and phrases** in content descriptions.  

---

## 🧩 Dataset Details  
The dataset provides detailed metadata for each Netflix title, including:  
- `show_id`, `title`, `director`, `cast`  
- `country`, `date_added`, `release_year`  
- `rating`, `duration`, `listed_in`, `description`

This enables analysis of Netflix’s content catalog from multiple perspectives — geographic, temporal, and thematic.

---

## 🛠️ Libraries Used  

| Library | Purpose |
|----------|----------|
| **pandas** | Data cleaning, manipulation, and preprocessing |
| **numpy** | Numerical computations and array operations |
| **matplotlib.pyplot** | Foundational plotting library for graphs |
| **seaborn** | Enhanced visualizations with statistical insights |
| **wordcloud** | Generating word clouds from content descriptions |

---

## 📈 Visualizations and Analysis Performed  

### 🧹 Data Cleaning and Preprocessing  
- Handled missing and duplicate values.  
- Standardized date formats.  
- Extracted new temporal features such as `year_added` and `month_added`.  

### 🔍 Exploratory Analysis  
- Distribution of **Movies vs TV Shows**.  
- Top **content ratings** (TV-MA, TV-14, PG, etc.).  
- Most frequent **genres** and **countries**.  
- Comparison between **release year** and **date added**.  
- Temporal trends in Netflix content production and additions.  

### 🧠 Text Analysis  
- Generated a **WordCloud** from descriptions to highlight popular themes.  
- Identified common keywords and recurring phrases in summaries.  

### 📊 Visual Representations  
- **Bar charts** → Genre popularity, country-wise content, rating distribution.  
- **Pie chart** → Proportion of Movies vs TV Shows.  
- **Line plots** → Yearly content addition trends.  
- **WordCloud** → Frequent words in content descriptions.  
- (Optional) **Geographic visualizations** → Mapping top content-producing countries.  

---

## 🧠 Key Insights  
- Netflix’s content library expanded rapidly after **2015**, especially in **TV Shows**.  
- **United States**, **India**, and **United Kingdom** dominate in content production.  
- **TV-MA** is the most prevalent maturity rating, indicating adult-oriented preferences.  
- A visible delay exists between **release year** and **addition year**, reflecting licensing and acquisition patterns.  
- Frequent description words include *love*, *family*, *murder*, *drama*, and *life*, suggesting dominant genres.  

---

## 🗺️ Geographic Trends  
If available, the dataset allows for visualization of **country-level content contribution**.  
Future extensions can include interactive maps showing regional content diversity.

---

## 🧾 Conclusion  
This project delivers a comprehensive analysis of Netflix’s catalog, showcasing its evolution from a movie-centric to a TV show–rich platform.  
Through visual exploration and text analysis, it provides valuable insights into how Netflix curates and expands its content globally.

---

## 📂 Files Included  
- `Netflix_EDA.ipynb` → Main notebook with data analysis and visualization.  
- `README.md` → This documentation file.  
- *(Optional)* `netflix_titles.csv` → Dataset used for the analysis.

---

## 💡 Author  
**Gauranshee Verma**  
BCA Student | Data Enthusiast | Python Learner  

---
