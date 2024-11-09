## Description
This is a ROS Noetic docker image with [libcamera_ros_driver](https://github.com/ctu-mrs/libcamera_ros_driver) installed and set up.
## Getting started
Pull the docker image
```bash
docker pull ghcr.io/raameshb/libcamera-ros-driver
```
Run the docker image
```bash
docker run -it --net host -v /run/udev:/run/udev:ro --privileged ghcr.io/raameshb/libcamera-ros-driver
```
The ros node should start automatically
