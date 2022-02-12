# ROS IN DOCKER -Pi 

 - [arm64v8 select ros version ](https://hub.docker.com/r/arm64v8/ros/)

 - [arm32v7 select ros version ](https://hub.docker.com/r/arm32v7/ros/)

 supported tags are ros version for example to install ros melodic 
 
 - #### docker pull arm64v8/ros:melodic ###
 once completed 
 - #### docker images
 select repository  name or image id 
 - #### docker run -it image_name/repo_id
check some ros commands
- #### roscore

To setup arm simulator in x86_64 install qemu

- #### sudo apt-get install qemu binfmt-support qemu-user-static
