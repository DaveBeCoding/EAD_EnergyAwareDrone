# Minimum required version of CMake
cmake_minimum_required(VERSION 3.10)

# Project name and specify C++ standard
project(EAD_EnergyAwareDrone CXX)

# Set C++ standard to C++11
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Specify the source file(s)
set(SOURCE_FILES EAD_EnergyAwareDrone.cxx)

# Add executable target
add_executable(EAD_EnergyAwareDrone_simulator ${SOURCE_FILES})

# Include any directories if needed (not necessary for standard headers)
# target_include_directories(drone_simulator PRIVATE ${INCLUDE_DIRS})
