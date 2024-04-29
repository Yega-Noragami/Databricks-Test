# Databricks-Test

This project includes all the files necessary for performing data ingestion, data transformations, and data storage using a databricks notebook 


### How to set up the project 

Update docker-compose.yaml file to make sure that you are using the correct volume. I have alreadt updated the config to use current directory. 

```
    volumes:
      - ./:/home/jovyan
```

### Docker Set up

To strat the project run the following command

```
docker compose up 
```

The Analysis for the file has been performed in the Analysis.ipynb notebook  

### Analysis.ipynb 

Contains code for the following as per the requirements of the project. 

1. Data Ingestion
2. Data Transformation 
3. Data Manipulation 
4. Data Visualisation 
5. Data Storage 
