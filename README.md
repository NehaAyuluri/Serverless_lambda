# Serverless_lambda


Reproducing serverless dataengineering pipeline using AWS Cloud9

Create a cloud9 environment. 

Create a lambda function with a python file and add admin role while creating the function.

Create an SQS Queue and copy the link in the python file created in lambda function.

Create a table named fang(consisting names of companies) in DynamoDB.

Now we can deploy lambda function and can be checked in AWS Services Lambda. Here we can see the lambda function created in cloud9. 

Create a cloud watch events/event bridge to monitor the success of lambda function.
