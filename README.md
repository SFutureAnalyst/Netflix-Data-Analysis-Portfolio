
![Netflix-Marvels-Daredevil-Banner](https://github.com/SFutureAnalyst/Netflix-Data-Analysis-Portfolio/assets/146059342/7eb7c749-ceba-4354-ba50-0dfd7a10bed9)

# Netflix-Data-Analysis

_**A Journey Through Data to Reveal Netflix's Hidden Potential :-**_
- - The research work aims to perform data analysis on the data on Netflix primarily on movies and shows. The analysis focuses on various details like release year, type, rating, duration etc. Analysis also focuses on popularity of the shows and movies amonst Netflix viewers.

## Table of Contents

- [About the project](#about-the-project)
- [About the dataset](#about-the-dataset)
- [Tools and libraries](#tools-and-libraries)
- [Phases of the project](#phases-of-the-project)

## About the project
This project is a self-study project, its main objective is to help me practice on a real dataset and strength my analysis skills in Python.
<br>

It is about cleaning and analyzing Netflix movies and tv shows data, and getting insights about the countries where they were filmed, their ratings and release years.
<br>

The detailed notebook of the project is [here](Netflix%Data%20Analysis.ipynb).

<hr>

## About the dataset
This project's dataset is an open-source data ![Netflix-Marvels-Daredevil-Banner](https://github.com/SFutureAnalyst/Netflix-Data-Analysis-Portfolio/assets/146059342/522cfd61-6c38-4f61-a3b5-70b6f132988e)
from __Kaggle__.
<br>

> [You can find it here.](https://www.kaggle.com/datasets/rajakali/netflex-analysis)

<u>
The dataset contains one "csv" file which has 7789 entries with the following information:
</u>

* __Show_id__: Primary Key as ( s1, s2, s3 ...)
* __Category__: Movie or TV Show
* __Title__: The name of the movie/tv show
* __Director__ The name of the director.
* __Cast__: The names of the movie/tv show's cast
* __Country__: The country(s) which this movie/tv show was filmed
* __Release year__ Month and Year
* __Rating__: Age-based media reviews
* __Duration__: The number of minutes for movies or number of seasons for tv shows
* __Type__: International, Dramas, Kids Tv, Sports movies, Horror Movies etc.
* __Description__: A sentence which describes this movie/tv show on Netflix

<hr>

## Tools and libraries
This project was done in Python using Jupyter Notebooks.

The libraries used are:
* __Pandas and Numpy__: for exploration, cleaning and analysis
* __Matplotlib and Seaborn__: for visualizations

<hr>

## Phases of the project
**1. Data Exploration**

<ul>

After reading the data I have to explore it, its columns, and the info it contains. So, I've gained information about:

1. Checking the Top and Bottom of the Data.
2. The dataset size.
3. The dataset shape.
4. The datatypes of the columns.
5. What each column represents
6. The Overall Information of the Dataset.

</ul>

<hr>

**2. Data Cleaning**

<ul>

After exploring the data, I need to check it if there are any issues.

1. Search for duplicates
  
    * There has only 2 Duplicates Records in the dataset.

2. Search for nulls

    2.1. Dropping those null values for better analysis or better resilt

3. Change the incorrect datatypes into appropriate datatypes

</ul>

**3. Analysis on Dataset**

<ol>

I have used some methods and function on this netflix data analysis project namely;
<br>
* __Basic_Functions__ : These are basic function in analysis.

  1. head()
  2. taiil()
  3. shape
  4. size
  5. columns
  6. Tdtypes
  7. info()
<br>

* __Mostly_Used_Functions__: These are mostly used functions.

  1. value_counts()
  2. unique()
  3. nunique()
  4. duplicated()
  5. isnull()
  6. dropna()
  7. isin()
  8. str.contains()
  9. str.split()
  10. to_datetime()
  11. dt.year.value_counts()
  12. groupby()
  13. max(), min(), mean()
<br>

* __Methods__: These are followed.

  1. Creating New Columns
  2. Creating New DataFrame
  3. Filtering (Single Column)
  4. Filtering (Multiple Columns)
  5. Filtering with AND
  6. Filtering with OR
<br>

* __Library__: Seaborn library has been used

</ol>

<hr>
