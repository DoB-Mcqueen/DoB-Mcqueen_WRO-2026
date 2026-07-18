<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/302a7021-1306-48f9-872a-8aa2fe2f5a9b" />
Dreams of Bangladesh (DoB) is a robotics team from Bangladesh making its debut in the World Robot Olympiad Future Engineers 2026 category. Our autonomous robot, DoB McQueen is designed and developed entirely by our team with a focus on intelligent LiDAR-based navigation, reliability, image processing, and engineering excellence.






This repository contains our complete project documentation, including source code, CAD models, hardware design, technical reports, photos, videos, and every stage of the development journey behind DoB McQueen. 

# Table of Contents
* [Team Introduction](#team-introduction)
* [About Dreams of Bangladesh](#about-dreams-of-bangladesh)
* [About WRO](#about-wro)
* [Repository Overciew](#repository-overview)
* [FE Mission Overview](#fe-mission-overview)
* [Key Features](#key-features)
* [Component and Hardware](#component-and-hardware)
* [Algorythm](#algorythm)
* [Mission Run Flow](#mission-run-flow)

# Team Introduction
<table>
  <tr>
    <!-- Member 1: Ahnaf Safwan Islam -->
    <td align="center" width="220" style="padding-right: 30px;">
      <img src="https://github.com/user-attachments/assets/035c62a3-effd-4b9c-9dcd-5ef7229efd91" alt="Ahnaf Safwan Islam" width="130" height="130" style="border-radius: 50%; object-fit: cover;">
      <br />
      <strong>Ahnaf Safwan Islam</strong>
      <br />
      <sub>Embedded Electronics</sub>
    </td>
    <!-- Member 2: Al Amin Sani -->
    <td align="center" width="220" style="padding-right: 30px;">
      <img src="https://github.com/user-attachments/assets/5e03d710-feaf-4fe4-97b6-286c165e0a7d" alt="Al Amin Sani" width="130" height="130" style="border-radius: 50%; object-fit: cover;">
      <br />
      <strong>Al Amin Sani</strong>
      <br />
      <sub>Software and ROS</sub>
    </td>
    <!-- Member 3: Mohammad Sifat -->
    <td align="center" width="220">
      <img src="https://github.com/user-attachments/assets/c41fb012-cda3-4aac-94ad-fcfa7d66c3fb" alt="Mohammad Sifat" width="130" height="130" style="border-radius: 50%; object-fit: cover;">
      <br />
      <strong>Mohammad Sifat</strong>
      <br />
      <sub>Hardware and CAD</sub>
    </td>
  </tr>
</table>

# About Dreams of Bangladesh

<p align="center">
  <img src="https://github.com/user-attachments/assets/0ad98393-3a7f-4ec5-a675-5130f6215df6" alt="Dreams of Bangladesh Logo" width="300" height="300" style="object-fit: contain;">
</p>

Dreams of Bangladesh (DoB) is a youth-led innovation, research, and technology organization based in Bangladesh, working in Robotics, AI, IoT, Autonomous Vehicles (USV/AUV), and Space Technology. 

We design and develop real-world engineering solutions focused on education, sustainability, safety, and humanitarian impact, empowering young innovators to compete and collaborate on national and international platforms. Through research, competitions, workshops, and partnerships, Dreams of Bangladesh is building a global future for Bangladeshi talent.

### Organization Profile

| Attribute | Details |
| :--- | :--- |
| **Website** | [://dreamsofbangladesh.com](https://://dreamsofbangladesh.com) |
| **Industry** | Robotics Engineering |
| **Company Size** | 2-10 employees |
| **Type** | Nonprofit |
| **Founded** | 2021 |

### Core Specialties
* **Robotics & Automation:** Autonomous Surface Vehicles (USV) & Autonomous Underwater Vehicles (AUV)
* **Advanced Tech:** Artificial Intelligence (AI), Internet of Things (IoT), & Embedded Systems
* **Future Tech:** Space Technology, Research & Development, & STEM Education

---
*For collaboration, sponsorship, or partnership: contact us via our official website.*

# About WRO

<table width="100%" style="border: none;">
  <tr style="border: none;">
    <!-- Left Column: Short Definition Text -->
    <td width="70%" valign="middle" style="border: none; padding-right: 20px;">
      <blockquote>
        <strong>World Robot Olympiad (WRO) Future Engineers (FE)</strong> is an advanced, high-tier robotics category designed for top-tier student engineers. The competition challenges teams to design, build, and program fully autonomous self-driving vehicles from scratch, simulating real-world engineering and autonomous vehicle development cycles.
      </blockquote>
    </td>
    <!-- Right Column: Logo in a Circular Frame -->
    <td width="30%" align="center" valign="middle" style="border: none;">
      <img src="https://github.com/user-attachments/assets/0ad98393-3a7f-4ec5-a675-5130f6215df6" alt="WRO Logo" width="160" height="160" style="border-radius: 50%; object-fit: contain;">
    </td>
  </tr>
</table>

### Competition Framework

| Team Dynamics | Technical Freedom |
| :--- | :--- |
| **Age Limit:** 14 – 22 years old <br> **Team Size:** 2 to 3 students <br> **Mentorship:** 1 Official Coach | **Hardware:** Open choice (Arduino, Raspberry Pi, ESP32, etc.) <br> **Software:** Open choice (Python, C++, ROS, OpenCV, etc.) <br> **Materials:** No platform restrictions |

---

### Core Pillars of the Challenge

<table width="100%">
  <tr>
    <td align="center" width="30%">
      <strong>1. Autonomous Driving</strong><br>
      <sub>Steering & Navigation</sub>
    </td>
    <td align="center" width="5%">➔</td>
    <td align="center" width="30%">
      <strong>2. Computer Vision</strong><br>
      <sub>LiDAR & Obstacle Tracking</sub>
    </td>
    <td align="center" width="5%">➔</td>
    <td align="center" width="30%">
      <strong>3. Engineering Lifecycle</strong><br>
      <sub>Full Documentation & GitHub</sub>
    </td>
  </tr>
</table>

#### Autonomous Track Navigation
Teams must engineer a scale vehicle equipped with a mechanical, functional steering system. The robot must dynamically read, navigate, and self-correct through a complex track circuit completely autonomously.

#### Sensor Fusion & Vision
Vehicles rely heavily on cutting-edge control algorithms, computer vision tracking (like color or lane detection), and time-of-flight sensors (LiDAR/Ultrasonic) to map paths and dodge track obstacles in real-time.

#### Industry-Standard Documentation
Unlike basic coding challenges, teams are strictly evaluated on their engineering workflow. You must thoroughly document your engineering iterations, 3D CAD modeling design choices, and code architecture—treating the project like a true industrial development cycle.

# Repository Overview

This repository includes all files, designs, and code for DoB McQueen, our WRO 2025 robot.

<table width="100%">
  <tr>
    <td valign="top" style="padding: 15px;">
      <h3>File Structure</h3>
      <p>Here’s a breakdown of the project folders within the repository:</p>
      <ul>
        <li><strong><a href="./Asset">Asset</a>:</strong> Contains all the images used in the README files of this repository.</li>
        <li><strong><a href="./Dreams%20of%20Bangladesh">Dreams of Bangladesh</a>:</strong> Overview material, documentation, and assets regarding our parent organization.</li>
        <li><strong><a href="./Instructions">Instructions</a>:</strong> Contains all the instructions on how to setup and use the package.</li>
        <li><strong><a href="./Mentor's%20Statement">Mentor's Statement</a>:</strong> Endorsement records and guidance documentation provided by our team coach.</li>
        <li><strong><a href="./Models">Models</a>:</strong> Contains 3D models and CAD designs of the robot.</li>
        <li><strong><a href="./Old%20vs%20New">Old vs New</a>:</strong> Iteration logs and structural comparisons between previous prototypes and the current build.</li>
        <li><strong><a href="./Review">Review</a>:</strong> Performance evaluations, testing data matrices, and design critique feedback.</li>
        <li><strong><a href="./T-Photos">T-Photos</a>:</strong> Technical images of the robot build.</li>
        <li><strong><a href="./Team%20Member's%20Statement">Team Member's Statement</a>:</strong> Documentation containing official structural records and engineering statements from each team member.</li>
        <li><strong><a href="./V-Photos">V-Photos</a>:</strong> Visual photos for aesthetics and showcasing.</li>
        <li><strong><a href="./Videos">Videos</a>:</strong> Performance and demo videos of DoB McQueen.</li>
        <li><strong><a href="./src">src</a>:</strong> Source code for the robot's programming. This contains the ROS2 packages.</li>
      </ul>
    </td>
  </tr>
</table>
  

# FE Mission Overview

### Round 1: Navigation Challenge

The robot must autonomously complete three laps on a pre-defined track. The goal of this round is for the bot to demonstrate stable navigation and precise lap tracking without any obstacle avoidance requirements.

* **Objective:** Complete three laps on the track within the allotted time.
* **Key Tasks:** Accurate path-following, speed control, and lap counting.

<br>
<img src="PASTE_ROUND_1_IMAGE_LINK_HERE" alt="WRO FE Round 1 Layout" width="100%" style="max-height: 400px; object-fit: cover; border-radius: 6px; border: 1px solid #30363d;">
<br>

---

### Round 2: Obstacle Avoidance & Parking

The bot must complete three laps while avoiding dynamic colored obstacles placed along the circuit. After completing the final lap, the vehicle must execute a precision stop within the designated end zone.

* **Green Obstacles:** The bot should move left to avoid.
* **Red Obstacles:** The bot should move right to avoid.
* **Objective:** Complete three laps, avoid obstacles, and park in the designated area.
* **Tasks:** Obstacle detection, color-based avoidance, and precision parking.

<br>
<img src="PASTE_ROUND_2_IMAGE_LINK_HERE" alt="WRO FE Round 2 Layout" width="100%" style="max-height: 400px; object-fit: cover; border-radius: 6px; border: 1px solid #30363d;">
      <br />





# Key Features

The structural layout and computing architecture of DoB McQueen are engineered to maximize performance consistency across dynamic competition environments.

<table width="100%">
  <!-- Feature 1 & 2 Row -->
  <tr>
    <td width="50%" valign="top" style="padding: 15px; border-right: 1px solid #30363d;">
      <h4>Simple but Standard Mechanical Design</h4>
      <p>Every structural subsystem is engineered with a strict focus on mechanical reliability. Optimized component placement lowers the vehicle's center of gravity, minimizing inertia during high-speed turns and ensuring consistent physical execution on the track circuit.</p>
    </td>
    <td width="50%" valign="top" style="padding: 15px; background-color: #161b22;">
      <h4> 3D Printed Chassis</h4>
      <p>Leveraging proven structural design paradigms, the vehicle utilizes a hybrid layout strategy. Combining the immediate manufacturing precision of standard custom-engineered 3D printed components achieves optimal rigidity and geometric flexibility.</p>
    </td>
  </tr>

  <!-- Feature 3 & 4 Row -->
  <tr>
    <td width="50%" valign="top" style="padding: 15px; background-color: #161b22; border-right: 1px solid #30363d;">
      <h4>High-Fidelity Image Processing System</h4>
      <p>The onboard vision system utilizes optimized edge-computing pipelines to achieve low-latency environmental detection. This configuration enables the vehicle to instantly detect track boundaries and execute color-based navigation decisions under varying ambient light profiles.</p>
    </td>
    <td width="50%" valign="top" style="padding: 15px;">
      <h4>Advanced Sensor Suite Integration</h4>
      <p>Equipped with high-frequency LiDAR for 360-degree boundary mapping, precision encoder motors for linear distance calculation, and an onboard Inertial Measurement Unit (IMU) to monitor real-time angular heading and orientation changes.</p>
    </td>
  </tr>

  <!-- Feature 5 & 6 Row -->
  <tr>
    <td width="50%" valign="top" style="padding: 15px; border-right: 1px solid #30363d;">
      <h4>Robot Operating System Framework (ROS2)</h4>
      <p>The core software stack is built natively around ROS2. This design choice enforces complete modular separation between sensing and execution nodes, providing powerful telemetry logging, node communication protection, and reliable visualization tools.</p>
    </td>
    <td width="50%" valign="top" style="padding: 15px; background-color: #161b22;">
      <h4>Real-Time Odometry Calculation</h4>
      <p>By implementing real-time data fusion, the navigation stack combines raw data streams from the onboard IMU and drive wheel encoders. This allows the vehicle to maintain accurate spatial positioning records across successive lap runs.</p>
    </td>
  </tr>


  

