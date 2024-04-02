
---

# GazeBo

This repository provides instructions on how to run Gazebo

## Requirement

You need to be on Ubuntu version 20.04 with ROS already installed.

## Creating Catkin Workspace

In your terminal:

```bash
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws
catkin_make
```

```bash
source devel/setup.bash
```

## Usage

To use the package, clone this repository into the `src` folder of your catkin workspace:

```bash
cd ~/catkin_ws/src
git clone https://github.com/KiengYang/Turtlebot-Publish-Subscriber.git
```

## Running the Turtlesim

Open a terminal and run:

```bash
roscore
```

```bash
roslaunch smb_gazebo hw_gazebo.launch
```
