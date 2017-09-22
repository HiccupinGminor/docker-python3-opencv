[![Docker Automated buil](https://img.shields.io/docker/automated/jjanzic/docker-python3-opencv.svg)]()

Docker image with python 3.6, opencv 3.3, and Jupyter

Usage:

To run bash shell within existing docker image:      
    
    docker run -it --entrypoint /bin/bash -p 8888:8888 python3-opencv-jupyter

From within the docker container run:     
    
    jupyter notebook --ip=0.0.0.0 --allow-root --no-browser

From your host machine, visit localhost:8888



Image tagged with `:contrib` contains docker image built with [contrib modules](https://github.com/opencv/opencv_contrib/)

List of available docker tags:

- `opencv-3.3.0` (`latest`)
- `contrib-opencv-3.3.0` (`contrib`)
- `opencv-3.2.0`
- `contrib-opencv-3.2.0`
