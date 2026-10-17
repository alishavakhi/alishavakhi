# Ali Shavakhi

**M.Sc. Control Systems Engineering, University of Padova.** I work on robotics
perception and control — ROS 2 systems that see, decide and move: AprilTag pose
estimation, colour segmentation, LiDAR navigation, MoveIt 2 motion planning, and
the control theory underneath them.

Before Padova: control boards, sensor fusion and power electronics for
award-winning humanoid and small-size RoboCup teams.

---

## Projects

### [turtlebot3-navigation-perception](https://github.com/alishavakhi/turtlebot3-navigation-perception)
ROS 2 navigation and perception on a simulated TurtleBot 3 — AprilTag goal
extraction, Nav2, a LiDAR corridor-following controller, LiDAR table detection,
and a baseline versus Kalman-filtered state estimator running side by side. The
Gazebo environment is vendored, so the repository builds self-contained.
`ROS 2 · Nav2 · Gazebo · Python`

### [ur5-vision-guided-manipulation](https://github.com/alishavakhi/ur5-vision-guided-manipulation)
Vision-guided cube swapping on a simulated UR5 — 6-DoF pose recovery from a
single RGB camera, colour classification from the ring band around each tag,
pose/colour fusion with explicit staleness handling, then a constraint-aware
MoveIt 2 pick-and-place sequence executed by a C++ node. Environment vendored.
`ROS 2 · MoveIt 2 · OpenCV · C++`

### [traffic-sign-light-detection](https://github.com/alishavakhi/traffic-sign-light-detection)
One YOLO11 detector for 33 classes — 20 traffic signs and 13 traffic-light
states — unified from two datasets whose annotation formats, coordinate
conventions and label taxonomies have nothing in common. The converters and the
frozen class index are the substance of the work.
`Python · YOLO · PyTorch`

### [control-engineering-laboratory](https://github.com/alishavakhi/control-engineering-laboratory)
Five applied control laboratories in MATLAB/Simulink — PID design by the Bode
method with experimental identification of inertia and friction, state-space
tracking with anti-windup and feedforward, digital control by emulation
(backward/forward/Tustin) and a reduced-order observer, LQR and eigenvalue
placement on a resonant two-mass load, and discrete LQR with integral action on
a balancing robot.
`MATLAB · Simulink · Control`

Each repository documents its own limits — what was verified in the original
environment, and what has not been re-run here.

---

## Publication

**[SRBL Team Description Paper](https://ssl.robocup.org/wp-content/uploads/2025/04/2025_TDP_SRBL.pdf)**
— *Small Size League, RoboCup 2025.* First author. The team's mechanical,
electrical and software design for the competition.

---

## Skills

- **Robotics** — ROS 2, MoveIt 2, Nav2, Gazebo, OMPL, tf2
- **Perception & learning** — OpenCV, YOLO, Roboflow, AprilTag, Kalman filtering
- **Control** — state-space and digital control, LQR, pole placement, system
  identification, MCMC parameter estimation
- **Languages & tools** — Python, C/C++, MATLAB, Lua, V+ (Adept), Git, LaTeX
- **Hardware & embedded** — Altium, STM32CubeIDE, PLC ladder logic, SolidWorks;
  motor-control and interface board design

## Education

- **M.Sc. Control Systems Engineering** — University of Padova, Italy · 2024–present
- **B.Sc. Electrical Engineering** — Qazvin I. Azad University, Iran · 2019–2023
  Thesis: optimisation and programming of a humanoid robot's main control circuit

## Robotics experience

- **Team leader, Small Size League** — RoboCup 2025. Also RoboCup referee and
  Junior Soccer League technical-committee member (IranOpen)
- **Researcher / R&D electronics engineer — MRL Humanoid, QIAU** (2019–2024):
  designed the humanoid's main control board (dedicated motor communication path,
  inertial sensor fusion, power distribution and stabilisation) and the
  USB2Dynamixel interface board
- **Co-founder and mentor — NJRT** junior robotics team
- **R&D, Noandishan Hooshmand Sepahan** (2020): hardware for city variable-message
  signs and a sensor gateway for a smart greenhouse

### Awards
- **2023** — International Humanoid Robot League, RoboCup IranOpen — **1st place**
- **2021** — International Humanoid Robot League, RoboCup Bordeaux — **2nd place**
- **2019** — International Humanoid Robot League, RoboCup Sydney — **1st place**
- **2018** — Junior Soccer Robot League, RoboCup Asia-Pacific — **1st place**
- **2018** — Junior Soccer Robot League, RoboCup IranOpen — **3rd place**
- **2017** — Junior Soccer Robot League, RoboCup IranOpen — **5th place**
- **2016** — Junior Soccer Robot League, RoboCup IranOpen — **Best Design award**
- **2016** — Junior Soccer Robot League, RoboCup IranOpen — **1st place**
- **2015** — Junior Soccer Robot League, RoboCup IranOpen — **2nd place**
---

## Contact

- **Email** — alishavakhi99@gmail.com
- **LinkedIn** — [ali-shavakhi](https://www.linkedin.com/in/ali-shavakhi-1335911a6)

Open to robotics, control and computer-vision research and engineering roles.
