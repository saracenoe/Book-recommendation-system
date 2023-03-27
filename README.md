# Book recommendation system

"My Content" is a start-up who's goal is to encourage people to read by recommending relevant content to users.

In this project, we want to create a first MVP that will take the form of an application that will be recommend relevant articles to users based on their implicit 
preferences, their profiles and the articles content. 


Goals: This Recommender System will complete the following tasks: 

* We will compare different models of recommender system on the Globo.com dataset. 

* We will use Azure Functions to store the recommendations in Azure CosmosDB and to make the recommendations available to the users.

* We will integrate that Azure Functions into a Streamlit App that will be able to recommend relevant articles to users. 

## Installation
  ### Prerequisites
  Python 3.8\
  Azure subscription\
    
  ### Virtual environment
      
      conda create -n mybook python=3.8 -y
      conda activate mybook
      
  ### Dependencies    
      pip install -r requirements.txt
