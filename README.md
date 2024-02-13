This is a part of the specialization on Coursera - Practical Data Science on the AWS Cloud offered by deeplearning.ai.

# Details of the projects:

# Analyze Datasets and Train ML Models using AutoML
1. In this section, we ingest and transform the customer reviews dataset and use AWS data stack services such as AWS Glue and Amazon Athena for ingesting and querying the dataset. Finally, we use AWS Data Wrangler to analyze the dataset and plot some visuals extracting insights.
2. Bias can be present in the data before any model training occurs. Inspecting the dataset for bias can help detect collection gaps, inform feature engineering, and understand societal biases the dataset may reflect. So we analyze bias on the dataset, generate and analyze bias reports, and prepare the dataset for the model training.
3. Next we use Amazon Sagemaker Autopilot to train a BERT-based natural language processing (NLP) model. The model analyzes customer feedback and classifies the messages into positive (1), neutral (0), and negative (-1) sentiment.
4. Then we use SageMaker BlazingText's built-in algorithm to predict the sentiment for each customer review.
   
# Steps to follow:
1. List and access the Reviews dataset files hosted in an S3 bucket
2. Install and import AWS Data Wrangler
3. Create an AWS Glue Catalog database and list all Glue Catalog databases
4. Register dataset files with the AWS Glue Catalog
5. Write SQL queries to answer specific questions on your dataset and run your queries with Amazon Athena
6. Return the query results in a pandas data frame
7. Produce and select different plots and visualizations that address your questions

## 
# Build, Train, and Deploy ML Pipelines using BERT
 
1. In this section, we prepare the Reviews dataset to train a BERT-based natural language processing (NLP) model. The model will be used to classify customer reviews into positive (1), neutral (0), and negative (-1) sentiments. We perform feature engineering and train the data with BERT. To perform the required feature transformation you will configure an Amazon SageMaker processing job, which will be running a custom Python script.
2. Next,  we train a text classifier using a variant of BERT called RoBERTa - a Robustly Optimized BERT Pretraining Approach - within a PyTorch model run as a SageMaker Training Job.
3. We define and run a pipeline using a directed acyclic graph (DAG) with specific pipeline parameters, model hyper-parameters, and a processing step that cleans, balances, transforms, and splits our dataset into train, validate, and test datasets. Next, we define a training step that trains a model using the train and validation datasets and a processing step that evaluates the trained model's performance on the test dataset. Also, we define a register model step that creates a model package from the trained model to check the model's performance and conditionally registers the model for deployment.

# Steps to follow:
1. List and access the Reviews dataset files hosted in an S3 bucket
2. Install and import AWS Data Wrangler
3. Create an AWS Glue Catalog database and list all Glue Catalog databases
4. Register dataset files with the AWS Glue Catalog
5. Write SQL queries to answer specific questions on your dataset and run your queries with Amazon Athena
6. Return the query results in a pandas data frame
7. Produce and select different plots and visualizations that address your questions



