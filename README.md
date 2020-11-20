# How the London real estate market affected by the economic crisis of 2008
By the summer of 2007, global financial markets had begun to show signs that the bill for a years long binge on cheap credit was coming due. Many big banks were ready to collapse and the investors were warning that they might be not able to withdraw money back. 


In this project, I tried to examine how the real estate market of London was affected by the crisis. I exported a data set from Kaggle with over 13500 values. Data from 1995 till 2019 which mentioned the areas of London. The features that I used to draw conclusions  were the area, year, month, average house price and sold houses per period.

# Data Cleaning
After reading the data I made some cleaning in order to manipulate them. I made the following changes and created the following variables.

•	Made new columns in order to present the year the month and the post code

•	Parsed numerical data out of the post code

•	Convert object data type to numerical type

•	I filled the NaN values in the number of crimes columns with the average value of crimes in order to keep as much data as I could.

# EDA

## Number of sold houses over the years

The chart below shows a big reduction in sold houses after 2008. The houses sold compared to the previous year were reduced by 50%.

![sold_london_over](https://user-images.githubusercontent.com/66875726/99805167-c2266a00-2b44-11eb-9b3f-b12eedf296b1.png)


## Let’s see also the distribution of the sold houses prices over the years, the number of the sold houses and the level of the prices per month 

![average_prices](https://user-images.githubusercontent.com/66875726/99805490-51cc1880-2b45-11eb-8c6b-bf3b8720e489.png)

![months](https://user-images.githubusercontent.com/66875726/99807575-5f36d200-2b48-11eb-94cc-2dffd5be5e5c.png)

![av_months](https://user-images.githubusercontent.com/66875726/99807740-9c02c900-2b48-11eb-9111-cabf307eb428.png)

## The distribution of the prices per London area

![area](https://user-images.githubusercontent.com/66875726/99807907-d10f1b80-2b48-11eb-9da9-ded19e532c64.png)

## The distribution of the prices in the five most expensive London area over the years

![kens](https://user-images.githubusercontent.com/66875726/99808459-935ec280-2b49-11eb-8a92-0baacc2769ee.png)


In conclusion, the analysis shows that the magnitude of the crisis was huge, the sales between 2008 and 2009 reduced by 50% and although 12 years passed the real estate market has not reached the pre-crisis sales level. A worth mentioning fact is that the houses prices reduced in 2009 by 10% and increased the following years rapidly. 




