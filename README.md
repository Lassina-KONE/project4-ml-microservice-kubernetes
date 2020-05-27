#  Operationalize a Machine Learning Microservice API
[![Lassina-KONE](https://circleci.com/gh/Lassina-KONE/project4-ml-microservice-kubernetes.svg?style=svg)](https://circleci.com/gh/Lassina-KONE/project4-ml-microservice-kubernetes)

## Summary
####  Machine Learning Microservice API
Operationalizing microservices by deploying a machine learning inference API using docker and kubernetes.

##### Run python scripts and web app

To run the python script do `python3 app.py` or `./app.py`
But you can run as follow:
1. run `run_docker.sh`
or
2. run `run_kubernetes.sh`
and
3. run `make_prediction.sh` to get response from the app.
---
### Project files

- `run_docker.sh` : Build the docker image from the Dockerfile
- `make_prediction.sh` : Make a prediction
- `upload_docker.sh` : Upload your Docker image to **Docker Hub**
- `run_kubernetes.sh` : Deploy the application on the Kubernetes cluster
