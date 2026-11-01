# Hi, I'm Adhu 👋

**Robotics · AI/ML · Optimization**

I work across robotics, AI/ML and optimization, connecting physical systems with perception, control and planning algorithms. My projects include ROS 2 robot integration, language-guided perception, industrial anomaly detection, and metaheuristic approaches to constrained routing and resource allocation.

This is where I'm bringing those projects together, from my two master's programs and ongoing work. You'll find code, recordings and results, along with notes on what works and what still needs attention.

## A glimpse of the work

### [A robot from the ground up](https://github.com/ADHU-ADHU/mobile-robot-platform-ros2)

Motors, sensors, teleoperation and mapping on a physical ROS 2 robot.

https://github.com/user-attachments/assets/cd998e9a-4e2d-4023-997b-f0450d08a12d

### [ScenePilot · Language-Guided Robot Perception](https://github.com/ADHU-ADHU/scenepilot-ros2)

Natural-language questions, visual answers and semantic target selection with Qwen3-VL and SAM 3.

https://github.com/user-attachments/assets/513159de-e3a8-439b-97b9-53676761720d

*Silent demos: mobile robot, 35 seconds; ScenePilot, 48 seconds. [Media provenance](https://github.com/ADHU-ADHU/ADHU-ADHU/blob/main/media/provenance.json).*

## Currently working on

ScenePilot has grown into the foundation for my ongoing master's thesis on **network-aware robot perception**. I'm investigating how video transport and AI processing choices affect end-to-end latency and perception performance, including **SCReAM congestion control and L4S**. The planned robot platform is a **Husky**.

The public ScenePilot repository shows the earlier working perception prototype. Thesis-specific methods, implementation and results remain unpublished; [SCReAM is available upstream as open source](https://github.com/EricssonResearch/scream). [Project update](https://github.com/ADHU-ADHU/scenepilot-ros2/blob/main/docs/PROJECT_UPDATE.md).

## A few other things I've worked on

- **[TurtleBot3 hybrid exploration](https://github.com/ADHU-ADHU/turtlebot3-hybrid-exploration-ros2)** — choosing where to explore, planning a path and reacting to obstacles. This is the dedicated exploration project, with ROS 2 Jazzy, simulation and physical-robot results.
- **[Visual inspection with AE/VAE models](https://github.com/ADHU-ADHU/factory-anomaly-detection-ae-vae)** — looking for assembly defects with autoencoders, variational autoencoders and transfer learning.
- **[AGV planning with nested PSO](https://github.com/ADHU-ADHU/agv-part-feeding-nested-pso)** — deciding what to carry on each trip and the order in which to visit the stops.
- **[ESP32, micro-ROS and LoRa](https://github.com/ADHU-ADHU/esp32-microros-lora-telemetry)** — sensor readings, ROS 2 topics and compact radio packets.

There are also [MATLAB optimization studies](https://github.com/ADHU-ADHU/technical-optimization-metaheuristics) and [anomaly-detection experiments on tabular sensor data](https://github.com/ADHU-ADHU/Anomaly-Detection-Tabular-Data-).

## Technical focus

- **Robotics and autonomous systems:** sensor integration, pose estimation, SLAM integration, occupancy-grid mapping, frontier exploration, A* planning, path tracking, obstacle avoidance and teleoperation.
- **AI, machine learning and perception:** autoencoders, variational autoencoders, anomaly detection, transfer learning, vision-language models and image segmentation, with applications in industrial inspection and robot perception.
- **Metaheuristic optimization:** Particle Swarm Optimization (**PSO**), Differential Evolution (**DE**), Genetic Algorithms (**GA**) and Simulated Annealing (**SA**). My work covers problem formulation, objective functions, constraint handling, parameter tuning and convergence comparisons, applied to AGV allocation and routing, assembly-line balancing and facility location.
- **Mathematical optimization:** linear programming for constrained production planning and resource allocation.

## Tools and platforms

| Area | Tools and technologies |
| --- | --- |
| Programming and numerical computing | Python, C++ (Arduino), MATLAB |
| Modeling and simulation | Simulink, Gazebo |
| Robotics middleware | ROS 2, micro-ROS |
| Machine learning frameworks | PyTorch, TensorFlow/Keras |
| Embedded platforms and communication | Raspberry Pi, ESP32, Arduino, LoRa |
| Development and deployment | Git, Docker, Docker Compose, Kubernetes, Helm |
