# Microsoft Movie Studios Business Plan
Authors: Ogo Ndugba, Zach Pollatsek, Tom Chapman

## Overview
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Business Problem
Movie production has significant up-front costs that will require internal stakeholder support to adequately fund new projects. Further, it will be important to generate engagement with Microsoft's titles both to maximize return on investment and to legitimize Microsoft as a content producer in the future. Therefore, this analysis aims to generate recommendations on how best to deploy the content production budget. 

We will use data from IMDB, The Numbers and The Movie Database to determine answers to the following questions:

- What genres of movie are likely to optimize return on investment?

- What is the relationship between movie budget and expected gross revenue? 

- What season/month should we target releases in order to optimize our return on investment?


## Data

[IMDB](https://IMDB.com) is the largest, most comprehensive movie database publicly available on the web. [The Numbers](https://www.the-numbers.com/) is a trusted resource for movie business information including movie budget, performance and various revenue categories. The data files analyzed herein provide movie titles, genre tags and release date, as well as financial characteristics such as worldwide gross revenue and production budget.

## Methods

This project uses descriptive analysis to provide an overview of the factors that go into executing a successful movie production and release. 

## Results

Movies with the Animation, Adventure or Sci-Fi tags generally produced the highest ROI. War and Western movies were the least profitable.
![](images/MedianROI_genre.png)


There is a strong correlation between production budget and return on investment.
![](images/WorldwideGrossRevenueByProductionBudget.png)


The data reveals that movies released in June, July, or November produce the highest return on investment.
![](images/MedianROI_ReleaseMonth.png)


## Conclusions

- **Movies in the animation, adventure and sci-fi genres tend to produce better return on investment than other genres.** As a result, we recommend prioritizing the creation of content that aligns with these genres. Avoid war and western-themed content as these tend to produce unfavorable ROI.
- **Movies released in June, July and November tend to generate better return on investment than other months.** As a result, we recommend targeting new releases for the summer or November months.
- **There is a strong correlation between movie production budget and return on investment.** Microsoft should direct its movie-making budget toward a relatively small number of projects in the above genres to avoid diluting ROI.

## Next Steps

Entering a new industry comes with significant startup costs. To help Microsoft produce an initial movie that is a blockbuster, we recommend the following additional analysis.

- Additional budgetary data to increase sample size and refine observations.
- Identify replacement metrics to measure success where budget/revenue is unavailable.
- Further analysis of the top grossing 50 movies of the past decade. Taking a more in depth look at what made these movies so financially successful.

## For More Information

See the full analysis in the [Jupyter Notebook](main_notebook.ipynb) or review [this presentation](MSFT_Movie_Presentation_P1_Project.pdf).

For additional info, contact Ogo Ndugba, Zach Pollatsek or Tom Chapman as follows:

- Ogo:    ogo.ndugba@gmail.com 
- Zach:   zacharypollatsek@gmail.com
- Tom:    thomas.h.chapman@gmail.com

## Repository Contents
- data
- images
- working notebooks
- README.md
- MSFT_movie_presentation_P1_Project.pdf
- MSFT_movie_analysis.ipynb
