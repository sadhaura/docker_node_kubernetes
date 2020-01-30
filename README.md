                                  Node App built with Docker Compose and kubernetes

For Docker:-

Enviroments:-
. node 10


Installation:-
Clone this repository on your local computer. 


1. git clone https://github.com/sadhaura/docker_node_kubernetes.git
2. cd docker_node_kubernetes

3. docker-compose up -d

Your Node App is now ready!! You can access it via http://localhost:49162.

For Kubernetes:-

1.Clone the repository on kubernetes cluster.

git clone https://github.com/sadhaura/docker_node_kubernetes.git

2.cd docker_node_kubernetes/kubernetes

3.run the below command

kubectl create -f apache.yml


