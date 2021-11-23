# Multi-Container App on Kubernetes
This repository explores how to make a Multi container deployment on kubernetes cluster using full stack Application.

## Big Picture
Application Stack
 | React| Node.js | Postgres | Ingress Nginx | step by step

## Architecture
 A diagram shows graphical description of whole project structure.

## Instructions
`
1. It contains React client, Node.js backend, PostgreSQL and Nginx
2. You should install Ingress Nginx with the command:
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.46.0/deploy/static/provider/cloud/deploy.yaml
3. After that you can use the following command to start in main folder:
4. kubectl apply -f k8s
, .