# GitHub Actions Deep Dive

A simple Lambda function that can be deployed via a GitHub Actions Workflow. 

In AWS, need to:
* Create an S3 bucket
* Create a Lambda function with Python 3.13 runtime 
* Create a role for the lambda (name my-lambda-role)
* Create a cli user with access keys, with permissions to:
** S3
** Lambda
* Update the actions secrets to store the access keys and AWS account ID.

For the documentation, go to the repository settings, pages, select the new branch created by the job called "gh-pages", folder is root and click on Save. It will take a few minutes and eventually there will be a banner with the link of the site