# next-app-cicd
deployment of next app with Amplify via a gitHub action

## Setup of the project

##### Step 1: Create a repository

##### Step 2: Create an IAM user for your account

For security reason, it is a bad practice to connect and manage your ressources using the root user when an IAM user with restricted permissions can be used. Also, make sure to enable MFA to secure this root user. This is very important to avoid critical security breach.

Steps to create a IAM group, Iam user and attach it to the group
Steps to create identity provider github and give access to the repo through an IAM role 

####### Optimisation: Regarding the IAM roles, it's a better practice to create a group with permission policy and attach a user to this group instead of attaching the permissions directly to the user.

##### Step 2: Save AWS credentials as secrets

polly, step functions, AWS feelings, models AI

##### Step ...: Create the environment of development
