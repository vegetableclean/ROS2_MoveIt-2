# 🤖 Robot Arm Learning with ROS 2, MoveIt 2, and Imitation Learning


[ Isaac Sim ](https://www.youtube.com/watch?v=-7Lyu4t30uA)

This repository documents my learning and research journey combining **ROS 2**, **MoveIt 2**, and **Imitation Learning**.  
The goal is to understand how to model, configure, and control a robot arm using MoveIt 2 for motion planning — and explore how **learning from demonstrations (LfD)** can enable more adaptive robotic manipulation.

---

## 📚 References & Learning Resources

### 🎥 Main Tutorials

#### 🦾 MoveIt 2
**[ROS 2 MoveIt 2 [1H Crash Course]](https://www.youtube.com/watch?v=-xDyxxRiW7M&t=701s)** by *Robotics Backend*  
Learn how to create a robot arm, set up URDF files, and configure MoveIt 2 for motion planning.

#### 🧠 Imitation Learning
**[Imitation Learning for Robotics (Hands-on Guide)](https://www.youtube.com/watch?v=rl_ozvqQUU8)**  
Covers the fundamentals of **behavior cloning** and **learning from demonstrations**, applied to robotic tasks.

### 🧭 Extended Course
**[Complete MoveIt 2 Course](https://rbcknd.com/moveit2)**  

### 💾 Starting Code
👉 [Google Drive link (base project files)](https://drive.google.com/file/d/1i2TB...)  

---

## ⏱️ MoveIt 2 Course Timeline

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

### 🦾 ROS 2 + MoveIt 2
- Setting up **ROS 2 and MoveIt 2** environments  
- Understanding and modifying **URDF** (Unified Robot Description Format) files  
- Adding **collision and visual elements** to robot models  
- Using the **MoveIt Setup Assistant** for configuration  
- Running **MoveIt demos** for testing robot motion  
- Understanding configuration files and motion planning pipelines  

### 🧠 Imitation Learning
- Concept of **Learning from Demonstration (LfD)**  
- Basics of **Behavior Cloning** using supervised learning  
- Understanding **state-action mapping** from human or simulated data  
- Potential integration of MoveIt 2 for motion execution of learned policies  

---

## ⚙️ Environment

- **OS:** Ubuntu 22.04 LTS  
- **ROS 2 Distribution:** Humble Hawksbill  
- **MoveIt 2 Version:** Compatible with ROS 2 Humble  
- **Dependencies:**  
  - `ros-humble-desktop-full`  
  - `ros-humble-moveit`  
  - `rviz2`, `gazebo` *(optional for visualization and simulation)*  
  - `python3-ml-libraries` *(for imitation learning experiments)*

---

## 🚀 To Run

```bash
# Source ROS 2 and workspace
source /opt/ros/humble/setup.bash
source ~/ros2_ws/install/setup.bash

# Launch MoveIt demo
ros2 launch <your_moveit_package> demo.launch.py
