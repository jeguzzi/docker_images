# This is an auto generated Dockerfile for ros:jade-ros-base
# generated from templates/docker_images/create_ros_image.Dockerfile.em
# generated on 2015-06-10 19:52:57 -0700
FROM ros:jade-ros-core
MAINTAINER Dirk Thomas dthomas+buildfarm@osrfoundation.org

# install ros packages
RUN apt-get update && apt-get install -y \
    ros-jade-ros-base=1.2.0-0* \
    && rm -rf /var/lib/apt/lists/*

