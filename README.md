# First-Helm-Project

# Helm Charts for MongoDB Deployment

This repository contains Helm charts for deploying MongoDB and Mongo Express client on Kubernetes clusters. Helm is a package manager for Kubernetes that simplifies the process of deploying and managing applications.

## Prerequisites

Before using these Helm charts, ensure you have the following prerequisites installed:

- Kubernetes cluster (local or cloud-based)
- Helm v3.x

## Helm Charts

### 1. MongoDB Chart

The MongoDB chart deploys a scalable MongoDB database on your Kubernetes cluster. It includes configurations for setting up replica sets, persistent volume claims, and other MongoDB-specific settings.

#### Installation

To install MongoDB using Helm, execute the following command:

```
helm install mongodb ./mongodb-chart
```


#### Configuration

You can customize the MongoDB deployment by modifying the values in the `values.yaml` file or by providing your own `values.yaml` file during installation.

### 2. Mongo Express Chart

The Mongo Express chart deploys a web-based MongoDB client that allows you to interact with your MongoDB database through a user-friendly interface. 

#### Installation

To install Mongo Express using Helm, execute the following command:

```
helm install mongo-express ./mongo-express-chart
```

#### Configuration

Similar to the MongoDB chart, you can customize the Mongo Express deployment by modifying the values in the `values.yaml` file or by providing your own `values.yaml` file during installation.
