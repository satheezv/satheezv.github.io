---
layout: archive
title: "Project PREVENT (2025)"
permalink: /research/PREVENT
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="text-align: center;">
  <p><strong>PREVENT: Proactive Risk Evaluation and Vigilant Execution of Navigation and Manipulation Tasks for Mobile Robotic Chemists</strong></p>
</div>

<p><em> Mobile robotic chemists are a fast growing trend in the field of chemistry and materials research. However, so far these mobile robots lack workflow awareness skills. This poses the risk that even a small anomaly, such as an improperly capped sample vial could disrupt the entire workflow. This wastes time, and resources, and could pose risks to human researchers, such as exposure to toxic materials. Unimodal perception mechanisms can be used to predict anomalies but they often generate excessive false positives. This may halt workflow execution unnecessarily, requiring researchers to intervene and to resume the workflow when no problem actually exists, negating the benefits of autonomous operation. To address this problem, we propose navigation and manipulation skills based on a multimodal Behavior Tree (BT) approach that can be integrated into existing software architectures with minimal modifications. Our approach involves a hierarchical perception mechanism that exploits AI techniques (CNNs and VLMs) and sensory feedback through Dexterous Vision and Navigational Vision cameras and an IoT gas sensor module for execution-related decision-making. Experimental evaluations show that the proposed approach is comparatively efficient and completely avoids both false negatives and false positives when tested in simulated risk scenarios within our robotic chemistry workflow. The results also show that the proposed multi-modal perception skills achieved deployment accuracies that were higher than the average of the corresponding uni-modal skills, both for navigation and for manipulation. </em> </p>

<strong>Authors:</strong> Satheeshkumar Veeramani, Zhengxue Zhou, Francisco Munguia-Galeano, Hatem Fakhruldeen, Thomas Roddelkopf, Mohammed Faeik Ruzaij Al-Okby, Kerstin Thurow, Andrew Ian Cooper.


<div style="text-align: center; margin-top: 2em;">
  <h3>Graphical Abstract</h3>
  <img src="/images/SA.png" alt="Behavior Tree for Safe Navigation" style="max-width: 100%; height: auto; border: 1px solid #ccc;">
</div>


<!-- Video Frame -->
<div style="text-align: center; margin-top: 2em;">
  <h3>Figure: Coordinated Inspection and Navigation (CIN) Skill</h3>
  <img src="/images/CIN.png" alt="Behavior Tree for Safe Navigation" style="max-width: 100%; height: auto; border: 1px solid #ccc;">
</div>

<div style="margin-top: 2em;">
  <h3>Video Demonstration - CIN 1</h3>
    <iframe src="https://1drv.ms/v/c/cf51dbc58b2a1fcd/IQRCXLF8M7hAQYEgHnfyiz2rAYtVYlFK64c4-es-mzweBN4" width="960" height="540" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

<div style="margin-top: 2em;">
  <h3>Video Demonstration - CIN 2</h3>
    <iframe src="https://1drv.ms/v/c/cf51dbc58b2a1fcd/IQQdPa8PmSQETaHZGfZzFzyfAYvltJ5SwameaSfs9rAHixM" width="960" height="540" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

<div style="text-align: center; margin-top: 2em;">
  <h3>Figure: Inspection Before Manipulation (IBM) Skill</h3>
  <img src="/images/IBM.png" alt="Behavior Tree for Safe Navigation" style="max-width: 100%; height: auto; border: 1px solid #ccc;">
</div>

<div style="margin-top: 2em;">
  <h3>Video Demonstration - IBM 1</h3>
    <iframe src="https://1drv.ms/v/c/cf51dbc58b2a1fcd/IQRA2EldDddMR6gSuMR1E8RGAfxkj_ZP6DO44FB_ac1o1W8" width="960" height="540" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>

<div style="margin-top: 2em;">
  <h3>Video Demonstration - IBM 2</h3>
    <iframe src="https://1drv.ms/v/c/cf51dbc58b2a1fcd/IQT5sb8jj-cBRZsGuOdcQqqOAevDWoG_GYFX7L3UR_JUPe4" width="960" height="540" frameborder="0" scrolling="no" allowfullscreen></iframe>
</div>