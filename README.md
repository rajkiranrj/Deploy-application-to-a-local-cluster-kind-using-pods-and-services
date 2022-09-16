# Createing K8s cluster, deploy containerized stateless applications using K8s manifests, expose the applications as NodePort services, roll out an updated version of the application

1. Evaluate the applicability of containerization approach and viability of publicly/privately hosted containers orchestration platform for the business needs of the organization.
2. Design, implement and deploy containerized applications to address cost optimization, high availability, and scalability requirements of business applications
3. Evaluate and recommend networking, persistent storage, and IAM (Identity and Access Management) solutions to achieve the desired level of infrastructure and applications security.

# Tools & Services used:
1. Amazon ECR to securely store the container images
2. Cloud 9 IDE or the local environment to develop your application and build container images
3. Amazon EC2 to host the K8s cluster
4. Kind to deploy local K8s cluster
5. Kubectl to communicate with K8s API Server
6. AWS EC2 to host the containerized application
7. AWS IAM to grant EC2 instance an access to Amazon ECR repo
8. Terraform to deploy the infrastructure
