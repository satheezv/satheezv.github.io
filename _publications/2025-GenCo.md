---
title: "GenCo: A Dual LVLM Generate-Correct Framework for Adaptive Peg-in-Hole Robotics"
collection: publications
category: conferences
permalink: /publications/GenCo
excerpt: ' we propose GenCo, a Generate-Correct framework designed to automate a peg-in-hole task using a UR5e robot. This framework integrates an LVLM-based motion generator and motion expert, working collaboratively to refine and correct actions during robotic task execution.'
date: 2025-01-04
venue: 'International Conference on Robotics and Automation 2025 (ICRA 2025), Atlanta, USA'
paperurl: 'https://ieeexplore.ieee.org/document/11128409'
citation: '10.1109/ICRA55743.2025.11128409'
---
Recent advancements in Large-Vision Language Models (LVLMs) have enhanced their application in robotics, encompassing high-level task planning and low-level action control. Despite their strong performance across various robotic tasks, even for zero-shot scenarios, most LVLM applications remain open-loop, adhering to a plan-and-execute paradigm without mechanisms to assess task completion. To address this limitation, we propose GenCo, a Generate-Correct framework designed to automate a peg-in-hole task using a UR5e robot. This framework integrates an LVLM-based motion generator and motion expert, working collaboratively to refine and correct actions during robotic task execution. Both LVLM agents are fine-tuned using the pre-trained LLaVA, enhancing their adaptability and scaling efficiently to diverse tasks. Our comprehensive experiment demonstrates the adaptiveness of the framework, improving the success rate for the peg-in-hole task by 12.75\% compared to a single LVLM open-loop method. Notably, in unseen scenarios, the success rate for the triangular peg increased by 15\%, and for the random shaped peg by 17\%, underscoring the system's effectiveness in handling novel tasks. Additionally, adaptive testing under varied camera positions demonstrates robust performance, affirming its reliability despite shifts in the visual input. The framework is also designed to be lightweight and efficient, facilitating broader adoption and practical deployment. Access to our code and model is provided here: https://github.com/Zhengxuez/generate_correct


<p style="text-align: center;"><a href="https://ieeexplore.ieee.org/document/11128409"> click here</a>to download the ICRA 2025 Version</p>