# multi-docker

In progress: This is a Fibonacci-sequence calculator built with multiple Docker-containers, tested with Github Actions and deployed to AWS. 

A continuous integration workflow for multiple Docker-images.

Purpose of the different services in the docker-compose.yml file:

#NGINX: webserver
#REACT: frontend
#EXPRESS: backend server
*REDIS: in memory-data store for housing temporary or cached values ("calculated values" in this specific application)
*POSTGRES: is used for  storing “values I have seen”

You can take a look over here:
 http://multidocker1-env.eba-kjzrhz3b.us-east-1.elasticbeanstalk.com/


