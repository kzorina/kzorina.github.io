---
title: Temporally Consistent Object 6D Pose Estimation for Robot Control
authors:
- Kateryna Zorina
- Vojtech Priban
- Mederic Fourmy
- Josef Sivic
- Vladimir Petrik
date: '2025-01-01'
publishDate: '2025-07-19T16:32:15.108199Z'
publication_types:
- article-journal
publication: '*IEEE Robotics and Automation Letters*'
doi: 10.1109/LRA.2024.3502052
featured: true
abstract: "Single-view RGB object pose estimators have reached a level of precision and efficiency that makes them good candidates for vision-based robot control. However, off-the-shelf methods lack temporal consistency and robustness that are mandatory for a stable feedback control. In this work, we develop a factor graph approach to enforce temporal consistency of the object pose estimates. In particular, the proposed approach: (i) incorporates object motion models, (ii) explicitly estimates the object pose measurement uncertainty, and (iii) integrates the above two components in an online optimization-based estimator. We demonstrate that with appropriate outlier rejection and smoothing using the proposed factor graph approach, we can significantly improve the results on standardized pose estimation benchmarks. We experimentally validate the stability of the proposed approach for a feedback-based robot control task in which the object is tracked by the camera attached to a torque controlled manipulator."
summary: "We present a factor graph-based method to enforce temporal consistency in single-view RGB object pose estimation for robot control. By incorporating motion models, estimating measurement uncertainty, and performing online optimization, our approach improves pose stability and robustness. We validate its effectiveness on benchmarks and in real-time feedback control with a camera-mounted robot arm."
tags:
- Pose estimation
- Robot vision systems
- Smoothing methods
url_project: https://data.ciirc.cvut.cz/public/projects/2023VideoGuidedTAMP
---
