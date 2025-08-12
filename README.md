ChatGPT Review Analysis

## 📌 Overview
This project analyzes **ChatGPT user reviews** to uncover insights about user sentiment, rating trends, and common keywords in feedback. Using Python's data analysis and visualization libraries, it provides actionable insights into how users perceive the service over time.

---

## ✨ Features
- **Data Cleaning & Preprocessing**
  - Handles missing values
  - Converts review dates to datetime format
  - Ensures numerical ratings
- **Exploratory Data Analysis (EDA)**
  - Ratings distribution chart
  - Average monthly rating trends
  - Monthly review volumes
- **Text Analysis**
  - Lowercasing and punctuation removal
  - Stopword removal
  - Word cloud generation for common review terms

---

## 🛠 Tech Stack
- **Python**
- **Pandas** – Data manipulation  
- **Matplotlib** / **Seaborn** – Data visualization  
- **WordCloud** – Visualizing common terms  
- **NLTK** – Natural language text cleaning  
- **Jupyter Notebook** – Interactive data analysis

---

## 📂 Project Structure
📁 ChatGPT_Review_Analysis
│── chatgpt_Review_analysis.ipynb # Jupyter Notebook with code & analysis
│── chatgpt_reviews.xlsx # Dataset (not included for privacy)
│── README.md # Project documentation
│── /images # Folder for generated charts & wordcloud

yaml
Copy
Edit

---

## 📊 Workflow
1. **Load Dataset** from Excel (`chatgpt_reviews.xlsx`)
2. **Clean Data**
   - Fill missing review text
   - Remove rows missing ratings or dates
3. **Visualize**
   - Ratings distribution (bar chart)
   - Average ratings over time (line chart)
   - Monthly review volume (bar chart)
4. **Text Analysis**
   - Merge all review text
   - Clean and preprocess
   - Generate a word cloud

---

## 📸 Example Outputs

**Ratings Distribution**
![Ratings Distribution](images/ratings_distribution.png)

**Average Rating Over Time**
![Average Rating Over Time](images/avg_rating_trend.png)

**Monthly Review Volume**
![Monthly Review Volume](images/review_volume.png)

**Word Cloud of Common Words**
![Word Cloud](images/wordcloud.png)

> 📌 Place generated chart images in an `/images` folder for them to display correctly.

---

## ⚡ Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/chatgpt-review-analysis.git
   cd chatgpt-review-analysis
Install dependencies:

bash
Copy
Edit
pip install pandas matplotlib seaborn wordcloud nltk openpyxl
Download NLTK stopwords:

python
Copy
Edit
import nltk
nltk.download('stopwords')
Place your dataset (chatgpt_reviews.xlsx) in the project folder.

Run the notebook:

bash
Copy
Edit
jupyter notebook chatgpt_Review_analysis.ipynb
📌 Data Requirements
The dataset should contain at least:

Review – User's review text

Ratings – Numeric rating score

Review Date – Date of review

👨‍💻 Author
Developed by [Sachin Pal] –Data Analyst
