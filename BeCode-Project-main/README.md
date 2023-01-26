# BeCode Project

Description:

#Data Scrapping

#Data Visualization

For this first data analysis project, I asked the following two questions to the dataset obtained after scrapping the Immoweb Website ;

1) What's the relationship between a furnished apartment to rent in Brussels on its price versus an unfurnished apartment ?
2) How does having a garden in a furnished house affect the price when you want to buy a house in the center of Antwerp ?

The graphs aim to answer these two questions.

#Machine Learning

In the file "machine learning", I built a very basic pipeline that gave me a very low number (0.05). I was not satisfied. The cleaning of Florent's database would have taken too long, I decided to use Anil's.

I tried to build a linear regression model but it gave again a low value (0.2). The random regression was much accurate though (0.74). I was pretty happy with that.

I learned a lot in this project. In the Data PreProcessing part, I cleaned the dataset by dropping unnamed values and the columns I didn't need.

I then checked the outliers. There were none. 

Thanks to the sns heatmap, I found out which columns were the most relevant for this project. I therefore dropped the 11 columns that didn't interest me. 

In the Dummies section, I devided the type of real estate into numerous different columns, to make the results more precision.

I then specified my data set for the x and y axis and checked the accuracy for the linear regression. The score wasn't very high, even after playing with the data. I had the same issue with the random regression at first but after some data manipulation, the accuracy drastically improved. 

---------------------

Installation:

#Data Scrapping
#Data Visualization

To obtain my graphs, I had to import the following librairies ;

- Pandas
- Seaborn
- Matplotlib

#Machine Learning

- Pandas
- numpy
- Matplotlib
- seaborn
- sklearn
- warnings

--------------------

Usage:

#Data Scrapping
#Data Visualization

This code is only useful to understand the logic of pandas and a data analysis project.
The graphs can only be used for the sake of this first data analysis project.

#Machine Learning

The machine learning will deliver accurate price predictions of the real estate market in Belgium.

--------------------

Visuals:

#Data Scrapping

#Data Visualization

The visuals are obtain thanks to Matplotlib.

#Machine Learning

The visuals are again obtain thanks to Matplotlib.

--------------------

Contributor:

#Data Scrapping

Maité & Dimitri


#Data Visualization

Augustin Carbonnelle


#Machine Learning

Augustin Carbonnelle

------------------

Timeline:

#Data Scrapping
#Data Visualization

Day 1 - 5 : Getting familiar with Pandas, doing exercices & watching tutorials.
Day 6 & 7 : Creating the code & obtaining the visuals.

I didn't have enough time to clean my data in the way that I wanted and to make the graphs more readable
but it was nevertheless a good first exercice.

#Machine Learning

Learning the material

Cleaning the data

Building the pipeline, getting the result & evaluation
