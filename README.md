# Terraform-Remote-State

In this project, we are exploring the importance of using terraform Remote State by creating an AWS Dynamodb table to collect the Tf.lock file and later saving the State file in an S3 bucket. This is important because it prevents multiple people from making changes on the same Terraform repo by locking the state file when a change a about to be made by one person. Using S3 buckets to remotely save the state file also serves as a backup in case the local state file is damaged. Using the remote location also makes is possible for team collaboration. 
