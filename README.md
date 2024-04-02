
---

# Turtlesim Circle Drawing

This repository provides instructions on how to run the Turtlesim simulation and make it draw a circle.

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

To use the `my_robot_controller` package, clone this repository into the `src` folder of your catkin workspace:

```bash
cd ~/catkin_ws/src
git clone https://github.com/KiengYang/Turtlebot-Publish-Subscriber.git
```

Then build the workspace with `catkin_make` and source the new package:

```bash
cd ~/catkin_ws
catkin_make
```

```bash
source devel/setup.bash
```


## Running the Turtlesim

Open a terminal and run:

```bash
roscore
```

```bash
rosrun turtlesim turtlesim_node
```

```bash
rosrun my_robot_controller circle.py
```

You should now see the turtle drawing a circle.

---

