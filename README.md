# Details of the projects:

# Analyze Datasets and Train ML Models using AutoML
1. In this section, we ingest and transform the customer reviews dataset and use AWS data stack services such as AWS Glue and Amazon Athena for ingesting and querying the dataset. Finally we use AWS Data Wrangler to analyze the dataset and plot some visuals extracting insights.
2. Bias can be present in the data before any model training occurs. Inspecting the dataset for bias can help detect collection gaps, inform feature engineering, and understand societal biases the dataset may reflect. In this lab we analyze bias on the dataset, generate and analyze bias report, and prepare the dataset for the model training.
3. Next we use Amazon Sagemaker Autopilot to train a BERT-based natural language processing (NLP) model. The model analyzes customer feedback and classify the messages into positive (1), neutral (0) and negative (-1) sentiment.
4. Then we use SageMaker BlazingText built-in algorithm to predict the sentiment for each customer review.


# Build, Train, and Deploy ML Pipelines using BERT
 
1. In this section, we take the Reviews dataset and prepare it to train a BERT-based natural language processing (NLP) model. The model will be used to classify customer reviews into positive (1), neutral (0) and negative (-1) sentiment. We perform feature enginnering and train the data with BERT. To perform the required feature transformation you will configure an Amazon SageMaker processing job, which will be running a custom Python script.
2. Next,  we train a text classifier using a variant of BERT called RoBERTa - a Robustly Optimized BERT Pretraining Approach - within a PyTorch model ran as a SageMaker Training Job.
3. Furthermore, we define and run a pipeline using a directed acyclic graph (DAG) with specific pipeline parameters and model hyper-parameters and a processing step that cleans, balances, transforms, and splits our dataset into train, validation, and test dataset. Next, we define a training step that trains a model using the train and validation datasets and a processing step that evaluates the trained model's performance on the test dataset. Also, we define a register model step that creates a model package from the trained model to checks the model's performance and conditionally registers the model for deployment.




