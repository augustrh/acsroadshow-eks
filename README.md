CFN for creating an EKS environment quickly.
Uses a Lambda to build the environment from Cloud9 using eksctl.
You can adjust the eksctl output to do anything you need.
Also can add CLI to manage entire AWS environment and build more resources as required.
Also contains ECR steps and info on deploying to it.
Be mindful of instance sizing if deploying ACS SecuredCluster.
There is a script, create-c9-env.sh, you need to run (`wget` and `source create-c9-env.sh`) to setup the Cloud9 CLI (or whatever CLI you use, but due to the way EKS is built it's best to do it on the Cloud9 and avoid IAM hell.
