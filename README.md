# Multi-Sensor Fusion Pipeline in C++

C++ implementation of a sensor fusion pipeline that combines IMU and camera data for state estimation.

## Overview
- Fuses IMU inertial measurements with camera observations for real-time pose estimation
- Built with CMake, structured with separate include/src directories
- Processes real sensor data (IMU CSV, camera JSON)

## Tech Stack
- C/C++
- CMake build system
- JSON and CSV data parsing

## Project Structure
sensorfusion/
├── include/       # Header files
├── src/           # Source implementation
├── build/         # Build artifacts
├── task_imu.csv   # IMU sensor data
├── task_cam_data.json  # Camera observations
└── CMakeLists.txt


## Build & Run
```bash
mkdir build && cd build
cmake ..
make
./sensor_fusion
```
