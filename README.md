# Terraform-Remote-State

In this project we are doing to explore the importance of using terraform Remote State by creating an AWS Dynamodb table to collect the Tf.state file and later saving the State file in an S3 bucket. This is important because it prevent multiple people from doing changes on the same terraform repo by locking the state file when a change a about to be made by one person. Using S3 buckets to remotely safe the state file also serves as a backup in case the local state file is damaged. Using the remote location also make is possible for team collaboration. 
