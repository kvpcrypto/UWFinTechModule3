# UWFinTechModule3
Module 3

# Crypto Arbitrage
A financial analysis on Bitcoin between two exchanges, Bitstamp and Coinbase, to determine if any arbitrage opportunities exists.

## Technologies

Jupyter
Pathlib
Pandas
Matplotlib


## Usage

First step is to collect the dataset from both exchanges and then prepare it so that it can be properly analyzed. In the 'Resources' folder,  coinbase.csv and bitstamp.csv is given so next is to clean it up. This entails making sure there are no unknown or NaN values and that all values are floats and not strings. An example of this would be to remove any "$" so that there are no issues with computing the statistics. For the purpose of this analysis, we specifically want to check for any sizable spread between the two exchanges and an easy way to see that is to plot both datasets on the same graph.

![Bitstamp_Coinbase](https://user-images.githubusercontent.com/61864923/185065007-a05c0f4c-fe5d-4d0a-8e94-0d30a4ae42ed.jpg)

To determine if future arbitrage opportunities exists we'll need to analyze areas of interests and analyze areas throughout the dataset to find any trends or behaviors. Areas of interest would be anytime in the dataset where the spread was large. When analyzing the spread we have to take into account that the transaction or profit will have to exceed the trading costs. The image below will show the areas of interest for the analysis.

![Bitstamp_Coinbase_Zoom](https://user-images.githubusercontent.com/61864923/185067386-15e5e83f-1276-4402-906e-af9c33fceb1c.jpg)



## Contributers

UW FinTech
Kenny Pham
