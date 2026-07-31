# Instruction

# Operational Setup and Packages Deployment Guide

This manual covers initialization, package compilation, and deployment for the DoB McQueen project, supporting both physical and simulated environments.

---

## System Compatibility Architecture

| Dependency Category | Core Selection Profile | Operational Hardware Target |
| :--- | :--- | :--- |
| **Operating System** | Ubuntu 24.04 LTS (Noble Numbat) | Raspberry Pi 5 Core Compute Unit |
| **ROS2 Distribution** | ROS2 Jazzy Jalisco | Raspberry Pi 5 & Remote Workstation |
| **Simulation Core** | Gazebo Classic 11 / Ignition Gazebo | Separate Host Engineering Machine |

---

##  Base Operating System & ROS2 Initialization

For low-latency performance, install Ubuntu 24.04 LTS on the Raspberry Pi 5, targeting **ROS2 Jazzy Jalisco**.

### System Setup
1.  Flash Ubuntu 24.04 LTS (ARM64) to a microSD card.
2.  Install dependencies:
    ```bash
    sudo apt update && sudo apt install -y python3-pip git-all software-properties-common ros-dev-tools ros-jazzy-desktop python3-colcon-common-extensions python3-rosdep
    ```
3.  Initialize ROS2 and environmental variables (refer to full documentation for specific `locale` and `bashrc` commands).

---

##  Simulation & Repository Setup

> **Note:** Run intensive simulations on a separate, high-performance workstation using ROS2 Humble.

1.  **Clone Repository:**
    ```bash
    git clone https://github.com
    cd DoB-Mcqueen_WRO-2026
    ```
2.  **Build Workspace:**
    ```bash
    pip3 install -r requirements.txt --break-system-packages
    colcon build
    source install/setup.bash
    ```

---

##  Package Architecture
*   **`mcqueen_interface`**: Custom ROS2 message definitions.
*   **`mcqueen_bot`**: Primary navigation and hardware control (Physical).
*   **`mcqueen_sim`**: Gazebo environment simulation (Virtual).
*   **`Pico Firmware`**: Low-level motor control and sensor input via UART.

---

##  Launch & Development Workflow

### Physical Robot Execution
*   **Open Challenge:** `ros2 launch mcqueen_bot open.mcqueen_launch.py`
*   **Obstacle Challenge:** `ros2 launch mcqueen_bot robot.mcqueen_launch.py`

### Simulation Execution
*   **Launch Simulation:** `ros2 launch mcqueen_sim gazebo.mcqueen.launch.py`
*   **Run Algorithm (Sim):** `ros2 launch mcqueen_bot sim.mcqueen_launch.py`

*Refer to the full project documentation for specific calibration nodes (`color_calibration_node`) and configuration files (`track.yaml`).*
