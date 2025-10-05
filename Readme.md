# 🤖 Robot Arm Learning with ROS 2 & MoveIt 2

This repository documents my learning journey with **ROS 2** and **MoveIt 2**, following the *“ROS 2 MoveIt 2 [1-Hour Crash Course]”* tutorial.  
The goal is to understand how to model, configure, and control a robot arm using MoveIt 2 for motion planning and manipulation.

---

## 📚 References & Learning Resources

### 🎥 Main Tutorial Video  
**[ROS 2 MoveIt 2 [1H Crash Course]](https://www.youtube.com/watch?v=-xDyxxRiW7M&t=701s)** by *Robotics Backend*  

### 🧭 Full Course  
**[Complete MoveIt 2 Course](https://rbcknd.com/moveit2)**  

### 💾 Starting Code  
You can download the base files used in this tutorial here:  
👉 [Google Drive link](https://drive.google.com/file/d/1i2TB...)  

---

## ⏱️ Course Timeline (Chapters)

| Time | Topic |
|------|-------|
| 0:00:00 | Intro |
| 0:01:43 | Install and set up MoveIt 2 |
| 0:04:32 | The URDF we will use |
| 0:14:17 | Add collision tags in the URDF |
| 0:27:17 | Configure the arm with the MoveIt Setup Assistant |
| 0:43:06 | Files explanation |
| 0:50:33 | Test the arm with the MoveIt demo launch file |
| 1:01:40 | How to go further with MoveIt 2 |

---

## 🧠 What I’ve Learned

- Setting up **ROS 2 and MoveIt 2** environments  
- Understanding and modifying **URDF** (Unified Robot Description Format) files  
- Adding **collision and visual elements** to robot models  
- Using the **MoveIt Setup Assistant** to configure motion planning  
- Launching **MoveIt demos** for testing robot movement  
- Basic structure and roles of configuration files in a MoveIt 2 package  

---

## ⚙️ Environment

- **OS:** Ubuntu 22.04 LTS  
- **ROS 2 Distribution:** Humble Hawksbill  
- **MoveIt 2 Version:** Compatible with ROS 2 Humble  
- **Dependencies:**  
  - `ros-humble-desktop-full`  
  - `ros-humble-moveit`  
  - `rviz2`, `gazebo` *(optional for visualization and simulation)*

---

## 🚀 To Run

```bash
# Source ROS 2 and workspace
source /opt/ros/humble/setup.bash
source ~/ros2_ws/install/setup.bash

# Launch MoveIt demo
ros2 launch <your_moveit_package> demo.launch.py
