# CI-CD_nodeJs
The  task is to write a Dockerfile, build the image, and push it to Azure Container Registry (ACR). As mentioned in the questionnaire, this can be either a .NET or Node.js application.
I chose a basic Node.js application that displays "Hello ABB!" when the web app runs.
For this task, I created a new repository and applied the same branching rules as in the Terraform repository.
•	Created the Dockerfile, Node.js dependency files, deployment.yaml, and service.yaml. and pipeline.yaml
•	The pipeline is designed to:
1.	Check out the repository
2.	Build the Docker image
3.	Push the image to ACR
4.	Deploy the application to AKS
The deployment is deployed into the namespace specified during the pipeline run via a pipeline parameter.
