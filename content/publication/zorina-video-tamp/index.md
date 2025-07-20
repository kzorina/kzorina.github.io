---
title: Multi-Contact Task and Motion Planning Guided by Video Demonstration
authors:
- Kateryna Zorina
- David Kovar
- Florent Lamiraux
- Nicolas Mansard
- Justin Carpentier
- Josef Sivic
- Vladimir Petrik
date: '2023-01-01'
publishDate: '2025-07-19T16:32:15.097202Z'
publication_types:
- paper-conference
publication: '*2023 IEEE International Conference on Robotics and Automation (ICRA)*'
doi: 10.1109/ICRA48891.2023.10161551
featured: true
abstract: "This work aims to leverage instructional video to solve complex multi-step task-and-motion planning tasks in robotics. Towards this goal, we propose an extension of the well-established RRT planner, which simultaneously grows multiple trees around grasp and release states extracted from the guiding video. Our key novelty lies in combining contact states and 3D object poses extracted from the guiding video with a traditional planning algorithm that allows us to solve tasks with sequential dependencies, for example, if an object needs to be placed at a specific location to be grasped later. We also investigate the generalization capabilities of our approach to go beyond the scene depicted in the instructional video. To demonstrate the benefits of the proposed video-guided planning approach, we design a new benchmark with three challenging tasks: (i) 3D re-arrangement of multiple objects between a table and a shelf, (ii) multi-step transfer of an object through a tunnel, and (iii) transferring objects using a tray similar to a waiter transfers dishes. We demonstrate the effectiveness of our planning algorithm on several robots, including the Franka Emika Panda and the KUKA KMR iiwa. For a seamless transfer of the obtained plans to the real robot, we develop a trajectory refinement approach formulated as an OCP."
tags:
- Three-dimensional displays;Automation;Buildings;Benchmark testing;Planning;Task
  analysis;Robots
url_project: https://data.ciirc.cvut.cz/public/projects/2024TemporalPose
---
