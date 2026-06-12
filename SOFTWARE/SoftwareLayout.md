<img width="1360" height="1440" alt="image" src="https://github.com/user-attachments/assets/f6b38e13-9468-48da-8832-d14148a74179" />
--

**Software and Electrical Architecture**

The system is powered by a Raspberry Pi 4 (2GB) running Ubuntu and ROS, with all processing performed locally on the device.

A Logitech C720 USB camera provides real-time video input to the Raspberry Pi. A ROS vision node uses OpenCV to process images and detect objects within the robot's workspace.

ROS handles communication between nodes, command planning, and overall system coordination. During development, Gazebo can be used to simulate the robot and test ROS topics before running on physical hardware.

Motion commands are sent from the Raspberry Pi to the serial bus servo controller through a UART connection. The controller translates these commands and drives the robotic arm's servos.

Each servo returns encoder position data, which is sent back through the controller to the Raspberry Pi. ROS uses this feedback to update the robot's state and improve positioning accuracy through closed-loop control.

Control Loop:
Camera → Vision Processing → ROS Planning → Servo Controller → Robotic Arm → Encoder Feedback → ROS Update
