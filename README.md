## ROS-Gazebo Introduction

This repo contains example files for integrating Gazebo simulation with ROS... primarily for my own experimentation. Specifically, the repo contains a package which can be added to a catkin workspace.

Convention Note: Repos with hyphens are standard repos and stand-alone workspaces. Repos with underscores are ROS packages which ought to be cloned to a catkin workspace (or included in a repo as a git submodule).

#### Getting it Running

1. Clone this repo into the `src` directory of a catkin workspace.
1. Build workspace
```bash
cd /path/to/workspace
catkin_make
```
1. Note about launchfiles TODO
