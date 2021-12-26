# DevOps Exercise #1

## Task 
1 Deploy a web application to a cloud provider of your choice. This web application can be something you have written yourself or an open-source project.

2 Deploy the web application as a Docker Container.

3 Deploy the Docker Container using Kubernetes.
4 Any supporting infrastructure should be configured and deployed as code (e.g. Terraform)

5 Bonus points for any build and deployment automation employed in the deployment of the web application.

6 Bonus points for demonstrating the ability to deploy, destroy and re-deploy the web application and any supporting infrastructure.

7 Include all code and artefacts you create to complete this exercise within this repository for review.

## Status

* Automated the EKS cluster creation through Terraform
  - Points Covered - 4
  - Code - https://github.com/vjsairam/infra-exercise-vjsairam/tree/main/terraform-eks-cluster
* Created a nodejs demo app and Dockerized it 
  - Points Covered - 2
  - Code - https://github.com/vjsairam/infra-exercise-vjsairam/blob/main/nodejs-app/Dockerfile
* Created a CodePipeline and deployed the app to EKS 
  - Points Covered - 1, 3, 5, 6
  - Code - https://github.com/vjsairam/infra-exercise-vjsairam/tree/main/nodejs-app
  - High Level Doc - https://github.com/vjsairam/infra-exercise-vjsairam/blob/main/Implementation%20Documentation.pdf
