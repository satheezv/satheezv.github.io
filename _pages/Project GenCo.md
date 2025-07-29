---
layout: archive
title: "Project GenCo (2025)"
permalink: /projects/GenCo
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><strong>GenCo: A Dual LVLM Generate-Correct Framework for Adaptive Peg-in-Hole Robotics</strong></p>

<div style="text-align: center;">
Satheeshkumar Veeramani<sup>1</sup>, Zhengxue Zhou<sup>1</sup>, Hatem Fakhruldeen<sup>1</sup>, Seda Uyanik<sup></sup>, Andrew Ian Cooper<sup>1,*</sup>.
</div>

<div style="text-align: center;">
  <p><sup>1</sup>Department of Chemistry and Materials Innovation Factory, University of Liverpool, Liverpool, United Kingdom</p>
</div>

<p style="text-align: justify;"><em> Recent advancements in Large-Vision Language Models (LVLMs) have enhanced their application in robotics, encompassing high-level task planning and low-level action control. Despite their strong performance across various robotic tasks, even for zero-shot scenarios, most LVLM applications remain open-loop, adhering to a plan-and-execute paradigm without mechanisms to assess task completion. To address this limitation, we propose GenCo, a Generate-Correct framework designed to automate a peg-in-hole task using a UR5e robot. This framework integrates an LVLM-based motion generator and motion expert, working collaboratively to refine and correct actions during robotic task execution. Both LVLM agents are fine-tuned using the pre-trained LLaVA, enhancing their adaptability and scaling efficiently to diverse tasks. Our comprehensive experiment demonstrates the adaptiveness of the framework, improving the success rate for the peg-in-hole task by 12.75% compared to a single LVLM open-loop method. Notably, in unseen scenarios, the success rate for the triangular peg increased by 15%, and for the random shaped peg by 17%, underscoring the system's effectiveness in handling novel tasks. Additionally, adaptive testing under varied camera positions demonstrates robust performance, affirming its reliability despite shifts in the visual input. The framework is also designed to be lightweight and efficient, facilitating broader adoption and practical deployment. Access to our code and model is provided here: https://github.com/Zhengxuez/generate\_correct </em> </p>

<div style="text-align: center; margin-top: 2em;">
  <h3>Graphical Abstract</h3>
  <img src="/images/GenCo/GA.jpg" alt="" style="max-width: 100%; height: auto;">
</div>


<!-- Video Frame -->
<div style="text-align: center; margin-top: 2em;">
  <h3>Figure: Proposed Approach</h3>
  <img src="/images/GenCo/GA.png" alt="Behavior Tree for Safe Navigation" style="max-width: 75%; height: auto;">
</div>

<!-- <div style="margin-top: 2em;">
  <h3>Video Demonstration - CIN 1</h3>
    <iframe src="https://1drv.ms/v/c/cf51dbc58b2a1fcd/IQRCXLF8M7hAQYEgHnfyiz2rAYtVYlFK64c4-es-mzweBN4" width="960" height="540" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

<div style="margin-top: 2em;">
  <h3>Video Demonstration - CIN 2</h3>
    <iframe src="https://1drv.ms/v/c/cf51dbc58b2a1fcd/IQQdPa8PmSQETaHZGfZzFzyfAYvltJ5SwameaSfs9rAHixM" width="960" height="540" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

<div style="text-align: center; margin-top: 2em;">
  <h3>Figure: Inspection Before Manipulation (IBM) Skill</h3>
  <img src="/images/IBM.png" alt="Behavior Tree for Safe Navigation" style="max-width: 100%; height: auto;">
</div>

<div style="margin-top: 2em;">
  <h3>Video Demonstration - IBM 1</h3>
    <iframe src="https://1drv.ms/v/c/cf51dbc58b2a1fcd/IQRA2EldDddMR6gSuMR1E8RGAfxkj_ZP6DO44FB_ac1o1W8" width="960" height="540" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

<div style="margin-top: 2em;">
  <h3>Video Demonstration - IBM 2</h3>
    <iframe src="https://1drv.ms/v/c/cf51dbc58b2a1fcd/IQT5sb8jj-cBRZsGuOdcQqqOAevDWoG_GYFX7L3UR_JUPe4" width="960" height="540" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>
 -->




<!-- Page Visits -->
<div style="display: flex; justify-content: center; margin-top: 1em;">
  <a href="https://hits.sh/satheezv.github.io/projects/GenCo"><img alt="Hits" src="https://hits.sh/satheezv.github.io.svg?style=plastic&label=Page%20Visits"/></a>
</div> 

<!-- https://hits.sh/satheezv.github.io.svg?style=plastic&label=Page%20Visits -->