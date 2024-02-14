# Scalable-Node.js-App-on-AWS-through-IaC
# Submodules Repository

This repository contains submodules for the following three repositories related to cloud infrastructure deployment and a web application:

1. [AWS and Google Cloud Infrastructure Deployment](https://github.com/CSYE-6225-Anshul/iac-pulumi)
2. [WebApp](https://github.com/CSYE-6225-Anshul/webapp)
3. [Lambda Function for GitHub Repo Processing](https://github.com/CSYE-6225-Anshul/serverless)

## Table of Contents

- [Scalable-Node.js-App-on-AWS-through-IaC](#scalable-nodejs-app-on-aws-through-iac)
- [Submodules Repository](#submodules-repository)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Cloning the Repository](#cloning-the-repository)
  - [Cloning the Repository](#cloning-the-repository-1)
  - [Initializing Submodules](#initializing-submodules)
  - [Updating Submodules](#updating-submodules)
  - [Contributing](#contributing)

## Introduction

This repository contains submodules for the AWS and Google Cloud Infrastructure Deployment and WebApp repositories. Submodules allow for managing external repositories within this repository, enabling easy integration and deployment of multiple components.

## Cloning the Repository

To clone this repository and its submodules, use the following command:

```bash
git clone --recursive <repository-url>
```

## Cloning the Repository

If the repository was already cloned without the `--recursive` option, use the following commands to initialize and update the submodules:

```bash
git submodule init
git submodule update
```

##  Initializing Submodules
If you have already cloned the repository but haven't initialized the submodules, run the following commands:

```
git submodule init
git submodule update
```

##  Updating Submodules
To update the submodules to the latest commit from their respective repositories, use the following command:

```
git submodule update --recursive --remote
```

## Contributing

If you want to contribute to any of the submodules, please refer to the respective repository's contribution guidelines:

1. [AWS and Google Cloud Infrastructure Deployment](https://github.com/CSYE-6225-Anshul/iac-pulumi)
2. [WebApp](https://github.com/CSYE-6225-Anshul/webapp)
3. [Lambda Function for GitHub Repo Processing](https://github.com/CSYE-6225-Anshul/serverless)