# KubernetsSimpleApplication
This project demonstrates the orchestration of a full-stack application environment using Kubernetes.

Technical Implementation

    Cluster Management: Local cluster provisioning using Minikube.

    Workload Orchestration: YAML-based deployments for both the application and the database.

    Networking: Exposing the application via NodePort and securing internal database traffic via ClusterIP.

    Storage: Decoupled storage logic using PersistentVolumeClaims to handle database state.

    CLI Mastery: Managed entirely via kubectl for resource creation, debugging, and log monitoring.
