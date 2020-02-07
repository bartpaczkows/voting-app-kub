# voting-app-kub
Microservices appliaction on Kubernetes

This is example of Apllication on Kubernetes.

To deploy it you need to create all object defined in yml files,
for example:
kubectl create -f voting-app-pod.yml
kubectl create -f voting-app-service.yml
...
...


The project has two separete web application: voting-app and result-app
To access them enter
<IP of any of the Kuberentes nodes>:30008    (voting-app)
<IP of any of the Kuberentes nodes>:30009    (result-app)
  
For example:
http://192.168.50.10:30008/
http://192.168.50.10:30009/
