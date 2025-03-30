
# 🎬 Data-Driven Movie Studio Strategy

This project explores which types of films perform best at the box office and translates these insights into actionable recommendations for a new movie studio. Our analysis combines data from multiple movie industry sources to guide decisions around genre selection, budgeting, casting, and production planning.

---

## 📌 Project Objective

To help a new movie studio make informed decisions by analyzing historical movie data and identifying:
- What genres perform best?
- Which budget ranges yield the highest return?
- Who are the top-performing directors and writers?
- What runtime leads to better ratings?
- How can we balance critical acclaim and popularity?

---

## 📂 Datasets Used

We integrated four key datasets:

- **Box Office Mojo:** Domestic and international gross earnings
- **IMDB (via SQLite):** Ratings, genres, directors, writers
- **The Numbers:** Production budgets and profitability
- **TMDB:** Popularity metrics, vote counts, and language

---

## 🧠 Methodology

Following the CRISP-DM process:
1. **Business Understanding**
2. **Data Understanding**
3. **Data Preparation**
4. **Exploratory Data Analysis (EDA)**
5. **Visualization & Insight Generation**
6. **Strategic Recommendation Development**

---

## 📊 Key Findings

- 🎭 **Top Genres:** War, Musicals, and Animation deliver high ratings and wide appeal
- 🎬 **Bankable Talent:** Directors like *Amitabh Reza Chowdhury* and *Mahesh Manjrekar* consistently receive strong audience ratings
- 🕒 **Ideal Runtime:** 90–150 minutes yields higher ratings and better viewer engagement
- 💰 **Best ROI:** Mid-range budgets ($5M–$50M) balance risk and profitability

---

## ✅ Final Recommendations

- Focus on genres with strong critical and global appeal
- Partner with high-performing, reputable directors and writers
- Standardize runtimes between 90–150 mins
- Target mid-range budgets for optimal return

---

## 💼 Contributors

Beth Nyambura, Benson Ouma, Harrison Karime, Rahab Gachie

---

## 📎 Note

This project uses a zipped SQLite database (`im.db.zip`) that is **excluded from the repository** due to size limits.  
Please place the zip file in the project root folder before running the notebook.

---

## 📁 Repository Structure

```
.
├── notebooks/
│   └── final_analysis.ipynb
├── data/
│   └── im.db.zip (excluded from Git)
├── README.md
├── .gitignore
└── Data_Driven_Movie_Strategy_Presentation.pptx
```

---

## 📊 License

This project is for educational purposes under the Data Science Curriculum (DSC Phase 2).
