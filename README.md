# Simple AWS Lambda Express App

A simple demo application using lambda and express.js to implement REST API's


# List of API's

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

|HTTP Method     | Endpoint                      |HTML                     	   |
|----------------|-------------------------------|-----------------------------|
|GET			 |api/info            			 |it will return sample json   |
|POST			 | api/v1/getback           	 |it will getback req.body     |

## Steps to Deploy into AWS
	- Create an AWS account
	- Create IAM user role and download access keys
	- Install AWS SDK in your system
	- Install Serverless framework in your system
	- Configure Access keys in your system using `aws configure`
	- Go to app folder
	- Run `serverless deploy` command in system
	- After deployment, it will provide endpoint and you can test those with relavant api and input.
