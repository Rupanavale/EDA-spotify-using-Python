# EDA Spotify Using Python
This repository contains an Exploratory Data Analysis (EDA) project on Spotify data, performed using Python(Jupyter Notebook).

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Exploratory Questions](#exploratory-questions)
- [Visualization](#visualization)
- [Insights](#insights)
- [License](#license)

## Project Description
Spotify is a proprietary Swedish audio streaming and media services provider founded on 23 April 2006 by Daniel Ek and Martin Lorentzon. It is one of the largest music streaming service providers, with over 527 million monthly active users, including 210 million paying subscribers, as of March 2023. 

In this project I have performed Exploratory Data Analysis (EDA) on Spotify data using Python(Jupyter Notebook). The analysis includes data exploration, data cleaning, data visualization, and deriving insights from the data. The scripts and notebooks in this repository cover different techniques and visualizations used in EDA.

The purpose of this EDA is to understand the data, discover patterns, identify anomalies, and derive meaningful insights that can help to make informed decisions or guide for further analysis.

## Installation
To run the code in this repository, you need to have Python and the required libraries installed. 

The following libraries are used in this project: 

 Pandas : [https://pandas.pydata.org/] 
 
 NumPy : [https://numpy.org/install/] 
 
 Matplotlib : [https://matplotlib.org/] 
 
 Seaborn : [https://seaborn.pydata.org/] 

If you don't have Python installed, you can download it from the official Python website: [(https://www.python.org/downloads/)] Or you can use Anaconda (Jupyter Notebook) : [https://www.anaconda.com/]

##  Usage
1. Clone the repository to your local machine: git clone https://github.com/Rupanavale/EDA-spotify-using-Python.git

2. Navigate to the specific dataset or analysis of interest.

3. Open the Python script or Jupyter notebook in your preferred environment (e.g., Jupyter Notebook, JupyterLab, or any Python IDE).

4. Execute the code cells or run the script to perform the EDA.

5. Explore the visualizations, summary statistics, and insights obtained from the analysis.

## Data Source
The dataset used in this project is sourced from two Kaggle datasets which are as follows:
1. [[https://www.kaggle.com/datasets/arnabchaki/indian-restaurants-2023](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db)]
2. [https://www.kaggle.com/datasets/lehaknarnauli/spotify-datasets?select=artists.csv]

## Technologies Used
- Microsoft Excel
- Python(Jupyter Notebook)

## Exploratory Questions
1. Which are the top 10 lowest Popular songs?
2. What are the top 10 songs with popularity greater than 90?
3. What is the correlation between all variables?
4. Are loudness & energy correlated?
5. Are popularity & acousticness correlated?
6. How is the distribution of total number of songs each year since 1922?
7. What is the duration of songs over the years?
8. What is the average duration of songs over the years?
9. What is the duration of songs for different genres?
10. What are the top 5 genres by populrity?



## Visualization
1. Correlation HeatMap Between All Variables:
![image](https://github.com/Rupanavale/EDA-spotify-using-Python/assets/109949193/da002210-252e-47b7-8f23-a933fedfe1ce)

2. Regresssion plot between Loudness & Energy:
![image](https://github.com/Rupanavale/EDA-spotify-using-Python/assets/109949193/a834d41b-ffe0-4e79-8bb7-a03655347ac2)

3. Regresssion plot between Popularity & Acousticness:
![image](https://github.com/Rupanavale/EDA-spotify-using-Python/assets/109949193/27e8846f-f48d-41b6-b68e-5a0297b41692)

4. Distribution plot of total number of songs each year since 1922:
![image](https://github.com/Rupanavale/EDA-spotify-using-Python/assets/109949193/1492f786-b093-4a58-80e6-5d4d61444772)

5. Bar plot of duration of songs over the years:
![image](https://github.com/Rupanavale/EDA-spotify-using-Python/assets/109949193/8364358d-5df3-4faa-8a89-29a4f32226bb)

6. Line plot of average duration of songs over the years:
![image](https://github.com/Rupanavale/EDA-spotify-using-Python/assets/109949193/067823cc-1c86-4e1c-bdc8-8d9e5537d296)

7. Bar plot of duration of songs for different genres:
![image](https://github.com/Rupanavale/EDA-spotify-using-Python/assets/109949193/7229e799-c81c-454f-b7f1-df104d37cabf)

8. Bar plot Top 5 genres by populrity:
![image](https://github.com/Rupanavale/EDA-spotify-using-Python/assets/109949193/ed967e9c-ef9e-41fd-b131-752ee5c5b971)


## Insights
1. There is high positive correlation between loudness & energy.
2. There is negative correlation between popularity & acousticness.
3. Number of songs each year were increased in the recent years since music became more accessible to the people globally with technological advancement
4. Duration of the songs in 1920's were less and later it increased in late 1930's, this remained consistent until 2010 where the duration of songs were high & after 2010 again the duration of songs started decreasing.  
5. Duration of songs of 'World' genre are highest & lowest for 'Children's Music'.
6. Top 5 genres by popularity are 'Dance', 'Pop', 'Rap', 'Hip-Hop', 'Reggaeton'.



## License
This project is licensed under the [MIT License](LICENSE).
