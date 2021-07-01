
![wine_chalkboard](https://user-images.githubusercontent.com/19881320/54493655-d8c4ea00-48a8-11e9-8b50-28394f91ba62.jpg)

<h1><center>Wine Review Analysis<center></h1>

<h2><center>Team Pura Pythonic Vida</center></h2>

<p align="center">
  <img width="180" src="https://user-images.githubusercontent.com/19881320/54484151-b85c4780-4836-11e9-923f-c5e0e5afe866.jpg">
</p>


## Contact Information

William Ponton: [LinkedIn](https://www.linkedin.com/in/williamponton/) 

Email: [@gorbulus](waponton@gmail.com)

REPL: [@gorbulus](https://repl.it/@gorbulus)

Github: [gorbulus](https://github.com/gorbulus)


## Project Description

#### Welcome to Team Pura Vida's Wine Review Analysis for the [RMOTR](https://rmotr.com/) Data Science Coursework.  

Started: 2.17.19

Completed: 3.17.19

### Project Vision Statement: 

This project will explore a dataset with Python and use standard Data Science skills to clean, analyze, visualize, and interpret data  and elegantly use the data patterns to provide scientific meaning to a dataset I found on [kaggle](https://www.kaggle.com/zynicide/wine-reviews).

## Inspiration

Since I have spent the majority of my career in the FoodService and FoodService Equipment Industry, I wanted this project to be related to a culinary dataset of some kind.  The Wine Review dataset caught my attention because I always had been suspicious of the concepts of quality and price being directly affect the consumer's mind.  Usually "you get what you pay for" is a safe bet, but sometimes a more expensive commodity is not the "best" or preferred choice for consumers.  This is especially evident in the Food Industry where epicurean prices are related to a subjective palette.  I want to analyze the Wine Reviews and see if the more expensive wines are always the highest rated ones by consumers.
    

I think that this dataset offers some great opportunities for text related predictive models. My overall goal in the future is to use another version of this dataset (with three additional columns) to do some predictive analysis on the Text based ```Description``` column. Ultimately I am interested in building a bot that could produce a convincing Wine Review.  If anyone has any ideas, breakthroughs, or other interesting insights/models please post them~!  Feel free to fork as well.  I am open to constructive feedback and tips as well.  


## Project goals

1. Import and inspect the dataset using ```pandas```.
    
2. Analyze the dataset using ```pandas``` and ```numpy```.
    
3. Create visualizations using ```matplotlib``` and ```seaborn```.
    
4. Interpret meanings from the data using the ```Scientific Method``` ("Data Science!").
    
## Project Stack
Python has a rich Data Science functionality that has been motivated by teams of scientists and engineers trying to solve scientific and engineering problems.  Python's Object Oriented Design, ease of syntax, and available libraries make it the industry standard for Data Analysis.  A 2016 study done by [O'Reily](https://www.oreilly.com/data/free/files/2016-data-science-salary-survey.pdf) shows that ```Python``` is now dominant over ```R``` throughout the Data Science community, favoring ```Python 3.6``` to the soon to be extinct ```Python 2.7```.  


```Python``` has become the fastest growing programming language of 2019, and continues to remain the industry standard for modeling and analysis in the scientific and engineering industries.  The Scientific Python Stack is an array of technologies that make Python so powerful for Data analysis and statistical prediction.

To get everything running in this project, use ```pip install -r requirements.txt```

### Let's take a quick tour of the Scientific Python (SciPy) stack I used for the Wine Review Analysis:


### Language
- Python 3.6 (replacing legacy Python 2.7 in 2020)
- Cython (a speedy C library for backing up numpy)


### Scientific & Numeric Power
- SciPy
- NumPy
- SciKitLearn


### Interactive Environment
- Anaconda IDE
- IPython Notebooks
- GitHub (version control)
- RMOTR Notebooks


### Data Science Libraries
- Analysis tools
    - NumPy
    - Pandas
    - Cython
- Visualization tools
    - Matplotlib
    - Seaborn
    - Bokeh

![Python_Stack](https://user-images.githubusercontent.com/19881320/54723910-6457a880-4b3f-11e9-850b-8c2be2ff62a8.jpg)


## Dataset Overview

I searched Food related datasets on [kaggle](https://www.kaggle.com/) and found the Wine Review dataset.  I was looking for a medium sized CSV file between 50MB - 1GB.  I also wanted something that would take some processing but wasn't a wrangling project.  I wanted to make some visualizations as well using the ```seaborn``` library.  I used kaggle's filtering and search and found the [Wine Review](https://www.kaggle.com/zynicide/wine-reviews/) dataset.
    
The data was scraped from [Wine Enthusiast Magazine](https://www.winemag.com/) during the week of June 15th, 2017.

This dataset is 150,930 Wine Reviews in one csv file of about 50 MB:

```winemag-data_first150k.csv```contains 10 columns and 150k+ rows of Wine Reviews scraped from WineEnthusiast during June of 2017.


Each record in the dataset represents a single wine review from an online user of [Wine Enthusiast Magazine](https://www.winemag.com/)

The following is a brief summary of the 10 different columns of data included in ```winemag-data_first150k.csv```:

![reviews_df_dtypes](https://user-images.githubusercontent.com/19881320/54575190-7c0d2080-49c9-11e9-97b4-46c510a2c89d.jpg)
    

## Data Columns

1. Country  - The country of origin of the wine.

2. Description - The description of the wine's flavor profile.

3. Designation - The vineyard where the wine's grapes are sourced.

4. Points - The number of points Wine Enthusiast  Magazine rated the wine on a scale of 1-100.

5. Price - The cost for a single bottle of the wine.

6. Province - The province or state that the wine is from.

7. Region 1 - The wine growing area in a province or state (for example, Napa Valley in California).

8. Region 2 - (Optional) A more specific region in a wine growing area (for example, Rutherford inside Napa Valley).

9. Variety - The type of grapes used to make the wine (for example, Pinot Noir).

10. Winery - The winery that made the wine.

    
## Analysis
    
Check out the [WineReviewAnalysis](WineReviewAnalysis.ipynb) Notebook for the analysis.

    
### Dependencies
To get everything running, use ```pip install -r requirements.txt```

    
### Results
After cleaning and inspecting the Wine Reviews dataset, we used numerical and statistical analysis to create visualizations from the dataset.  Using the focused plotting of point distributions, jointplots, and heatmaps, it has been determined that the best value of wines in the 150,930 reviews is as follows:
    
- Made in California
- A Chardonnay, Pinot Grigio, or Cabernet Savignon
- 12.00 - 18.00 USD per bottle
- 87.5 or greater points is highly likely
    
### Conclusions
- California is well known for its Wine producing industry, and agriculture capabilities.

- This means that overall, wines in the 10.00 - 20.00 range have frequently better ratings when compared to more expensive wines.

- This could be due to the price point of these wines, or the fact that most consumers drink expensive wines less frequently or only for special occasions.

- It makes sense for the wine producers to focus on the market demand for their products and target their resources towards the taste of the public.

- There is no correlation between price and quality when comparing the majority of commercial wines.
   
### Contact Information
What did you think about the Wine Review Analysis?

Cheers.

Email: [@gorbulus](waponton@gmail.com)

Github: [gorbulus](https://github.com/gorbulus)

REPL: [@gorbulus](https://repl.it/@gorbulus)

William Ponton: [LinkedIn](https://www.linkedin.com/in/williamponton/) 

![FoodCubes](https://user-images.githubusercontent.com/19881320/54451802-09cae080-472a-11e9-9add-d6a051bacada.jpg)
