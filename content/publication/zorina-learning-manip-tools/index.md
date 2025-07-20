---
title: Learning to Manipulate Tools by Aligning Simulation to Video Demonstration
authors:
- Kateryna Zorina
- Justin Carpentier
- Josef Sivic
- Vladimír Petrík
date: '2022-01-01'
publishDate: '2025-07-19T16:32:15.086127Z'
publication_types:
- article-journal
publication: '*IEEE Robotics and Automation Letters*'
doi: 10.1109/LRA.2021.3127238
featured: true
abstract: "A seamless integration of robots into human environments requires robots to learn how to use existing human tools. Current approaches for learning tool manipulation skills mostly rely on expert demonstrations provided in the target robot environment, for example, by manually guiding the robot manipulator or by teleoperation. In this work, we introduce an automated approach that replaces an expert demonstration with a Youtube video for learning a tool manipulation strategy.
The main contributions are twofold. First, we design an alignment procedure that aligns the simulated environment with the real-world scene observed in the video. This is formulated as an optimization problem that finds a spatial alignment of the tool trajectory to maximize the sparse goal reward given by the environment. Second, we describe an imitation learning approach that focuses on the trajectory of the tool rather than the motion of the human. For this we combine reinforcement learning with an optimization procedure to find a control policy and the placement of the robot based on the tool motion in the aligned environment. We demonstrate the proposed approach on spade, scythe and hammer tools in simulation, and show the effectiveness of the trained policy for the spade on a real Franka Emika Panda robot demonstration."
summary: "We propose a method for learning tool manipulation from unconstrained videos, removing the need for expert demonstrations. Our approach aligns the simulated environment with the video scene and uses tool-centric imitation learning to derive robot control policies. We validate the method on tools like a spade, scythe, and hammer, and demonstrate real-world success with a spade on a Franka Emika Panda robot."
tags:
- Reinforcement learning
- Trajectory optimization
- Learning from Video
url_project:  https://data.ciirc.cvut.cz/ public/projects/2021LearningToolMotion
---
