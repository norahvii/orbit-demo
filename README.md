# 3D Orbiting Atomic Spheres

Interactive Spring Boot application featuring customizable 3D orbiting spheres with particle effects.

## Requirements

* Java 17
* Maven

## Getting Started

### Build the Project
```bash
mvn clean install
```

### Run the Application
```bash
mvn spring-boot:run
```

### View in Browser

Open [http://localhost:8080/](http://localhost:8080/)

## Features

- Real-time 3D sphere orbital simulation
- Adjustable rotation speed, particle count, and sphere dimensions
- Multiple color schemes
- Interactive particle glow effects
- Perspective-based rendering with depth sorting

## Controls

Use the control panel to adjust:
- Rotation speed
- Number of orbiting spheres (1-10)
- Particles per sphere
- Sphere and orbit radius
- Glow intensity
- Particle size
- Color schemes (toggle between blue-cyan, red-orange, and blue-red)

## Project Structure
```
src/
└── main/
    ├── java/com/example/orbit/
    │   └── OrbitDemoApplication.java
    └── resources/
        └── static/
            └── index.html
```
