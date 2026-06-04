### **EN** | [RU](README.ru.md)

# D-Bus City
### Russian Technological University MIREA (RTU)
---
## Application Description

**D-Bus City** — is a mobile educational game developed using the Godot Engine for Aurora OS. The player completes game levels, answers questions, and maintains user happiness. As the game progresses, new stages of urban development are unlocked, and the achieved progress is visually displayed.

---
## Project Goals
The project was developed as part of an internship with the goal of creating a mobile game application for Aurora OS using the Godot Engine to familiarize developers with the D-Bus system on Android OS. The project demonstrates the capabilities of mobile game development using Godot, including user interface design, game mechanics implementation, and a result-saving system.

---
## Application Features
- completing game levels;
- selecting answers to questions;
- health/ lives system;
- development of a virtual city;
- saving player results;
- leaderboard (Hall of Fame);
- settings screen;

---
## Technologies Used
- Godot Engine 4.4;
- GDScript;
- built-in Godot UI system;
- built-in Godot animation system;
- built-in scene and resource management system.

---
## Содержание
1. [Description](#application-description)
2. [Goals](#project-goals)
3. [Features](#application-features)
4. [Technologies](#technologies-used)
5. [Detailed Description](#detailed-description)
6. [Compatibility](#compatibility)
7. [Build Features](#build-features)
8. [Installation and Launch](#installation-and-launch)
9. [Gallery](#gallery)
11. [Known Issues](#known-issues-and-limitations)
12. [License and Contribution Rules](#license-and-contribution-rules)

---
## Detailed Description
The gameplay consists of sequential level progression. At each level, the player is required to complete a task and choose the correct answer option. Successful completion allows the player to develop the virtual city and observe changes in the urban environment.

The application includes:
- result saving mechanics;
- achievement tracking system;
- lives system;
- settings system;
- leaderboard system.

The interface is adapted for mobile devices and touch controls.

---
## Compatibility
The application is developed using Godot Engine 4.4 for the aarch64 architecture.

Supported devices:
- devices running Aurora OS with ARM64 architecture;
- Aurora OS emulator.

---
## Build Features
General guidelines for building applications for Aurora OS:
 - https://developer.auroraos.ru/doc/software_development/guides/port_apps/godot_export
 - https://wiki.pmifi.ru/ru/guides/godot-aurora

To build the project, the following is required:
  - Ubuntu Desktop 22.04 or higher, or Alt Linux;
  - Godot Engine 4.4 (Yaroslav Andreev build);
  - Aurora SDK MB2;
  - configured Aurora OS build environment (detailed guide - https://wiki.pmifi.ru/ru/guides/godot-aurora)

No external servers or additional services are required.

---
## Installation and Launch
1. Clone the repository on Ubuntu 22.04+ or Alt Linux;
2. Open the project in Godot Engine 4.4 (Yaroslav Andreev build);
3. Export the application for Aurora OS; (detailed guide - https://wiki.pmifi.ru/ru/guides/godot-aurora)
4. Install the RPM file on a device or emulator;
5. Launch the application.

No additional launch conditions are required.

---
## Gallery
![1](screenshots/img1.jpg)
![2](screenshots/img2.jpg)
![3](screenshots/img3.jpg)
![4](screenshots/img4.jpg)
![5](screenshots/img5.jpg)

---
## Known Issues and Limitations
- the application is designed for portrait screen orientation;
- the game content contains a fixed set of levels;
- rendering accuracy depends on device resolution.

---
## License and Contribution Rules
- License: [LICENSE](LICENSE)
- Project authors: [AUTHORS](AUTHORS.md)
- Contribution guidelines: [CONTRIBUTING](CONTRIBUTING.md)
