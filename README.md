# ROS-and-Gazebo

## install

### 1. Setup your sources.list
```sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'```

### 2. Set up your keys
```sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 421C365BD9FF1F717815A3895523BAEEB01FA116```

### 3. Make sure your package index is up-to-date
```sudo apt-get update```

### 4. Install ros Desktop-Full package
```sudo apt-get install ros-kinetic-desktop-full```

### 5. Initialize rosdep
```sudo rosdep init```

```rosdep update```

### 6. Environment setup
```echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc```

```source ~/.bashrc```



http://wiki.ros.org/kinetic/Installation/Ubuntu

https://charlyhuangrostutorial.wordpress.com/2015/

## catkin work space

```mkdir -p ~/catkin_ws/src```

```cd ~/catkin_ws/```

```catkin_make```

```source devel/setup.bash```

http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment
http://wiki.ros.org/catkin/Tutorials/using_a_workspace

## launch file
http://gazebosim.org/tutorials?tut=ros_roslaunch

https://blog.techbridge.cc/2016/09/28/ros-collision-avoiding-robot/
