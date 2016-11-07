msphpsql docker
=====================
[![Docker Pulls](https://img.shields.io/badge/docker%20pulls-20-blue.svg?maxAge=2592000)](https://hub.docker.com/r/nsidhaye/msphpsql-dev/)

**How to run this docker.**

	docker run -it  nsidhaye/msphpsql
    docker run -it  nsidhaye/msphpsql-dev bash

With attached your local directory to the docker with configured port.

	docker run --rm -it -v {Your_DIR_PATH}:/data  nsidhaye/msphpsql
    docker run --rm -it -v {Your_DIR_PATH}:/data  nsidhaye/msphpsql-dev bash
	
	docker run -d -v {Your_DIR_PATH}:/data -p {Your_IP}:{Your_desired_port}:80  nsidhaye/msphpsql

Example: 

	docker run --rm -it -v C:/opt/Docker:/data  nsidhaye/msphpsql
    docker run --rm -it -v C:/opt/Docker:/data  nsidhaye/msphpsql-dev bash
	
	docker run -d -v C:/opt/Docker:/data -p 127.0.0.1:8080:80  nsidhaye/msphpsql
	
Validating: You can validate msphpsql libs status by visiting http://[Your_IP]:[docker_configured_port]/phpinfo.php

####**Details:**

ID | Type | Tags | Dockerfile | Docker Build Status
--- | --- | --- | --- | ---
1.0|msphpsql-dev|0.1.0| https://github.com/nsidhaye/docker/blob/master/msphpsql/Dockerfile-msphpsql-dev | [![Docker Build](https://img.shields.io/badge/Build-Passing-green.svg?maxAge=2592000)](https://hub.docker.com/r/nsidhaye/msphpsql-dev/)
2.0|msphpsql|| https://github.com/nsidhaye/docker/blob/master/msphpsql/Dockerfile-msphpsql | [![Docker Build](https://img.shields.io/badge/Build-Passing-green.svg?maxAge=2592000)](https://hub.docker.com/r/nsidhaye/msphpsql/)

