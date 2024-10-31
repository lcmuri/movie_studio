

# Data Analysis on Movie Financials

This project presents a comprehensive analysis of movie financials, exploring production budgets, box office gross, and Return on Investment (ROI). By analyzing various datasets, we aim to uncover the underlying factors that drive a movie's financial success and provide valuable insights into the correlation between budget size and profitability. This analysis includes detailed visualizations, predictive models, and hypothesis testing.

## Datasets Used

The project utilizes the following datasets:

1. **IMDB Data**:
    - Metadata about movies, including titles, release years, genres, and IMDB ratings.

2. **Box Office Mojo Data**:
    - Detailed financial information like production budgets, domestic and worldwide gross earnings.

3. **Supplementary Data**:
    - Additional information such as actor/actress names, directors, and other variables influencing a movie's financial performance.

## Project Overview

### Key Objectives
This project has several core objectives aimed at understanding the financial landscape of the movie industry:

1. **Analyze Movie Financial Success**:
    - Investigate how production budgets correlate with worldwide box office gross and profit margins.
    - Explore ROI behavior across different budget ranges to identify any patterns in profitability.

2. **Correlation and Causality**:
    - Identify the relationships between key financial variables: production budgets, worldwide gross, domestic gross, profit, and ROI.

3. **Hypothesis Testing**:
    - Test assumptions such as whether higher-budget films generate higher ROI or how critical other factors like genre or release timing are to financial outcomes.

4. **Predictive Analysis**:
    - Build predictive models using machine learning algorithms to forecast a movie’s financial success based on input variables like budget and genre.

## Tools & Technologies

The following tools and libraries were used in the analysis:

- **Python**: The main programming language used for data manipulation and analysis.
- **Pandas**: Essential for managing and cleaning the datasets.
- **Matplotlib & Seaborn**: Used for visualizing data trends and insights.
- **Jupyter Notebook**: Served as the environment for conducting the analysis.
    
## Steps and Workflow

### 1. Data Cleaning
   - The first step was to load and clean the datasets. This involved:
     - Handling missing values by either filling them appropriately or dropping them.
     - Removing duplicate entries to ensure data integrity.
     - Formatting columns correctly (e.g., converting dates, numerical values).
     
### 2. Exploratory Data Analysis (EDA)
   - Visualized relationships between different financial metrics (e.g., budget vs. worldwide gross).
   - Generated correlation heatmaps and scatterplots to investigate patterns.
   - Analyzed the distribution of ROI and profit across various budget sizes.

### 3. ROI Analysis
   - Examined the distribution of ROI across movies to understand which types of films (based on budget) yield the highest returns.
   - Investigated whether smaller-budget films are more likely to provide higher ROI due to lower production costs.

## Analysis Results

### 1. Correlation Analysis
- **Strong Positive Correlation**:
  - There is a significant positive correlation between **Worldwide Gross** and **Production Budget** (0.73). Generally, higher-budget movies tend to perform better globally.
  
- **Weak Relationship with ROI**:
  - The correlation between **Production Budget** and **ROI** is weak (0.05). This suggests that big-budget films don’t always have proportionally higher returns on investment.
  
- **Negative Correlation Between ROI and Production Budget**:
  - As production budgets increase, ROI tends to slightly decrease (-0.05). This could imply that big-budget films involve more financial risk compared to smaller-budget films.

### 2. Return on Investment (ROI) Insights
   - **High ROI for Lower-Budget Films**: Smaller-budget films often yield the highest ROI due to their lower production costs.
   - **Larger Budgets Aren't Always Profitable**: While larger-budget films earn more gross revenue, they also come with higher costs, which doesn’t always translate into better profitability.

## Return on Investment (ROI) Calculation

### Overview
The **ROI** helps stakeholders understand the financial benefits of a project relative to its cost.

### ROI Formula
The formula for calculating ROI is as follows:

$$
\text{ROI} = \frac{\text{Net Profit} - \text{Total Investment}}{\text{Total Investment}} \times 100
$$

### Definitions
- **Net Profit:** The financial gain from improved student performance and retention rates.
- **Total Investment:** The costs incurred during the project, which may include:
## Conclusion
By using the ROI formula, stakeholders can evaluate the effectiveness and financial viability of the project.


- **Net Profit**: The financial gain from improved student performance and retention rates.
- **Total Investment**: The costs incurred during the project (software, data analysis tools, salaries, etc.).

### 3. Predictive Analysis
   - The predictive models created as part of the project show that **production budget** is a significant predictor of a movie's gross revenue. However, it is not a perfect predictor, as other factors (e.g., marketing, cast) play crucial roles in determining success.
   
## Insights and Takeaways

- **Larger budgets contribute to better box office performance but do not guarantee higher ROI**.
- **Smaller-budget films often yield higher ROI**, making them potentially more profitable investments.
- Factors such as **genre, marketing, and timing** can significantly influence a movie’s financial success.

## Future Improvements

- **Incorporate Talent Data**: By integrating actor and director popularity data, we could explore how cast and crew influence a movie's financial performance.
- **More Advanced Machine Learning Models**: Further experiments with models such as Random Forests or Neural Networks could help better predict the financial outcomes of films.
- **Time-Series Analysis**: Investigate the impact of release timing (e.g., summer blockbusters vs. holiday films) on box office success.


    ```

## Visualizations

The project includes several key visualizations:
- Correlation heatmaps for financial metrics
- Scatterplots illustrating the relationship between budget and box office performance
- ROI distribution histograms

### Visualizations

| Image 1                     | Image 2                     |
|-----------------------------|-----------------------------|
| ![Studio by Gross](tudiobyfross.png) | ![Heatmap](heatmapfinal.png) |
| ![Movies by Rating](moviesbyrating.png) | ![Genres Pie Chart](genrespie.png) |
| ![Movies by Votes](moviesbyvoytes.png) | ![Movies by Gross](aven.png) |

## Description of Images

- **Studio by Gross**: A visual representation of the studio's performance.
- **Heatmap**: A heatmap showcasing data trends.
- **Movies by Rating**: A chart illustrating movie ratings.
- **Genres Pie Chart**: A pie chart displaying genre distribution.
- **Movies by Votes**: A graph of votes received by movies.
- **Movies by Gross**: A chart showing gross revenue of movies.


# Movie Studio Recommendations
### 1. Emulate Successful Franchises
- **Action:** Analyze franchise models from leading studios.
- **Goal:** Create original content with franchise potential.

### 2. Diversify Genre Offerings
- **Action:** Explore a variety of genres like horror, action, and animation.
- **Goal:** Appeal to a broader audience base.

### 3. Leverage Strong IPs
- **Action:** Acquire or develop strong intellectual properties.
- **Goal:** Utilize existing IP libraries for expansion.

### 4. Innovate Marketing Strategies
- **Action:** Implement engaging marketing campaigns.
- **Goal:** Build audience anticipation using digital platforms.

### 5. Collaborate for Success
- **Action:** Form strategic partnerships with other studios.
- **Goal:** Enhance production quality and distribution reach.

## Conclusion

- These recommendations aim to position the new movie studio competitively in the evolving film industry landscape.
---
## Contributors

- [Abdihakim Issack](https://github.com/zaenhakeem)
- [Imran](https://github.com/malvadaox)
- [Boniface Ngechu](https://github.com/bonie99)
- [Linet Lydia](https://github.com/linetlydia)
- [Batuli Abdullah](https://github.com/batuli'02)
- [Tableau Dashboard Links](https://public.tableau.com/shared/XMQHJR676?:display_count=n&:origin=viz_share_link)
  ---

