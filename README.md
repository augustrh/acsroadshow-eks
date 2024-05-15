CFN for creating an EKS environment quickly. <br>
Uses a Lambda to build the environment from Cloud9 using eksctl.  <br>
You can adjust the eksctl output to do anything you need.  <br>
Also can add CLI to manage entire AWS environment and build more resources as required.  <br>
Also contains ECR steps and info on deploying to it.  <br>
Be mindful of instance sizing if deploying ACS SecuredCluster.  <br>
There is a script, create-c9-env.sh, you need to run (`wget` and `source create-c9-env.sh`) to setup the Cloud9 CLI (or whatever CLI you use, but due to the way EKS is built it's best to do it on the Cloud9 and avoid IAM hell.  <br>
Control EKS version with variable in template.  <br>
