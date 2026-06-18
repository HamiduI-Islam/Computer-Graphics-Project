# Computer-Graphics-Project
# ✈️ Airplane Rescue Scenario

An interactive 3D computer graphics simulation of an aviation emergency and subsequent rescue operation. Developed in C++ using OpenGL and the GLUT (OpenGL Utility Toolkit) library, this project demonstrates core computer graphics concepts such as 3D modeling, lighting, camera animations, and interactive event handling.

## Features

- Dynamic Scenario Simulation: Experience a multi-stage narrative including an airplane take off, emergency landing, flare deployment, and the arrival of a rescue boat.
- Custom 3D Models: Procedurally generated 3D models of an airplane, rescue helicopter, rugged terrain, and environmental elements using OpenGL primitives.
- Realistic Lighting & Shading: Implements ambient, diffuse, and specular lighting to simulate a realistic emergency atmosphere.
- Particle Systems: Realistic rendering rescue signal flares.

## 🎮 Controls

Launch the simulation and use the following keyboard and mouse inputs to interact with the environment:

- key Board Arrow: R / L  : Move Forward / Move Backward
- Mouse Double Click : Trigger Rescue Operation / Object Movement

- N : Toggle Day / Night Lighting mode
- M / U : Sound Mute / Unmute

## 🛠️ Prerequisites

Before running the project locally, ensure you have a C++ compiler and the necessary OpenGL/GLUT development libraries installed.

### Windows 

Windows (Code::Blocks / Visual Studio) Open your IDE and create a new GLUT Project or an empty C++ Project. After Download the .rar file Add all the .cpp and .h source files from this repository to your project workspace.Configure the Linker Settings in your IDE to include:freeglut (or glut32)opengl32glu32
