# Arduino-Maze-Solving-Robot
An autonomous maze-solving robot built using Arduino Uno, IR sensors, and a motor driver. The robot navigates through a maze using the Left-Hand Rule algorithm, allowing it to follow paths and reach the exit without manual control. This project demonstrates real-time decision-making using sensor feedback and control logic.

**Features**
Autonomous Navigation – No manual control required
IR Sensor-Based Detection – Identifies path and turns
Maze-Solving Algorithm – Implements Left-Hand Rule
Motor Control – Smooth movement using motor driver
Modular Design – Easily adjustable for different maze layouts

**Components**
Arduino Uno
Arduino Motor Shield / Motor Driver
2WD Robot Chassis
3 × IR Sensors
7.4V LiPo Battery
Jumper wires & connectors

**How It Works**
Sensor Input: IR sensors detect lines/paths in the maze
Decision Making: Robot applies Left-Hand Rule:
Turn left if possible
Else go straight
Else turn right
Else turn back (dead end)
Motor Control: Arduino sends signals to motors for movement
Continuous Navigation: Repeats process until exit is reached

**Results**
Successfully navigates line-based mazes autonomously
Demonstrates real-time control, sensor integration, and algorithm-based navigation
Reliable performance with proper sensor calibration

**Applications**
Robotics competitions (maze solving / line following)
Autonomous navigation systems
Educational STEM projects
Foundation for advanced robotics (AI pathfinding, SLAM, etc.)
