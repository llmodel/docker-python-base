# docker-python-base
Base docker container for python development

#### Build the docker image (not the training period, this is REQUIRED! ):
```
docker build -t <image_name> .

Example:
docker build -t python_dev .
```
#### Running the container
```
docker run -it -v <host_directory>:/code <image_name> bash

Example
docker run -it -v /home/user_name/projects/docker/docker-python-base/code:/code python_dev bash
```
