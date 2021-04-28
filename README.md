# Sneakers-x-IH
<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
*Gabriel Verrone*

*DA PT - Sao Paulo - October 2020*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
I'm a huge sneakerhead myself (google the term in case you've never heard of it). So, the goal of the project is to evaluate whether sneakers could be compared to regular stocks as a financial asset. A secondary goal is to evaluate a StockX dataset to evaluate some nuances that are specific to the sneaker resale market. 

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
* Are sneakers more lucractive as a financial asset than stocks? 
* What are the relevant nuances that one must know before investing in sneakers for resale? 
* How does the performance of a few stocks compare with that of a handful of sneakers?  

<a name="dataset"></a>

## Dataset
* There are two separate group of datasets. The first was obtained from a competition organized by StockX (https://stockx.com/news/the-2019-data-contest/).
* The dataset obtained from this StockX competition is made of approximately 99k orders made by customers on the StockX website, from September 2017 until February 2019.
* The second dataset is composed by a group of csv files showing the open/close price of a few stocks I decided to compare sneakers with.

<a name="cleaning"></a>

## Cleaning
The CSV provided by StockX didn't need much cleaning. I was able to obtain reach some conclusions basically using Tableau.
The CSV files from the stocks I analyzed needed some cleaning. Mostly added some dates which were missing (stock exchanges do not operate on some days like weekends/holidays, whereas StockX sales did happen on those dates)
To normalize that effect, I added the dates to make sure that there would be a corresponding date/stock price to every single day in which an order was made on StockX.

<a name="analysis"></a>

## Analysis
* First I will look at the performance of a few stocks.
* Then, I'll collect some relevant info to explain the basics about the global sneaker sale/resale market.
* After that I'll compare the performance of those stocks with that of the sneakers in the StockX dataset

<a name="conclusion"></a>

## Conclusion
* Just like with stocks, if you know which sneakers to buy, when to buy and when to sell, they can be more profitable than stocks.
* But just because sneakers can be more profitable, it doesn't mean it's a more practical way of saving money and building one's portfolio.

<a name="future-work"></a>

## Future Work
The next step is to build a model that would estimate the future resale price of sneakers based on the amount of mentions on Twitter.

<a name="workflow"></a>

## Workflow
The first step was to obtain the dataset from the StockX competition, because it was the only way of looking at an organized dataset with past prices of a few select sneakers.
After that, I downloaded the datasets that showed prices of stocks traded during the same dates as that of the competition dataset.
Once I had those two groups of datasets, then I started the data cleaning step.

<a name="links"></a>

## Links

[Repository](https://github.com/lvl1charizard/Sneakers-x-IH.git)  
[Slides](https://public.tableau.com/profile/gabriel.verrone#!/vizhome/SneakersxStocks/Story1?publish=yes)  
