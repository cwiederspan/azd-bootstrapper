# Azure Dev CLI Bootstrapper

A template repository for bootstrapping Azure Developer CLI projects using GitHub Codespaces.

## Getting Started

```bash

# Log in to azd. Only required once per-install.
azd auth login

# Find a template
azd template list

# First-time project setup. Initialize a project in the current directory, using this template. 
azd init --template Azure-Samples/todo-nodejs-mongo-aca

# Provision and deploy to Azure
azd up

```