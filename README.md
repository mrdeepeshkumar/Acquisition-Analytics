# Machine Learning 
# Project: Acquisition Analytics Bank Marketing
## Installation
### Install the requirements 
This project requires Python 3 and the following Python libraries installed:

* [NumPy](http://www.numpy.org/) 
* [Pandas](http://pandas.pydata.org/)
* [matplotlib](http://matplotlib.org/)
* [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have tool to run and execute a [Jupyter Notebook.](http://ipython.org/index.html)
Make sure you use Python 3.If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

### Intalling Anaconda Python
The easiest way to install Jupyter Notebook as well as NumPy, Pandas,matplotlib is to start with the Anaconda Python distribution.
Follow the installation instructions to download the [Anaconda](https://www.anaconda.com/distribution/) Python. We recommend using Python 3.7.

git clone https://github.com/mrdeepeshkumar/Acquisition-Analytics Use cd to navigate into the top directory of the repo on your machine

Launch Jupyter by entering

This will open the Jupyter Notebook software and project file in your browser. 
## Download the data 
Before running the notebook, you'll first need to download data we'll be using. This data is located in the bank_marketing.csv. We will extract these into the same directory as Acquisition-Analytics.

## Objective: 

To reduce the customer acquisition cost by targeting the ones who are likely to buy and improve the response rate, i.e., the fraction of prospects who respond to the telemaketing campaign.

## Project overview:
Acquisition analytics is one of the classic problems in building a response model.Response models are often used by marketing teams to 
create an acquisition strategy according to the budget constraints.  

The data is related to a `marketing campaign` done by a `Portuguese Bank`. The campaigns were telephonic, i.e., sales agents made phone calls
to sell a term deposit product. 
### Data
* `Customer data`: Demographic data, data about other financial products like home loans, personal loans, etc.

* `Campaign data`: Data about previous campaigns (number of previous calls, number of days since the last call was made, etc.)

* `Macroeconomic data`

* `Target variable`: Response (Yes/No)

### Starting the project:
`Acquisition-Analytics`repository contains the all necessary project files. To run this project , you may download the all files.The implimented code is provided in the `Acquisition_Analytics_Bank_Marketing.ipynb` jupyter notebook file.You will also be required to use the marketing_data.csv dataset files to complete your work. 

This project contains two files:
* `Acquisition_Analytics_Bank_Marketing.ipynb`: This is the main iPython file which you must run this file to run this project.
* `bank_marketing.csv`: This is the dataset. You'll load this into the main file.
### Run
To successfully run the project In a terminal or command window, navigate to the top-level project directory Acquisition_Analytics/ (that contains this README) and run one of the following commands:
     
    ipython notebook Acquisition_Analytics_Bank_Marketing.ipynb
  or
    
    jupyter notebook Acquisition_Analytics_Bank_Marketing.ipynb
    
### Methodology:
#### Business understanding - bank marketing dataset: 
A Portuguese bank had conducted a telemarketing campaign for a term deposit product somewhere around late 2010. A term deposit is very 
similar to a fixed deposit, where you deposit money for a fixed period of time.  

Through the campaign, the bank had collected data about the prospects' demographics, other financial products they have purchased in the
past (loans, deposits, etc.), the number of times they were called, etc. They also recorded the `response data`, i.e., whether the person
had subscribed to the term deposit product, which is the `target variable`. 
The bank's marketing team wants to launch yet another telemarketing campaign for the same product. 

#### Data understanding - EDA:
Understood the data using univariate and multivariate analysis.Identified relevant predictor variables for a response using EDA.
#### Feature Selection:
Used Pricipal Component Analysis algorithm for feature selection.
#### Model Building:
In the this process built `Logistic Regression` model.
#### Campaign optimisation:
Sorted the prospects in order of decreasing probability of response predicted by the Logistic Regression and target the top 30%.
#### Assessing the financial benefits of the project:
Created report to Chief Marketing Officer
![Recommendation_to_CMO](https://user-images.githubusercontent.com/40337495/63093419-b67fe700-bf82-11e9-9c34-9095713cffc3.PNG)
## Conclusions
Optimized per customer acquisition cost 82 to 53 through the target telemarketing campaign and attain 95% of total conversions by 
targeting only 30% of the total client base. 



