# Multi-Container App on Kubernetes
This repository explores how to make a Multi container deployment on kubernetes cluster using full stack Application.

## Big Picture
Application Stack
 | React| Node.js | Postgres | Ingress Nginx | step by step

## Architecture
 A diagram shows graphical description of whole project structure.
 ![multicontainer-kubernetes](https://user-images.githubusercontent.com/21228768/143078225-708fa5c8-ca22-4c53-b67f-4ca9a7aa14f5.png)

## Instructions
`
1. It contains React client, Node.js backend, PostgreSQL and Nginx
2. You should install Ingress Nginx with the command:
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.46.0/deploy/static/provider/cloud/deploy.yaml
3. After that you can use the following command to start in main folder:
4. kubectl apply -f k8s
, .
