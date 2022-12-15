# Terraform Localstack Playground

Environment for testing your Terraform scripts on Localstack for AWS.

## Prerequisites

* Docker
* Terraform

## Getting started

1. Run the Localstack container:

    ```(bash)
    docker compose up -d
    ```

2. Initialize a working Terraform directory

    ```(bash)
    terraform init
    ```

3. You are good to go and can start testing your scripts!
