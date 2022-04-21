# Step by Step

- Go to AWS and create a AWS Lambda Function
- On AWS IAM portal, create an access key for the github. Save both public and private key.
- Create a github repo
- In your repo, click on settings -> secrets -> Action Secrets. Deploy both secrets under the key names: "AWS_ACCESS_KEY_ID" and "AWS_SECRET_ACCESS_KEY"
- Once again on github, go to Actions, select "Set up a workflow yourself" (A main.yml file will be created on .github/workflow/)
- Replace the code of the main.yml for the one on this repository (adapt the values "function_name" and "aws_region" to your desire)

**Pipeline should be created by now!**
