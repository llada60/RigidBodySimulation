# Smoothed Particle Hydrodynamics (SPH) Simulation

[🎬 Watch the demo video](https://github.com/llada60/RigidBodySimulation/raw/refs/heads/main/demo.mp4)

---

**CSC_4IG03_TP** Fundamentals of Computer Graphics, Fall 2024

Implementation of a Smoothed Particle Hydrodynamics (SPH) simulation using OpenGL.

---



## File Structure

```
.
├── dep
├── src/
│   ├── main.cpp                        # Implementation of SPH simulation
│   └── Vector.hpp
├── CMakeLists.txt
├── demo.mp4
└── README.md                           # This file
```

## Running the code

The code uses `cmake` as a build system. Run the following commands in the terminal to build and run the project:

```
> cmake -B build    # under the directory where the CMakeLists.txt is located
> make -C build
> ./tpSubdiv        
```

## Controls

### Keyboard commands:
- H: print this help
- P: toggle simulation
- G: toggle grid rendering
- V: toggle velocity rendering
- S: save current frame into a file
- Q: quit the program
