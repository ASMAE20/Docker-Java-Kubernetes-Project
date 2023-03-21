# Docker-Java-Kubernetes-Project
Sample java microservice

In this devops project we learn how to build java applications using open-source build tool Maven with this commande 

``````
mvn clean install 
``````

This command aims to create the snapshot file to use it in DockerFile

Then we create images for all microservices using this command 

``````
docker build -t asmaeel/imageproduct:latest .
``````
Then we push it to docker hub using 

``````
docker push asmaeel/imageshop
``````

And finally, after we create all the YAML files needed, we deploy our Java microservices application on K8s using this command.

``````
kubectl apply -f imageproduct-service.yaml
``````

Credit: https://github.com/danielbryantuk/oreilly-docker-java-shopping/

By ASMAE ELAZRAK 


