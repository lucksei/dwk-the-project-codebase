# DevOps with Kubernetes - Codebase

Configurations repository [here](https://github.com/lucksei/dwk-the-project-configurations)

Code for part "4.10. The project, the grande finale" of the DevOps with Kubernetes course from Helsinki University of Finland. The original repository for the entire course's exercises can be found [here](https://github.com/lucksei/k8s-submissions-chapter2).

This repository contains the code for the todo-app, the todo-backend and the todo-broadcaster components of the project.

- When pushing a commit to main, GitHub Actions will build the docker images, and modify the 'staging' kustomization.yaml files inside the configuration repo.
- When pushing a tagged commit to main, GitHub Actions will build the docker images, and modify the 'production' kustomization.yaml files inside the configuration repo.
