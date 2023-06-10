# AWS-File.hosting (CI/CD)

- Clone repostory.
- push it to AWS Codecommit
- Setup ECR Repository, Copy the URL,paste it in buildspec file after (REPOSIRTORY_URL=)
- Setup AWS Codebuild (Codebuild is going to use the buildspec file as an instruction on what to do)
- Setup ECS Cluster
- Setup AWS Pipline (which is going to deploy the application to ECS cluster)
