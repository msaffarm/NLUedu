## Overview of Dockerfiles

### Building Images
```bash
docker build -t <your_image_tag> -f <path_to_dockerfile> .
```

Alternatively you can pull the images from my Dockerhub using the links provided in the dockerfiles.
```
docker pull <image_name>:<image_tag>
```

## NLU Base Image
[![](https://images.microbadger.com/badges/image/msaffarm/rasa_nlu.svg)](https://microbadger.com/images/msaffarm/rasa_nlu "Deep enough ?!")
[![](https://images.microbadger.com/badges/version/msaffarm/rasa_nlu.svg)](https://microbadger.com/images/msaffarm/rasa_nlu "We'll keep it updated!")

Base image which contains the minimal requirements for running the experiments. Note that this image does not support experiments which use deep learning libraries. Here on notes on how to use it.

```bash
docker run -idt --name <your_container_name> -p 8888:8888 -p 8889:8889 -p 5000:5000 -v "$PWD":/home/jovyan/work <docker_image_name>:<docker_image_tag>
```


## NLU Full Image
[![](https://images.microbadger.com/badges/image/msaffarm/rasa_nlu.svg)](https://microbadger.com/images/msaffarm/rasa_nlu "Deep enough ?!")
[![](https://images.microbadger.com/badges/version/msaffarm/rasa_nlu.svg)](https://microbadger.com/images/msaffarm/rasa_nlu "We'll keep it updated!")

This images contains all the necessary libraries for running the experiments. Note that this image does not support experiments which use deep learning libraries. Here on notes on how to use it.

```bash
docker run -idt --name <your_container_name> -p 8888:8888 -p 8889:8889 -p 5000:5000 -v "$PWD":/home/jovyan/work <docker_image_name>:<docker_image_tag>
```