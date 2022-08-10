# Phase 1 Project - Joel Mott

### Project Overview:

The purpose of this project is to help Microsoft’s (fictional) emerging film studio optimize its return on investment (or ‘ROI’). After couching my analysis in Microsoft’s interests and explaining a little about my process steps, I relay three business recommendations regarding suggested genres, release dates, and directors.

### I couch my analysis in the following business context:

* Microsoft is opening a film studio and seeking data on films doing well at the box office. 
* This project defines box office success as return on investment (ROI).
* Specifically, ROI is defined here as the amount of money in USD that a film made worldwide, minus its production budget. 
* The project analyzes box office data along with genre, month of release, and directors to help Microsoft make informed decisions on producing films more likely to have a robust ROI.

### Data Overview: 

* This study examines data from 1,949 films with budgets that are not small (general consensus is that small budgets end at around $2 million USD).
* Budget and ROI data was drawn from the-numbers.com; the CSV file used may be found under this repo's 'zippedData' folder.
* Genre, month of release, and director information comes from IMDb; the database used may be found under this repo's 'zippedData' folder.

### Analysis Overview:

First, I examined:
1. when high-ROI films tend to be released 
2. which genres earn higher ROIs
3. which directors make high-ROI films

Then I compiled more specific findings:

1. when high-ROI films in a particular genre tend to be released
2. which directors within that genre tend to make higher-ROI films

### Visualizing Data (click each graph to expand and see axis labels and legend):

Preliminary genre findings are summarized in the following graph:
* ![image](https://user-images.githubusercontent.com/51928528/183788794-52b2da22-708f-4c75-92c4-0e390e83ce54.png)

Since not all genres follow the same release date patterns over the course of the year and are often produced under different directors, each profitable genre is broken down with its own respective graph highlighting optimal release months and their top-ten ROI-earning direcotrs, all of whom are still alive and active. For purposes of this README, I include the top three genres of adventure, animation, and action:
* ![image](https://user-images.githubusercontent.com/51928528/183789450-0b8b4e57-ed12-4634-a831-d599beb48c0e.png)
* ![image](https://user-images.githubusercontent.com/51928528/183789476-ef28d1c4-71dd-4928-bc00-50c2dfafbf02.png)
* ![image](https://user-images.githubusercontent.com/51928528/183789506-5b06c930-86f8-45a7-9ced-4786bfdb61b6.png)

### Conclusions:

While each of these genres average a positive ROI, the following three stand out with the highest earning potential:
1. an adventure film released in June
2. an animation film released in April
3. an action film released in May

Furthermore, Microsoft may be able to maximize ROI by recruiting one of the respective top ten ROI-earning directors listed next to each genre’s graph. 

### Repository Structure:
```
├── zippedData
│   ├── im.db (the IMDb database file with genre, release date, and director info)
│   ├── tmdb.movies.csv.gz (the-numbers.com CSV with budget and ROI info)
├── .canvas
├── .gitignore
├── LICENSE.md
├── README.md
├── movie_data_erd.jpeg (the ERD for the IMDb database file)
├── presentation.pdf
└── project_notebook.ipynb
```
