# MongoDB Service

This repository contains the MongoDB service for a microservices application. The MongoDB service runs a single instance of MongoDB and is used as the primary database to store and manage video files for the application. For more information about the main project, visit [pdf2podcast-microservice](https://github.com/Prosperibe12/pdf2podcast-microservice).

## Installation

To install the MongoDB service, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/mongodb-service.git
    ```
2. Navigate to the project directory:
    ```bash
    cd mongodb-service
    ```

## Usage

Apply the Kubernetes manifests to deploy MongoDB:
Ensure you have a kubernetes cluster running
```bash
kubectl apply -f manifests
```
This will create the following resources:

A Single MongoDB Instance.

A Service to expose MongoDB internally.

A PersistentVolumeClaim (PVC) for data persistence.