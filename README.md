# KDD-Group-4-Project

### Team Members : Mahesh HS, Rujul Joshi , Rutul Joshi, Tharani Kumaresan, Tejal Devkule, Samanwitha Lakkadi, Gunakar Maddi, Prathima Mahankali.

### Introduction to Problem or Opportunity
##### Amid all the uncertainty brought on by COVID-19, the pandemic has re-ordered real estate markets across the board on an unprecedented scale. No one could have predicted it. Not the economists, not the real estate agents, and especially not the nation’s homebuilders. But a pandemic definitely caused an emotional run on housing and more than one year after the Covid-19 crisis shut down and warped so much of American life, things are still unpredictable, but the outlook isn’t bright for housing. Home prices are overheated, mortgage rates are rising, the supply of homes for sale is anemic and consumer confidence in the housing market is falling.
  

### Research Question(s)
##### Analyze the weekly data and monthly data of new listings, pending sales, homes sold, housing inventory, price and price drops in the data set of the hosing market before covid and after covid for county and metro region types and discover various changes  like in housing sales,  listings, inventory, price and real estate trends and also represent them visually using graphs.
##### As  with Covid-19, Due to falling mortgage rates , the cost of borrowing money to buy a house is dropping. Also for people whose jobs weren’t negatively impacted were able to save more during quarantine times. Hence we need to study the Equity position of homebuyers and if there is any possibility of market to downturning post pandemic?
##### In the wake of Covid-19, the fear of Virus transmission have majorly impacted the house pricing for metro states like New York and New Jersey. Also due to work from home policies and for people transitioning their position to completely remote the freedom to ditch high rents or mortgage costs in major cities for more affordable locales has become tempting. Hence the question that leads study would be what are the reasons of inbound moves and  how popularity of a relocation destination have impacted real estate market?
##### Is it safe to expect that time-on-market (TOM) will have an unfavorable impact on price change?.
##### During the pandemic, which predictors can be the deciding factor used to anticipate price changes, more clearly?

### Stage 2 
### Data Preprocessing
#### For data preprocessing we hav extracted the only the required columns from the data set and for the missing data we have imputed the missing values with mean/median.
### Data Understanding and Exploration
#### We have visulized the data set using seaborn in google colab, please find the python notebook below.(Note : the file is shared to all people with uncc.edu account, please access the the file with your logged in uncc account)  
##### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18hPXngk_eccdJhUNni-OAqzfSx5f1mdq?usp=sharing)
### Data Preparation for Modeling
#### The main Data set is partiotined such that the 80% is used for training and the remaining 20% for testing.

### Stage 3
### Modeling
#### We have used ANN Model, we have split our data to 80% for the training and 20% for testing. We have used a network with 4 hidden layers and for optimization function, we have used Adam Optimizer with learning rate of 0.001, we ran the training for 500 epochs and batch size of 32.


### Evaluation and Results
#### For the test dataset our model had the loss of 0.0153 and mean squared error of 0.015, the results and graphs are in the below colab notebook.
#### (Note : the file is shared to all people with uncc.edu account, please access the the file with your logged in uncc account)
#### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QOYGkaR89PmuEH1akaA670bIhcz6NKI9?usp=sharing)

### Project Folder Drive Link : https://drive.google.com/drive/folders/1WbxRlMnzmZLU2u1RfO4txaz1B0DKo1Lh?usp=sharing


### Data Resources
##### Data Set : https://drive.google.com/drive/folders/1WbxRlMnzmZLU2u1RfO4txaz1B0DKo1Lh?usp=sharing
