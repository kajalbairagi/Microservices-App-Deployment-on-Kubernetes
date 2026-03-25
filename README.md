\# Kubernetes Microservices Project 



\##  Overview

This project demonstrates deployment of a microservices application using Kubernetes.



\##  Architecture

Frontend → Backend → API Communication



\##  Tech Stack

\- Docker

\- Kubernetes (Minikube)

\- Node.js

\- Nginx



\##  Features

\- Multi-container deployment

\- Kubernetes Deployments \& Services

\- Service communication

\- NodePort exposure



\##  Steps to Run



1\. Start Minikube



minikube start





2\. Build Images



docker build -t backend-app ./backend

docker build -t frontend-app ./frontend





3\. Deploy to Kubernetes



kubectl apply -f k8s/





4\. Access App



minikube service frontend-service





\##  Output

Frontend calls backend API successfully.



\##  Author

Kajal Bairagi

