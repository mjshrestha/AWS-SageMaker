# SageMaker Deployment Project

The notebook and Python files provided here result in a simple web app which performs sentiment analysis on the user input movie reviews predicting them as positive or negative. The model used for classification is trained with processed and tokenized data (using nltk) from [IMDB review dataset](http://ai.stanford.edu/~amaas/data/sentiment/) using Recurrent Neural network in AWS SageMaker and deployed using AWS API Gateway, S3, and AWS Lambda. For sentiment anlaysis, the publicly accessible API and the web page interact through the deployed endpoint.

**Note:** AWS account is required to run the SageMaker Project.ipynb file.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the SetUp instructions on setting up a SageMaker notebook.
