# Vulkan c++ project for Hypergryph course
This project is extracted from Sascha William's Vulkan Examples, used as homework for students of Hypergryph course. It's already setup with all required libraries as well as headers.

## Cloning
This repository contains submodules for external dependencies, so when doing a fresh clone you need to clone recursively:

```
git clone --recursive https://github.com/enjiushi/CourseHomework.git
```

## Building

Use the provided CMakeLists.txt with [CMake](https://cmake.org) to generate a build configuration for your favorite IDE or compiler, e.g.:

```
cmake -G "Visual Studio 16 2019"
```

Open created "CourseHomework.sln", set project "triangle" as startup project, press F5 and you're good to run

