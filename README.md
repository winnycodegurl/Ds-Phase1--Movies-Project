**PHASE ONE MOVIES PROJECT**

 Prediction project overview

**Introduction**

Very well!Lets go.

![awesome](https://github.com/winnycodegurl/Ds-Phase1--Movies-Project/assets/162214319/a2b093d4-bc0c-4b4d-b02c-8af59d553990)


This is a data science project aimed at helping Microsoft , a new movie company, establish what types of films are currently doing the best at the box office.The findings are the translated into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

 **Overview**
  
Our main goal is to create the best selling movies in the industry.

**Business Understanding.**

  Research Box Office Trends:
  Analyze recent box office hits to identify genres, themes, and characteristics that have performed well. This analysis can involve studying successful films across different genres.
  What is the best genre?

Consider Audience Preferences: Understand the preferences of different demographic groups, such as age, gender, and geographical location. This can help in tailoring movie concepts to specific target audiences.
what geographical location would make the best audience?

Explore Collaborations: Consider partnerships or collaborations with established filmmakers, directors, writers, or production companies who have a track record of success in creating box office hits.
Who are the best writers?
Who are the best producers in the industry?

**Projet Structure**
Data Understanding.
1.Data Exploration

In this project I explore the data sets to understand the available information  and identify relevant features.This includes getting the types of data available,the sizes of data available and the sources of data available.My data sets are from ImDb an amazon company.
There are three files: Two CSV files named 'tn.movie_budgets.csv.gz', and 'bom.movie_gross.csv.gz' and a sqlite database named 'im.db'

2.Data Cleaning

 Preprocessing the data to ensure its quality and sustainability for analysis throughout the project is maaintained.This involves removing the missing values and duplicates using the data science inbuilt functions.

3.Data Analysis

Utilize data Science techniques to analyse the data seta and extract meaningful insights.

Data VIsualization
Develop  graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

**Technologies Used**

Python

pandas

Numpy

Matplotlib

Seaborn

SQL

Jupyter Notebook

**File Description**

data/:bom.movie_gross.csv.gz,im.db,

Directory containing the input datasets (movies.csv, actors.csv, viewers.sql)

Movieprojectcode.ipynb: Directory containing Jupyter Notebooks for data exploration, analysis, and modeling.

README.md: This file, providing an overview of the project and its structure

**Usage**

Execute the code cells in the notebooks sequentially to replicate the analysis and modeling process.
Refer to the comments and markdown cells in the notebooks for detailed explanations of each step.

**Results**

The project will provide actionable insights and recommendations to Microsoft, aiding them in making informed decisions during the movie production process.
The least rated movies are Romance,Horror and comedy.

The top two most produced movies are Documenataries and Drama.

The most frequently watched movies are Documentaries.

second best movie has a rntime of is 70.0.

The two best writers are:Brian Baucum and Loreto Di Cesare.

The best producer is Maria Demeshkina Peek .

A correlation coefficient of 0.685682 indicates a moderately positive correlation between the two variables. This means that as production_budget increases, domestic_gross tends to increase as well. In this case, a correlation coefficient of 0.685682 suggests a moderate positive relationship between production_budget and domestic_gross.

A positive covariance suggests that when production_budget increases, domestic_gross also tends to increase, WHILE when the production_budget decreases the domestic_gross also decreases. the magnitude is quite large, indicating a strong relationship bwtween the production budget and domestic income.

RECOMMEDATIONS.

1.Given that Documentaries and Drama are the most produced movies, Microsoft should focus on these genres as they seem to resonate well with the audience.Since Documentaries are the most frequently watched movies, Microsoft could consider allocating more resources towards producing high-quality documentaries or exploring sub-genres within documentaries that are particularly appealing to the audience.

2.Given that Brian Baucum and Loreto Di Cesare are identified as the best writers and Maria Demeshkina Peek as the best producer, Microsoft should continue to collaborate with these talented individuals and potentially invest in nurturing emerging talents in writing and production.

3,Budget Allocation:

With a correlation coefficient of 0.685682 and a positive covariance between production_budget and domestic_gross, it's evident that there's a moderately positive relationship between the production budget and domestic gross. Microsoft should consider allocating sufficient budgets to productions while ensuring effective cost management to maximize return

4.The second-best movie has a runtime of 70.0 minutes. Microsoft may consider analyzing the runtime preferences of the audience and adjusting their movie lengths accordingly to optimize viewer engagement.s.


Click to add a cell.



