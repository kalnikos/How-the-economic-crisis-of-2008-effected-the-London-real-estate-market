# How the London real estate market affected by the economic crisis of 2008
By the summer of 2007, global financials markets had begun to show signs that the bill for a years long binge on cheap credit was coming due. Many big banks were ready to collapse and the investors was warning that they might be not able to withdraw money back. 


In this project, I tried to examine how the real estate market of London afected by the crisis. I exported a data set from Kaggle with over than 13500 values. Data from 1995 till 2019 which mentioned to the areas of London. The features that I used to draw conclusions  were the area, year, month, average house price and sold houses per period.

# Data Cleaning
After reading the data I made some cleaning in order to manipulate them. I made the following changes and created the following variables.

•	Made new columns in order to present the year the month and the post code

•	Parsed numerical data out of the post code

•	Convert object data type to numerical type

•	I filled the NaN values in the number of crimes column with the average value of crimes in order to keep as many data as I could.

# EDA

## Number of sold houses over the years

The chart below show a big reduce in sold houses after 2008. The houses were sold compared to the previews year were reduced by 50%.

![sold_london_over](https://user-images.githubusercontent.com/66875726/99805167-c2266a00-2b44-11eb-9b3f-b12eedf296b1.png)


## Let’s see also the distribution of the sold houses prices over the years, the number of the sold houses and the level of the prices per month 

![sold_houses](https://user-images.githubusercontent.com/66875726/91079400-ac400080-e64c-11ea-96a5-f51d86119494.png)

![months](https://user-images.githubusercontent.com/66875726/91080590-76038080-e64e-11ea-841f-b050fcb22df5.png)

![prices](https://user-images.githubusercontent.com/66875726/91080661-98959980-e64e-11ea-9198-9cdb9b896684.png)

## The distribution of the prices per area

![area_distribution](https://user-images.githubusercontent.com/66875726/91081152-56208c80-e64f-11ea-8983-8ed5b53ce65b.png)

In conclusion you can find in this exploratory data analysis, charts of the sold houses per area, a correlation matrix that show us the correlation between the features and a pivot table which present the sold houses and the average prices of the houses per year per area. 




