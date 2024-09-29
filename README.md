This repository contains Kubernetes resource definitions and configurations for deploying MySQL InnoDB Cluster using ArgoCD. It includes:

    ✅ **MySQL Operator**: Installation of the MySQL Operator to manage MySQL InnoDB clusters.
    ✅ **Custom Resources**: Definition of the MySQL Cluster, including configurations for a Router and multiple backend instances.
    ✅ **Secrets Management**: Kubernetes Secrets to securely manage sensitive information such as passwords.
    ✅ **Service Definitions**: Kubernetes Services to expose the MySQL Router for external access.

By using this repository with ArgoCD, you can automate the deployment and management of your MySQL InnoDB Cluster in a Kubernetes environment. This setup allows for easy scalability, monitoring, and backup capabilities.
