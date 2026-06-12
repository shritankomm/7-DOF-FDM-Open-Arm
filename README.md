# 7-DOF Open Source 3D Printed Humanoid Arms

An open-source, fully 3D-printable 7-DOF humanoid robotic arm designed as an accessible research platform. Built with high-torque Feetech serial bus servos and a Raspberry Pi 5, it supports ROS2 for motion planning, VR teleoperation for intuitive control, and autonomous/agentic operation via an onboard camera. With all CAD files, BOM, and software fully open source, anyone can build and expand on it for under $1,000.

<img width="832" height="683" alt="image" src="https://github.com/user-attachments/assets/5fb91a15-26a2-44ff-a8f1-01cf45a75f68" />

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
## Inspiration
- I made this project as something I find interest in is human-related robotics. In the past, I have made prosthetics and other medical devices, and this felt like the fun next step. I also built this as an act to make a low-cost research tool and as an ability for me to begin learning more advanced robotics. Things like ROS and openCV are new things to me that I want to integrate and explore, and I want to document this journey and open-source it so others can follow and build upon the project, doing bigger and better things. I hope I can inspire people to do more human-centered robotics, and I definitely have plans for more humanoid robot projects (a pair of legs potentially) and hope to be able to document them on GitHub and make them open source for everyone to be able to learn.


---

## Hardware

All parts, links, and pricing can be found in BOM.md

---

## Repository Structure

- CAD/          - CAD files, screenshots, Parts List (STEP/Onshape Public Link)
- software/     - Software, firmware, and control code (coming soon)
- docs/      - Build journal entries and progress updates/documentation
- BOM.md        - Full bill of materials with links and prices
- instructions.md - Build and assembly instructions (coming soon)
- pictures.md - pictures of the fully assembled arm 
- README.md     - This file

---

## Build Instructions

Full step-by-step assembly instructions can be found in instructions.md. Follow along via the build journal in /DOCS to track design decisions and progress in the meantime.

---

## Coming Soon

- ROS2 packages and launch files
- Vision capabilities 
- VR teleoperation integration
- Full open-source firmware and control code
- Complete build instruction guide

## License
Hardware designs: CERN-OHL-S v2 (or CC BY 4.0)
