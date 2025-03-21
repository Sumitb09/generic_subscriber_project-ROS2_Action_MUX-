# Generic Subscriber Project - ROS2 Action MUX

This project demonstrates a generic subscriber implementation in ROS2, focusing on the use of actions and multiplexing (MUX) mechanisms.

## Overview

The repository showcases:

- **Generic Subscriber**: A node that subscribes to multiple topics with varying message types using templates or dynamic typing.
- **ROS2 Actions**: Implementation of long-running tasks that provide feedback and result mechanisms.
- **Multiplexing (MUX)**: Techniques to handle multiple data streams efficiently, directing them to appropriate processing pipelines.

## Features

- Subscribe to multiple topics with different message types.
- Implement actions to manage long-running tasks with feedback.
- Utilize multiplexing to handle multiple data streams.

## Prerequisites

Before running this project, ensure you have the following:

- **ROS2 Jazzy** (or compatible version)
- **C++17** or later
- **Colcon build system**
- **Git** for cloning the repository
- **rosdep** for dependency management

## Installation and Setup

Follow these steps to set up and run the project:

### 1. Clone the repository

Open a terminal and run:

```bash
git clone https://github.com/Sumitb09/generic_subscriber_project-ROS2_Action_MUX.git
