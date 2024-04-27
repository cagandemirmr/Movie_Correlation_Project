
# Movie Correlation Analysis Project

What is my motivation?

It is my first data analysis project. I started this journey  to explore and  to show my python skills on data analysis .I took several several cources online and offline about statistics,python,data manipulation and Machine Learning.And somehow, i wanted to use this knowledge into dataset to evaluate my situation in my data analysis project.In this process, i saw that i developed many skills and also  that i need to improve myself in this journey as well.


Why did i build this project?

To withness end to end data analysis project, i started to it. At the same time, i wanted to observe relationship between movie features like budget and gross. I took data set from https://www.kaggle.com/datasets/danielgrijalvas/movies and inspired from alexthedata analytics project(https://www.youtube.com/watch?v=iPYVYBtUTyE&list=PLUaB-1hjhk8H48Pj32z4GZgGWyylqv85f&index=4)


What problem did you solve?
i made solution for  correlation problem between categorical and numerical data.


What did i learn?
In this project personally i learned lots of things.First of all, i learned that not all outliers should be supressed or excluded from data set. Also,everytime we should not fill missing falues with values or delete them.In addition to that, Before deciding corelation method, i learned that i  need to make test on data.


What makes my project stand out?

In exept other projects, i used several statistical like shapiro and Machine Learning methods such as one hot encoding.



## About the Data

- Movies data set consist of 7668 Rows and 15 columns.

 
- Columns are named as 'name', 'rating', 'genre', 'year', 'released', 'score', 'votes','director', 'writer', 'star', 'country', 'budget', 'gross', 'company', 'runtime'

- "name":cardinal value
- "rating": categorical value that based on appropriation rate for family or children in USA.
- "genre": categorical value that gives information of general concept of film such as Drama,action,etc.
- "year": it looks like numerical value but its categorical value because range of a value does not change too much.
- "released": this column can be classified as cardinal but it differs "name" column in terms of information that it keeps. "released" column have both date and country value.
- "score": numerical category.
- "votes": numerical value that represent how much a film loved.
- "director": it can be measured as cardinal value but it can be measured as categorical value because of well known directors and its effeect on film quality and box office.
- "writer": it can be calculated as cardinal because there are lots of writers and its effect on film quality changes.
- "star": it can be calculated as cardinal because there are lots of stars and its effect on film quality changes as well.
- "county": it should be categorical value because a county can have multiple films compared to "writer","star" and "country".
- "budget" : numerical value
- "gross": numerical value.
- "company": its look like cardinal but there are hundreds of company that produces thousands of good films.
- 'runtime' : its also numerical value.
