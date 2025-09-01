# Bootstrap k8s blue/green envs

This repository was created for a test assignment.

## Overview

The repository is used for bootstrapping Kubernetes environments and configuring general Ingress.  
Main components:
- **`manifest.yaml`** — Kubernetes manifest for deployment and configuration.
- **`.github/workflows/bootstrap-blue-green.yaml`** — GitHub Actions workflow for automating the bootstrap process

## Usage

1. Deploy the environments using the GitHub Actions workflow.
2. Verify that the manifests are successfully applied.
3. Bootstrap general Ingress for blue/green traffic routing.
