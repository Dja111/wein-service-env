# wein-service-env

This repository contains the environment configuration for the service: wein-service

## Description

This repository provides the Helm chart configuration required for deploying the wein-service

## Purpose

This project demonstrates that the application's configuration can be automatically updated through Continuous Integration (CI). Once the update is complete, ArgoCD detects the changes and deploys the new application version seamlessly.

For environments like Development, Production, and QA, we can also utilize Kustomize. However, this will be implemented later.

## Tools and Technologies

- Helm as the package manager for Kubernetes.

- Kustomize(planned): To customize configurations for multiple environments.

## Maintainer
This project is maintains by Jospin Aurèle Donfack

## Contact
aurel.donfak@gmail.com
