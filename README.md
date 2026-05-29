# Custom Engine

**Custom C++ Game Engine | DirectX 11 | DirectX 12 | Multi-Threaded Systems**

## Overview

This project is a custom game engine developed entirely from scratch in C++. It was built to explore engine architecture, low-level systems programming, physics simulation, networking, tooling, and real-time rendering.

The engine supports both DirectX 11 and DirectX 12 rendering backends and has been used to develop multiple games and technical projects. Throughout development, the focus has been on creating reusable systems that can support a wide variety of gameplay and rendering requirements.

Building this engine provided hands-on experience with graphics programming, systems architecture, memory management, multithreading, networking, physics, and developer tooling.

To see a more detailed walkthrough of my engine architecture, check out my portfolio page:
https://www.macraesmith.com/projects/engine


---

## Technologies

* C++
* HLSL
* DirectX 11
* DirectX 12
* ImGui
* FMOD

---

## Key Features

### Rendering

* DirectX 11 Rendering Pipeline
* DirectX 12 Rendering Pipeline
* Runtime API Switching Architecture
* Shader Compilation and Management
* Compute Shader Support
* Vertex Displacement
* Blinn-Phong Lighting
* Diffuse Lighting
* Render Targets
* Post Processing Pipeline
* GPU Resource Management

### Physics and Mathematics

* 2D Physics Simulation
* 3D Physics Simulation
* Collision Detection
* Collision Resolution
* Impulse-Based Physics Response
* Raycasting Systems
* Geometry Query Utilities

Supported primitives include:

* AABB2 / AABB3
* OBB2 / OBB3
* Discs and Spheres
* Capsules
* Cylinders
* Planes
* Convex Shapes

Each primitive supports:

* Point containment tests
* Nearest-point queries
* Overlap detection
* Raycast intersection tests
* Translation, rotation, and scaling

### Multi-Threading

* Custom Job System
* Worker Thread Architecture
* Parallel Task Execution
* Background Asset Processing
* Thread-Safe Synchronization Systems

### Networking

* Client-Server Architecture
* Networked Multiplayer Support
* Byte-Level Serialization
* Byte-Level Deserialization
* Packet Processing Utilities

### Event System

* Publish-Subscribe Architecture
* Runtime Event Registration
* Event Argument Definitions
* Loose System Coupling
* Console Event Execution

### Input System

* Mouse and Keyboard Support
* Xbox Controller Support
* Device Abstraction Layer
* Split-Screen Ready Architecture
* Action-Based Input Mapping

### Audio

* FMOD Integration
* Sound Effect Playback
* Music Playback
* Audio Channel Management

### Developer Tools

* ImGui Integration
* Developer Console
* Runtime Command Execution
* Debug Rendering
* Performance Monitoring
* Engine Diagnostics

---

## Engine Architecture

A major goal of this project was maintaining clean separation between systems while allowing them to communicate efficiently.

The engine is built around reusable subsystems responsible for rendering, physics, networking, input, audio, events, and tooling. Systems communicate through well-defined interfaces and an event-driven architecture, allowing projects to scale without introducing tight coupling between gameplay and engine code.

The rendering architecture supports both DirectX 11 and DirectX 12 backends through a common renderer interface, allowing projects to leverage either API while sharing the majority of engine code.

---

## Projects Built Using This Engine

The engine serves as the foundation for multiple projects, including:

* [Procedural Generation and Rendering Techniques for Underwater Environments](https://github.com/MacraeSmith/Procedural-Generation-and-Rendering-Techniques-for-Underwater-Environments.git)<br>
* [Simple Miner](https://github.com/MacraeSmith/Simple-Miner) <br>
* [Libra](https://github.com/MacraeSmith/Libra) <br>
* [Starship Gold](https://github.com/MacraeSmith/Starship-Gold) <br>
* And many more gameplay and rendering prototypes...

---

## Technical Focus Areas

This engine was developed to deepen understanding of:

* Graphics Programming
* Engine Architecture
* Systems Design
* Multi-Threaded Programming
* Real-Time Rendering
* Physics Simulation
* Networking
* Tool Development
* Low-Level C++ Programming

---

## Future Development

Planned areas of continued development include:

* Additional rendering techniques
* Expanded editor tooling
* Improved asset pipeline support
* Enhanced networking systems
* Further DirectX 12 optimization
* Additional gameplay framework features

