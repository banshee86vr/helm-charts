# Helm Chart Repository

Welcome to the Helm Chart repository for banshee86vr!

## Overview

This repository hosts Helm charts for deploying banshee86vr on Kubernetes clusters. Helm is a package manager for Kubernetes that enables easy installation, management, and upgrading of Kubernetes applications.

## Adding the Helm Chart Repository Locally

To add this Helm chart repository to your local Helm CLI, follow these steps:

1. Open a terminal window.

2. Use the `helm repo add` command to add the Helm chart repository.

   ```sh
   helm repo add banshee86vr-helm-charts https://banshee86vr.github.io/helm-charts
   helm repo update
   ```

3. Once added, you can search for charts from this repository using the `helm search repo` command.

   ```sh
   helm search repo banshee86vr-helm-charts
   ```

4. You can now install charts from this repository using the `helm install` command.

## Contributing

We welcome contributions from the community! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.