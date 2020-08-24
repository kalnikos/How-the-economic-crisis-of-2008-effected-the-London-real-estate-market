# How-the-economic-crisis-of-2008-effected-the-London-real-estate-market
By the summer of 2007, global financials markets had begun to show signs that the bill for a years long binge on cheap credit was coming due. Many big banks were ready to collapsed and the investors was warning that they might be not able to withdraw money back. 


In this project, I tried to examine how the real estate market of London efected by the crisis. I exported a data set from Kaggle with over than 13500 values. Data from 1995 till 2019 which mentioned to the areas of London. The basic target features that I used to draw conclusions  was the area, year, month, average house price and sold houses per period.

# Data Cleaning
After reading the data I made some cleaning in order to manipulate them. I made the following changes and created the following variables.

•	Made new columns in order to present the year the month and the post code

•	Parsed numerical data out of the post code

•	Convert object data type to numerical type

•	I filled the NaN values in the number of crimes column with the average value of crimes in order to keep as many data as I could.

# EDA

## Number of sold houses over the years

The chart show as a big decline in sold houses after 2008. In total, half of the houses were sold compared to the previews year.
![sold_houses_over the years](https://user-images.githubusercontent.com/66875726/91078294-1b1c5a00-e64b-11ea-9c81-79b305a82a8e.png)

## Let’s see also the distribution of the sold houses prices over the years, the number of the sold houses and the level of the prices per mont 

![sold_houses](https://user-images.githubusercontent.com/66875726/91079400-ac400080-e64c-11ea-96a5-f51d86119494.png)

![months](https://user-images.githubusercontent.com/66875726/91080590-76038080-e64e-11ea-841f-b050fcb22df5.png)



