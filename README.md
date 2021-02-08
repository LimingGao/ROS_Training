# ROS_Training
This is repo for basic ROS training

## Ubuntu install of ROS Melodic
 Recommended for Ubuntu 18.04
 Installation tutorial: http://wiki.ros.org/melodic/Installation/Ubuntu
 Commands to install summary: 
 1. sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
 2. sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
 3. sudo apt update
 4. sudo apt install ros-melodic-desktop-full
 5. echo "source /opt/ros/melodic/setup.bash" >> ~/.bashrc
    source ~/.bashrc
 6. (optional) sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential

## Tutorials
If you are new to Linux: You may find it helpful to first do a quick tutorial on common command line tools for linux. A good one is [here](http://www.ee.surrey.ac.uk/Teaching/Unix/). 
### ROS files structures
 Workspace, packages strutures, see lab 01 document
### ROS communication
 Master, Node, Topic, Message, see lab 01 document
