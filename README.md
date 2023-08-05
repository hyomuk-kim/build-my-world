# Build-My-World Project
The first project for **_Robotics Software Engineer_** nanodegree of _[Udacity](https://www.udacity.com)_

### Project Overview
- Design my world that has enough space for robots to navigate in Gazebo.
- How my _world_ looks:
  ![myworld](https://github.com/hyomuk-kim/build-my-world/blob/master/world_modeling.png)

### Guide
```
mkdir -p ~/{workspace}/src
cd ~/{workspace}/src
git clone git@github.com:hyomuk-kim/build-my-world.git
catkin_make
cd build-my-world/world
gazebo myHome
```

### Structure
```
build-my-world             # Build-My-World Project 
├── model                  # Model files 
│   ├── HumanoidRobot
│   │   ├── model.config
│   │   └── model.sdf
│   └── myBuilding
│       ├── model.config
│       └── model.sdf
├── script                 # Plugin files 
│   └── welcome.cpp
├── world                  # World files
│   └── myHome.world
├── CMakeLists.txt
└── world_modeling.png
```
