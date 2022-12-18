
### Summary 
This sample is from kodecloud tutorial and the architecture diagram can be seen below:
![architecture](../references/voting-app-architecture.png)

To create the pods and service 
`kubectl create -f redis-deploy.yaml`
`kubectl create -f redis-service.yaml`

`kubectl create -f postgres-deploy.yaml`
`kubectl create -f postgres-service.yaml`

`kubectl create -f voting-app-deploy.yaml`
`kubectl create -f voting-app-service.yaml`

`kubectl create -f result-app-deploy.yaml`
`kubectl create -f result-app-service.yaml`

`kubectl create -f worker-app-deploy.yaml`
`kubectl create -f worker-app-service.yaml`

To see the url to access
`minikube service voting-service --url`
`minikube service result-service --url`


