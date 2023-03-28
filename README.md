# Task-5.-CI-CD-Pipeline
Create a CI-CD pipeline for a sample application using any CI-CD tool of your choice like Jenkins, Azure DevOps, Gitlab, Github Actions, AWS CodePipeline or any other tool of your choice. Include a code build and a docker build step in your pipeline.


1. Install Jenkins on a server or use a Jenkins instance from a cloud provider.
2. Install necessary plugins for building Java applications and integrating with Git repositories.
3. Create a new Jenkins project and link it to your Git repository.
4. Configure the pipeline stages for building, testing, and deploying your application.
5. Add a Docker build step to create a Docker image of your application.
6. Push the Docker image to a Docker registry or a container repository like Docker Hub, Amazon ECR, or Google Container Registry.
7. Deploy the Docker image to a Kubernetes cluster using Kubernetes manifest files or Helm charts.
8. Add notifications and alerts to notify the team about build failures or deployment issues.


This pipeline builds and tests a Java application, creates a Docker image, pushes the Docker image to a registry, and deploys the image to a Kubernetes cluster. It also sends email notifications with test results and build status. You can customize the pipeline stages and notifications to fit your application and team's needs.
