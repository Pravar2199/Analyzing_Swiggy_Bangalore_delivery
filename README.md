# Analyzing_Swiggy_Bangalore_Delivery
This project aims to analyze Swiggy's food delivery operations in Bangalore, India using data from a public dataset. The code is written in Python and uses various data analysis and visualization libraries to perform the analysis.

**Table of Contents**

##### 1. Project Overview

##### 2. Installation

##### 3. Usage

##### 4. Data Source

##### 5. Results

##### 6. Conclusion

## Project Overview
The code is divided into two main parts:

######  Data preprocessing: 
This section includes loading the dataset, cleaning and transforming the data, and extracting relevant information for analysis. This is done using pandas, numpy, and other libraries.

###### Data analysis and visualization: 
This section involves using various data analysis techniques and libraries such as matplotlib and seaborn to analyze and visualize the data. The analysis includes insights such as popular cuisines, delivery time trends, and top restaurant chains, among others.
Installation
To run the code, you will need to have Python 3 and the following libraries installed:

**1. pandas**

**2. matplotlib**

**3. seaborn**

You can install these libraries by running the following command:

> pip install pandas matplotlib seaborn

## Usage

To run the code, simply open the notebook in Jupyter or any other compatible environment and run each cell sequentially. The cells are already arranged in the order of execution.

## Data Source

The dataset used in this project is sourced from the [ineuron internship](https://internship.ineuron.ai/) and is available [here](https://drive.google.com/file/d/1FwL6jfwfL5Na_6Pacbv5rjrz9zu5h_i-/view). It contains information about food delivery orders from Swiggy in Bangalore, India.

## Results


This project analyzes Swiggy's delivery data for Bangalore, India. The dataset contains details of various restaurants, including their location, cuisine, cost for two, and ratings. The aim of the project is to gain insights into the data and visualize the results.

**Data Extraction**

The first step was to extract the data from the CSV file "Swiggy Bangalore Outlet Details.csv" using the Pandas library.

**Data Transformation**

The extracted data was transformed by:


1. Converting the 'Cost_for_Two' column to numeric data

2. Converting the 'Rating' column to numeric data

3. Removing any rows with missing data

4. Removing any special characters or spaces in column names

5. Creating a new column for the average cost per person

6. Creating a new column for the cost category

7. Data Loading

8. After transforming the data, it was saved to a new CSV file "Swiggy Bangalore Outlet Details - Transformed.csv".


The basic information about the data, top 5 rows of the data, number of unique values for each attribute, average cost for each cuisine, and average rating for each cuisine were printed.

**Data Analysis and Visualization**

**1. Average Rating by Cuisine and Cost Category**

A heatmap was created to visualize the average rating by cuisine and cost category. The heatmap showed that Chinese, Continental, and North Indian cuisines had the highest ratings in the high-cost category, while Fast Food and Street Food had the highest ratings in the low-cost category.

**2. Distribution of Restaurants by Cost Category**

A pie chart was created to show the distribution of restaurants by cost category. The chart showed that the majority of the restaurants fell in the medium-cost category.

**3. Distribution of Ratings**

A histogram was created to visualize the distribution of ratings. The histogram showed that the ratings were normally distributed, with most of the ratings falling between 3.5 and 4.5.

**4. Number of Restaurants by Location**

A bar chart was created to show the number of restaurants by location. The chart showed that BTM had the highest number of restaurants, followed by Koramangala 5th Block and HSR.

**5. Average Cost per Person by Location**

A bar chart was created to show the average cost per person by location. The chart showed that the restaurants in Electronic City had the highest average cost per person, followed by Whitefield and Sarjapur.

**6. Average Rating by Cost Category**

A box plot was created to show the average rating by cost category. The plot showed that the high-cost restaurants had a slightly higher average rating than the medium and low-cost restaurants.

## Conclusion

After analyzing the Swiggy Bangalore outlet details dataset, it can be concluded that the majority of restaurants fall into the medium cost category, with 58.7% of all restaurants having an average cost per person between ₹200-₹500. Indian cuisine is the most popular cuisine, followed by North Indian and Chinese cuisines. Interestingly, the average cost per person for restaurants serving North Indian and Chinese cuisines is higher than the average cost per person for restaurants serving Indian cuisine.

The average rating for all restaurants in Bangalore is 3.5, with the highest rated cuisines being Continental, French, and Italian. Additionally, it can be observed that the number of restaurants is highest in the BTM layout location, followed by HSR layout and Koramangala 5th Block.

Furthermore, the analysis revealed that the majority of restaurants have an average rating between 3.0 and 4.0. The highest-rated restaurants fall into the high cost category, with an average rating of 4.1. In contrast, restaurants falling into the low cost category have the lowest average rating of 3.3.

Overall, the analysis suggests that Bangaloreans prefer medium cost restaurants serving Indian cuisine. However, restaurants serving cuisines such as Continental, French, and Italian have a higher average rating and may be worth exploring for those seeking a more upscale dining experience.
