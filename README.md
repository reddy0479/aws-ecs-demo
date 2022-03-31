A sample repo for storing a docker image. 
This repo is integrated with AWS Codebuild service such that whenever there is a commit to this repo it will trigger a codebuild that will build a docker image which gets pushed to AWS ECR registry.   
This latest built image will get tested in ECS cluster
