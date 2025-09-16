

# TF 

### installations 
``` bash 
   # For core TF libraries
    sudo apt install ros-${ROS_DISTRO}-tf2-ros \
        ros-${ROS_DISTRO}-tf2-tools \
        ros-${ROS_DISTRO}-tf-transformations \
        ros-${ROS_DISTRO}-tf2-msgs \
        ros-${ROS_DISTRO}-tf2-geometry-msgs
```
### commands debug tf
``` bash  
    ros2 run tf2_tools view_frames
    ros2 run tf2_ros tf2_echo <source_frame> <target_frame>
    ros2 topic list | grep tf
```

