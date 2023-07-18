# [5dpo_drivers_interfaces](https://github.com/5dpo/5dpo_drivers_interfaces)

This repository contains the ROS interfaces (actions, messages, services)
required to communicate with the robot drivers of the 5dpo Robotics Team.

## ROS

**foxy**

- [Ubuntu 20.04.6 LTS](https://releases.ubuntu.com/focal/)
- [ROS 2 Foxy](https://docs.ros.org/en/foxy/)

## Usage

### Compilation

```sh
# ROS 2
source /opt/ros/foxy/setup.bash

# Create workspace
mkdir -p ~/ros2_ws/src

# Clone the repository
cd ~/ros2_ws/src
git clone git@github.com:5dpo/5dpo_drivers_interfaces.git

# Build
colcon build
source install/setup.bash
```

## Acknowledges

- [Faculty of Engineering, University of Porto (FEUP)](https://sigarra.up.pt/feup/en/)
- [INESC TEC - Institute for Systems and Computer Engineering, Technology and Science](https://www.inesctec.pt/en/)

## Contacts

If you have any questions or you want to know more about this work, please
contact any member of the 5dpo Robotics Team.
