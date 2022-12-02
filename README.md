# ROS_Training
This is a repo for basic ROS training.

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
[ROS wiki Tutorial](http://wiki.ros.org/ROS/Tutorials)
### ROS files structures
 Workspace, packages strutures, see lab 01 document
 Create a Workspace and package.
 Install package from ROS. For example: sudo apt install ros-melodic-calibration-msgs
 Clone and complie source code package from git.(using packprofile to refresh hte path)
### ROS communication
 Master, Node, Topic, Message,Servers, see lab 01 document
 Run a ROS node using python command to demonstrate the communication.
 commonly used command for topics and node.
### Writing a Simple Publisher and Subscriber
 Using Python or C++, see lab 01 and lab02 document
 How to create a customer msg, see lab02 document

### Writing a Simple Simple Service and Client
 Using Python or C++, see lab 01 and lab03 document
 Note: ##change mode, change access permission "chmod +x xxx.py"
 How to create a customer srv, see lab03 document

### Lanuch file
 Lanuch several nodes and setup some parameters. see lab 01 document

### ROS bag file
 record and play data, tutorial 17 and 18 at http://wiki.ros.org/ROS/Tutorials

### ROS class function
see lab 06 document
This is a technique often used in real life robotic systems because it is very convenient to group similar tasks in the same class. For example, you would want to group any ‘Kinematics’ related methods and functions together in the same class, any ‘Computer Vision’ algorithms in a separate class and so on. This approach is much more organised than just creating a different package for every different little task you want to do on your robot
 If you are using Python, the package structure must follow these rules:
1.The ‘[class_def].py’ file must be in ‘catkin_ws/src/[pkg_name]/src/[pkg_name]/[class_def].py’
2.We must create a blank python file called ‘__init__.py’ in the same folder
3.We have to uncomment the ‘catkin_python_setup()’ command in ‘CMakeLists.txt’
4.We must create a python file called ‘setup.py’ in the same directory as ‘CMakeLists.txt’.


test pull request


This is Liming Client. I created a branch-client-1 branch. 

test local branch 

Ok, THanks for your commnets. I will learn the PR process more. 

Add something on the remote branch

 Add more something on the remote branch



