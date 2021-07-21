# Data Scraping 

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Challenges](#challenges)
  * [Outcome](#outcome)
  * [Directory Tree](#directory-tree)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [Credits](#credits)



![source_website](https://user-images.githubusercontent.com/40088060/126423236-3b940a82-69f7-43ab-a41e-6fa0cdb4aadf.png)
*Source Website Screen Shot*


## Overview

This is a data scraper designed to scrape the wellona pharma's products data. In this project I managed to scrape the following information from the [website](https://wellonapharma.com/category/finished-products). I saved the scraped data into the __Pandas' Data Frame__ and exported to .CSV file. 
 
![Screen Shot 2021-07-21 at 12 20 19 pm](https://user-images.githubusercontent.com/40088060/126423022-0196dae4-d77b-486d-970b-2d35241c3463.png)
*Pandas Data Frame containing scrapped data*

## Motivation

What could be a perfect way to enhance the data science knowledge in this covid-19 period? Like most of the data enthusiast, I spend my time in learning Machine learning algorithms, Computer Vision tasks, Data Visualization libraries and reading some latest research papers on weekends. It is clearly evident that __DATA__ is the most critical part of the any data science project. Usually, we just download the data from the publicaly available repositories for our projects but I wanted to do something different. I decided to build the scraper that extracts the all of the essential information from the [website](https://wellonapharma.com/category/finished-products) and store that into the table like format. And that desire led me to build this data scraper in jupyter notebook.

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
For the conda environment users simp

1. Create the environment from the ```environment.yml``` file:
```bash
conda env create -f environment.yml
```
The first line of the yml file sets the new environment's name. For details see [Creating an environment file manually](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#create-env-file-manually).

2. Activate the new environment: ```conda activate myenv```
3. Verify that the new environment was installed correctly:
```bash
conda env list
```
You can also use ```conda info --envs```.

## Challenges

## Outcome


## Directory Tree 
```
├── requirements.txt
├── data_scraper.ipynb
├── environment.yaml
├── requirements.txt
└── README.md
```

## Technologies Used

[<img target="_blank" src="https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png" width="400" height="180">](https://www.python.org/)[<img target="_blank" src="https://jupyter.org/assets/main-logo.svg" width="400" height="180">](https://jupyter.org/)


[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/1200px-Pandas_logo.svg.png" width=400>](https://pandas.pydata.org/) [<img target="_blank" src="https://sixfeetup.com/blog/an-introduction-to-beautifulsoup/@@images/27e8bf2a-5469-407e-b84d-5cf53b1b0bb6.png" width=300>](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

## Team
[![Ronak Patel](https://user-images.githubusercontent.com/40088060/126430084-c7566f18-1e6b-48d3-b9c1-27ef25e80b8c.jpg)](https://nifty-johnson-3c6fae.netlify.app) |
-|
[Ronak Patel](https://nifty-johnson-3c6fae.netlify.app) |)



## Credits
- [Wellona Pharma](https://wellonapharma.com/) - I would really like to thank you Wellona Pharma
