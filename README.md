# Devops Tools
List of awesome devops tools that will be useful for your daily work!

# Tools

## Infrastructure as code (IaC)
This tools allow the manage of infrastructure using code.

| Tool | Description | Stars
|:---|:---|:---
| [Terraform](https://github.com/hashicorp/terraform) | One of the most used IaC tool in the market. Has integration with multiple cloud providers and multiple services as databases or monitors as Pingdom. You can write terraform code using their own syntax called [HCL](https://www.terraform.io/language/syntax/configuration) or using their [CDK](https://www.terraform.io/cdktf) and your prefered programming language. | ![Terraform](https://img.shields.io/github/stars/hashicorp/terraform?style=for-the-badge)
| [Pulumi](https://github.com/pulumi/pulumi) | The main feature of Pulumi is allow the possibility of create infrastructure using your favorite language in a simple way. | ![Pulumi](https://img.shields.io/github/stars/pulumi/pulumi?style=for-the-badge)
| [Crossplane](https://github.com/crossplane/crossplane) | Allow the deployment of infrastructure in Cloud Providers as AWS, Google Cloud or Azure using your own Kubernetes Cluster. | ![Crossplane](https://img.shields.io/github/stars/crossplane/crossplane?style=for-the-badge)
| [CloudFormation](https://aws.amazon.com/es/cloudformation/) | Recommended tool if you will only deploy services to AWS. Has integration with all their services and is managed entirely by AWS. | Non available
| [Bicep](https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview?tabs=bicep) | Recommended tool if you will only deploy services to Azure. Has integration with all their services and is managed entirely by Azure. | Non available

# Containers
This tools enables the possibility to package an application in a container.

| Tool | Description | Stars
|:---|:---|:---
| [Docker](https://docs.docker.com/get-started/overview/) | Is the **game-changer** of this era. Enables you to separate your applications from your infrastructure allowing the developers to test their application faster. | Non available
| [Docker Buildx](https://docs.docker.com/buildx/working-with-buildx/) | Is the evolution of the Docker CLI, integrates new features as build images for other platforms (For example build an `arm64` image from a Windows computer) or mount secrets when you build an image in a safe way([Example](https://docs.docker.com/develop/develop-images/build_enhancements/#new-docker-build-secret-information)) | Non available
| [Podman](https://github.com/containers/podman) | Allow the creation of a POD(subset of containers) in your local environment. Is a good alternative to Docker if this feature is important to you. | ![Podman](https://img.shields.io/github/stars/containers/podman?style=for-the-badge)
| [Kaniko](https://github.com/GoogleContainerTools/kaniko) | Designed by Google, allows the **build and push** of Docker images (you cannot run it) using a Kubernetes cluster without higher privileges. It´s very fast and cache all the layers in the container registry that executes a `RUN` or a `COPY` command. Recommended for production environments. | ![Kaniko](https://img.shields.io/github/stars/GoogleContainerTools/kaniko?style=for-the-badge)









# Contributing
Feel free to open a pull request in case you want to add an awesome tool!
