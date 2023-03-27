# Book recommendation system

In this project, we want to create a first MVP that will take the form of an application that will be recommend relevant articles to users based on their implicit 
preferences, their profiles and the articles content. 


Goals: Create a Recommender System. To do so, we will complete the following tasks: 

* Compare different models of recommender system on the Globo.com dataset. 

* Use Azure Functions to store the recommendations in Azure CosmosDB and to make the recommendations available to the users.

* Integrate that Azure Functions into a Streamlit App that will be able to recommend relevant articles to users. 

## Installation
  ### Prerequisites
  Python 3.8\
  Azure subscription\
    
  ### Virtual environment
      
      conda create -n mybook python=3.8 -y
      conda activate mybook
      
  ### Dependencies    
      pip install -r requirements.txt

## Usage
  ### Data
  Download and extract the files from [Frames Dataset](https://www.kaggle.com/datasets/gspmoreira/news-portal-user-interactions-by-globocom).

  ### Exploratory Data Analysis
  The main notebook presents the results of the EDA
