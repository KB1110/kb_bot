# kb_bot

A ROS2-based two-wheeled differential drive robot with Lidar integration.

## Features
- Two-wheeled differential drive robot model
- Gazebo simulation integration
- Teleoperation control using keyboard (W, A, S, D)

## System Requirements
- ROS2 Jazzy
- Gazebo Harmonic

## Usage
1. Launch the Gazebo simulation:
```bash
ros2 launch kb_bot_bringup kb_bot_gazebo.launch.py
```

2. Start teleoperation:
```bash
ros2 run kb_bot_teleop kb_bot_teleop_node
```