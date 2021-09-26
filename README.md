

# Project: Visualizing Real World Data - Women's Shoe Prices

## Overview

The goal of this project was to practice visualization using real world data, under a tight time constraint. 

I have chosen to study a 2019 dataset of around 19,000 women's shoes and their associated product information. The dataset is the public extract of one of the databases sold by Datafiniti, a database provider. The public extract was downloaded from Kaggle.

Each line of the dataset is a pair of shoes sold at a merchant website. It shows brand, description, price, merchant and more.

Although it is a big dataset, a lot of information appears to be missing or non-usable, which made for long data cleaning at the beginning of the project. We only kept 725 rows and 6 columns from an initial dataset of 19,045 rows and 47 columns.

I have focused on studying the potential links between price and brand, and between price and color.



## Technical info

 - The dataset used was uploaded at https://www.kaggle.com/datafiniti/womens-shoes-prices?select=7210_1.csv
 - The codebook for the dataset can be found at https://developer.datafiniti.co/docs/product-data-schema
 

## Necessary Deliverables

 - A github repo was created specifically for this project, and can be found at https://github.com/HH2805/M2-mini-project-Dataviz-Helene
 The repo includes:
 - a jupyter notebook named 'Shoes_Dataviz_preparation', which was used mainly to clean the dataset.
 - The slides of a Tableau workbook which can also be found at: https://public.tableau.com/profile/h.l.ne.hill#!/

## Insights

Please refer to the Tableau workbook.

## Conclusion & Going Further

It would have been useful to have a more complete dataset to study. I suspect that brand and color may not be the most important variables explaining price of shoes.
The project timeframe did not allow to un-nest the info in the 'Shoe Features' column. It would be interesting to do so. I suspect we could find explicative variables there, such as style (pump, peep-toes, sandal etc.), heel height, material (leather or synthetic) to explain the price variable. 
It would be interesting to use the statsmodel library to see which of these variables explain the most the price of a shoe.
Finally, there is another dataset by Datafiniti relating to men's shoes. It would be interesting to study the differences between the 2 datasets to see if there is a difference in price between women and men.

