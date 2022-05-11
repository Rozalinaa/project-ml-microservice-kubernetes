[![CircleCI](https://circleci.com/gh/Rozalinaa/project-ml-microservice-kubernetes/tree/main.svg?style=svg)](https://circleci.com/gh/Rozalinaa/project-ml-microservice-kubernetes/tree/main)

# project-ml-microservice-kubernetes
udacity final project repo

# Description
This project is based off of udacitys project https://github.com/udacity/DevOps_Microservices and is the final result of the class.
This microservice is a python application which uses docker and kubernetes to build a project that uses machine learning to predict housing prices in boston.

# Environment
It is recommended to run this in a venv and install the requirements by running "make install"
Please note that it is advised to have the following setup in your environment:
- hadonlint
- minikube 
- docker

# Running the project
You can run the application like this:
./run_docker.sh
./upload_docker.sh
minikube start
./run_kubernetes.sh

you can then use ./make_prediction.sh to make a prediction

# Filestructure
Folder .circleci - config file for running circle ci build
Folder project-ml-microservice-kubernetes contains the app and model data
Folder project-ml-microservice-kubernetes/model_data contains data from kaggel concerning boston housing prices
Folder project-ml-microservice-kubernetes/output_txt_files contains output example files as requested by the assignment
File app.py is the application that needs to be run
File Dockerfile contains instructions for the docker build and exposing the port
File Makefile contains instructions for make rules
File requirements.txt contains the requirements that need to be installed before running the project
The remaining .sh files can be used to run the project as staed above. 




