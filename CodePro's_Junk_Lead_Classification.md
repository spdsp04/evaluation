# CodePro's Junk Lead Classification

1. Data Pipeline

1.1 Create functions for data pipeline in utils.py ( 30 marks )

the functions works as intended i.e., performs all the mentioned tasks, reads and write etc . . . . . 

1.2 Create data validation checks for input raw data and output data of the data pre processing pipeline ( 10 marks)

the functions works as intended i.e., performs all the mentioned tasks, reads and write etc . . . . . 

1.3 Create constants.py file for Data Pipeline (3 marks)

all the paths, file names and lists and other constant variables are present in constants file

1.4 Create significant_categorical_level.py for mapping of 'first_platform_c' 'first_utm_medium_c' and 'first_utm_source_c' (1 marks)

all the lists have all the correct elements . . . 

1.5 Create an airflow dag python file for data pipeline (6 marks)

all the tasks are defined properly, relations are properly defined, import statements are proper and the tasks id are as mentioned in the docstring
the DAGs final run is successful in grid and all the tasks are successfully executed in graph view screenshot


2. Training Pipeline


2.1 Create functions for training pipeline (10%) + setup mlflow in utils.py

the functions works as intended i.e., performs all the mentioned tasks, reads and write etc . . . . 
the functions works as intended i.e., sets up the experimentation properly, logs the necessary parameters and the model, reads and write etc . . . . 
the artifacts can be clearly seen in the screenshot
the model is visible and its stage is set to production


2.2 Create constants file of training pipeline


all the paths, file names and lists and other constant variables are present in constants file


2.3 Create an airflow dag python file for training pipeline

all the tasks are defined properly, relations are properly defined, import statements are proper and the tasks id are as mentioned in the docstring.
the DAGs final run is successful in grid and all the tasks are successfully executed in graph view screenshot


3. Inference Pipeline


3.1 Create functions for inference pipeline in utils.py

the functions works as intended i.e., performs all the mentioned tasks, reads and write to the proper table as and when required and 'app_complete_flag' is removed from the list of final features
the model is loaded from the registry and the function gets the predictions
the function works as intended


3.2 Create a constants.py file

all the paths, file names and lists and other constant variables are present in constants file


3.3 Create an airflow dag python file for inference pipeline

all the tasks are defined properly, relations are properly defined, import statements are proper and the tasks id are as mentioned in the docstring
the DAGs final run is successful in grid and all the tasks are successfully executed in graph view screenshot



4. Model Experimentation


4.1 Setup pycaret and mlflow environment

the db is created with proper name
the uri is properly set and mlflow server is running at the same uri
pycaret's setup is with all all the appropriate parameters


4.2 Building all the specified models in pycaret with all the features


the models that are supposed to be dropped are dropped


4.3 Screenshot of mlflow ui


the experiments are visible in the screenshot
the artifacts can be clearly seen in the screenshot


4.4 building the best pycaret with only the specified features and no transformations

the setup sets transformation and normalize to false


4.5 Screenshot of mlflow ui after dropping features


the experiments are visible in the screenshot
the artifacts can be clearly seen in the screenshot









