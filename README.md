# Kubernetes Practice

For now using application found in my [fib-docker repo](https://github.com/lukeschuyler/fib-docker).

## Local Setup

To run this application, you must have [minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/) & [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) installed.

- Install dependencies inside the client, server, and worker directories by running `npm install`   inside EACH directory.

- Initialize minikube with 
    `minikube start`

- From inside of the root directory, run:
    `kubectl apply -f k8s`

- Get minkube IP with:
    `minikube ip`

- Go to http://<YOUR_MINIKUBE_IP>:31515/ in your browser
