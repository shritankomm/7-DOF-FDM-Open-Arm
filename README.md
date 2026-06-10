# 7-DOF Open Source 3D Printed Humanoid Arms

An open-source, fully 3D-printable 7-DOF humanoid robotic arm designed as an accessible research platform. Built with high-torque Feetech serial bus servos and a Raspberry Pi 5, it supports ROS2 for motion planning, VR teleoperation for intuitive control, and autonomous/agentic operation via an onboard camera. With all CAD files, BOM, and software fully open source, anyone can build and expand on it for under $1,000.

<img width="923" height="879" alt="image" src="https://github.com/user-attachments/assets/3fbfab57-740d-4e75-ae8b-423eaefb871d" />

---

## Features

- 7 Degrees of Freedom - full human-like range of motion across the shoulder, elbow, and wrist
- High-torque serial bus servos - 30 kg at most joints, 50kg at the shoulder
- Fully 3D printable - all structural components printed in PETG at high infill, no custom machined parts required
- ROS2 integration - built for compatibility with the broader robotics software ecosystem
- VR teleoperation - control the arm intuitively through a VR headset
- Autonomous and agentic control - onboard Raspberry Pi 5 and camera enable independent perception and decision-making
- Under $1,000 - accessible to students, researchers, and makers without institutional budgets

---

## Hardware

All parts, links, and pricing can be found in BOM.md

---

## Repository Structure

- cad/          - CAD files and screenshots (STL, STEP, Onshape Public Link)
- software/     - Software, firmware, and control code (coming soon)
- docs/      - Build journal entries and progress updates/documentation
- BOM.md        - Full bill of materials with links and prices
- instructions.md - Build and assembly instructions (coming soon)
- pictures.md - pictures of the fully assemblied arm along with more detailed CAD pictures
- README.md     - This file

---

## Build Instructions

Full step-by-step assembly instructions can be found in instructions.md. Follow along via the build journal in /DOCS to track design decisions and progress in the meantime.

---

## Coming Soon

- ROS2 packages and launch files
- VR teleoperation integration
- Full open-source firmware and control code
- Complete build instruction guide
