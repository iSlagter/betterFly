# BetterFly - By Dor Slagter(HIT final project)
HIT Data science final project - web scraping/linear regression.

the betterFly project predict the ticket prices for upcoming flights to help me ;-) in selecting the optimum time for travel and the most importent selecting the cheapest flight to the desired destination.
Random forest regression model is applied to forecast the flight prices based on data scraped from Kayak.

## Table of Contents


- [Scraping](#scraper)
- [Analysis and Results](#project)
- [Authors](#authors)


## Scraping <a name="scraper" />
#### The Scraper  can be found [here](https://github.com/iSlagter/betterFly/blob/main/ScraperKayak.ipynb).

#### Here's a demo of the scraper in action (played at 2x speed):
![scraper (1)](https://user-images.githubusercontent.com/68873733/137405620-e8af4863-4359-4799-b518-7f1605ceb2a2.gif)

#### The scraped dataset can be found [here](https://github.com/iSlagter/betterFly/blob/main/BetterFly.ipynb).

#### In total, the data consists of 55,000 rows and 7 columns.


## Analysis and Results <a name="project" />

#### The project notebook can be found [here](https://github.com/iSlagter/betterFly/blob/main/BetterFly.ipynb).

#### Selected features are:
- Source (4 Sources were selected for this project)
- Destination (4 Destinations were selected for this project)
- Total Stops
- Average Price per Airline
- Duration
- Price (Target)

#### Correlation of features:

![image](https://user-images.githubusercontent.com/68873733/137396490-c72e4f89-441e-430a-b4a9-831081ff6375.png)

#### Experimenting with different models:
![image](https://user-images.githubusercontent.com/68873733/137396989-02b3f69b-d336-4600-b436-420e68069fb6.png)

#### The final selected model is the random forest regression model with:
| Metric | Score |
|:---:|:---:|
| MAE | 61.87 |
| MSE | 40409.87  |
| RMSE | 201.02 |

#### Therefore, the final model is able to predict flight ticket prices within around  ≈ $61.87.

#### The final model can be found [here](https://github.com/iSlagter/betterFly/tree/main/model).

![image](https://user-images.githubusercontent.com/68873733/137399435-4e2da145-512b-4df6-80e3-809e603b1727.png)


## Author <a name="authors"/>
- ### [Dor Slagter](https://www.linkedin.com/in/dor-slagter/)

