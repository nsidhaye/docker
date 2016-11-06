msphpsql docker
=====================
[![Docker Pulls](https://img.shields.io/badge/docker%20pulls-10-blue.svg?maxAge=2592000)](https://hub.docker.com/r/nsidhaye/msphpsql-dev/)

**How to run this docker.**

	docker run -it  nsidhaye/msphpsql bash
    docker run -it  nsidhaye/msphpsql-dev bash

With attached your local directory to the docker.

	docker run --rm -it -v {Your_DIR_PATH}:/data  nsidhaye/msphpsql bash
    docker run --rm -it -v {Your_DIR_PATH}:/data  nsidhaye/msphpsql-dev bash

Example: 

	docker run --rm -it -v C:/opt/Docker:/data  nsidhaye/msphpsql bash
    docker run --rm -it -v C:/opt/Docker:/data  nsidhaye/msphpsql-dev bash

####**Details:**

ID | Type | Tags | Dockerfile
--- | --- | --- | ---
1.0|msphpsql-dev|0.1.0| https://github.com/nsidhaye/docker/blob/master/msphpsql/Dockerfile-msphpsql-dev
2.0|msphpsql-dev|| https://github.com/nsidhaye/docker/blob/master/msphpsql/Dockerfile-msphpsql
