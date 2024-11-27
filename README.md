# Market Analysis & Insights For Strategic Movie Production

###### Authors ;
[Noel Christopher](https://github.com/NOE0464) 

[Margaret Nyairo](https://github.com/vidya-byte)

[Victor Masinde](https://github.com/Masinde10)

[Anthony Ekeno](https://github.com/sananthonio)

[James Ngumo](https://github.com/nyange21)


## Business Understanding

### Overview
This project is designed to aid a company's venture into the movie production industry by launching a new studio. Through comprehensive data analysis, the project will identify current trends and provide actionable insights from box office data. This information will guide the company in determining the types of movies that are most successful in today’s market, thereby supporting strategic content creation and maximizing box office returns.

![Alt text](https://github.com/NOE0464/dsc-phase-2-project-v3/blob/main/WB.08.58%20PM.jpeg)


###  The Problem Statement
The company needs to pinpoint what types of movies are most successful in the current market to propel the new studio's launch. Specifically, we aim to:

1. **Identify the Genres Performing Well at the Box Office**: Determine which movie genres are currently popular and yield high box office returns.
   
2. **Analyze Movie Budgets and Profitability**: Evaluate the relationship between production budgets, returns, and overall profitability to find the optimal investment range.
   
3. **Assess Audience Demographics Driving Success**: Understand which demographic segments are contributing significantly to box office revenues.
   
4. **Recommend Optimal Release Seasons or Windows**: Identify the best times of the year for releasing movies to maximize box office performance.

### Main objectives
To identify the most successful types of films currently at the box office and translate these insights into actionable strategies that guide the new movie studio's production choices, ensuring competitive and commercial success in the film industry.

### Keystakeholders
1. Audience
2. Investors and Financers 

### Data Understanding
The data used in this analysis contains data collected from various popular movie sites such as Box Office Mojo, IMDb, movie info and budget info. It contains detailed information on movie titles, actors, directors, box office earnings, and movie ratings.
 
We are working with four different datasets for this project. The first one named `imdb` has `73856 rows and 5 columns`. It has all the three types of data namely Float, intergers and objects. The data here helps us analyse the genres, titles, runtime minutes and the ratings of movies

The second dataset is named `gross` and it has `3387 rows and 5 columns`. It has Float, intergers and objects as dataypes. The data here helps us analyse income generated as it contains columns with domestic and foreign gross data.

The third dataset is named `budget` and it has `5782 rows and 6 columns`. The datatypes in this dataset are intergers and objects only. It has columns that can help us calculate the budget of producing a movie i.e production_budget. We can also see seasonal trends as it has a column with information on dates.

The last dataset is named `movie_info` and it has `1560 rows and 12 columns`. The datatypes in this dataset are intergers and objects only. It has columns with information about writer, director, studio etc that can help us make informed reccomendations at the end of the project

The imdb data was stored in a sql database with several tables as shown in the Entity Relationship Diagram below
![Alt text](movie_data_erd.jpeg)

### Data Cleaning
Missing values and duplicated rows are handled. Also, columns irrelevant to the project are dropped. Formatting of columns and their contents for smooth analysis.

### Data Analysis; Transformation, Merging, Visualisations.
`Transformation`-Converting the data types in our datasets to enable  manipulation. `gross[foreign_gross] &                         budget[domestic_gross,producion_budget,worldwide_gross]` the columns in this dataset are object datatype,this means the numeric figures are read like strings instead of numbers. So to have clarity ,we convert them to float datatype for more accurate readings

`Merging`-Having a cleaned data versions we perform merge .Merging data frames combines multiple datasets into a single, unified dataset,allowing for a more comprehensive analysis.Merging the datasets will enable us to explain more with visualization for better understanding of our objective

#### visaualisations
The merged data is analysed by use of visualizations. Sample visualizations include:

a)demographic perfomance analyses how the ratings are perceived locally, internationally and the total outcome.

![alt text](https://github.com/NOE0464/dsc-phase-2-project-v3/blob/main/Rating.09.21%20PM.jpeg)

b) Monthly Release compares the different months earnings.

![alt text](https://github.com/NOE0464/dsc-phase-2-project-v3/blob/main/month.14.07%20PM.jpeg)

c) Studio production Budgets compares financial input of different studio.

![alt text](https://github.com/NOE0464/dsc-phase-2-project-v3/blob/main/studio.13.39%20PM.jpeg)

For more Visualisation follow this Tableau Link = [Interactive Dashboard](https://public.tableau.com/views/FILMANALYSIS_/InteractiveDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Conclusions
Demographics Driving Success:
-The analysis of ratings indicates that PG-13 rated movies have the highest domestic earnings, while R-rated movies perform better in foreign markets. This suggests that different ratings attract different audience segments.

Optimal Release Seasons:
-The analysis of monthly performance shows that October has the highest total gross, followed by September, while June has the lowest total returns. This indicates that the fall(SEPT/OCT) season may be the most lucrative time for movie releases.
-The foreign gross tends to outperform domestic gross in September and October, suggesting that these months may attract a more international audience.

Movie Budgets and Profitability:
-There is a strong positive correlation (0.800886) between domestic gross and worldwide gross, suggesting that movies with higher domestic earnings tend to perform well globally.
-The analysis of studio budgets shows that A24 has the highest production budget, which may correlate with its success in producing high-grossing films.
-Studios like Fox have lower production budgets, which may limit their ability to produce high-grossing films.

Most popular Gernres;
-Documentary
-Comedy,Drama,History
-Action, Thriller & Comedy,Drama,Thriller
-These are the most popular genres in the movie industry

## Recommendations
We would recommend the company to focus on :

High-Performing Genres:The new studio should prioritize producing films in the`Documentary` , it yield's high box office returns.

Strategic Release Timing: Plan major releases for the fall months `(September and October)` to capitalize on higher audience turnout and box office performance. September has highest returns on Domestic market while October has highest returns in the Foreign market

Budget Allocation : since we want to minimize cost and it is not necessarily correct that a high production budget relates to higher returns. The optimal solution would be choosing  the studio with the lowest production budget , which is `Fox`

Target Audience: Marketing strategies based on the ratings that perform best in different markets. For instance, focus on PG-13 ratings for domestic releases and R ratings for international markets.
 
If interested in other options, consider the following genres ; `Comedy/Drama/History, Action/Thriller & Comedy/Drama/Thriller`.

If interested in other studios with favorable budgets, consider ; ` Independent Film Channel(IFC) & Warner Bros(WB)`.


