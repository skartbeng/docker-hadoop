# docker-hadoop
# This is a first attempt to create docker image with Ubuntu,Oracle JDK 8 and Hadoop 2.7.0
# forked from sequenceiq images

##To build locally, please follow the steps below.
1. use git to clone this project.
git clone https://github.com/skartbeng/docker-hadoop.git

2. Build the image, change directory to docker-hadoop, and run the following
docker build -t docker-hadoop .

3. Run the docker image
docker run  docker-hadoop

