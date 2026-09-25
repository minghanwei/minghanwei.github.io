---
permalink: /research-projects/
layout: single
author_profile: false
classes: wide
---

<p></p>

# Selected Research Projects

---

## Selected Projects at Florida Atlantic University

<!-- Example Placeholder -->
### Autonomous Robotic Systems for Macroalgae Harvesting in Tank Aquaculture

<div class="macroalgae-intro" style="display: flex; flex-wrap: wrap; align-items: flex-start; gap: 28px; width: 100%; margin: 12px 0 24px;">
  <div class="macroalgae-intro-text" style="flex: 1.65 1 480px; min-width: 0;">
    <p>Macroalgae harvesting plays a critical role in the integrated multi-trophic aquaculture (<a href="https://www.fau.edu/hboi/research/aquaculture-innovation/center-for-marine-and-warm-water-aquaculture/research/imta/">IMTA</a>) system developed at FAU HBOI. As aquaculture operations scale up, efficient and consistent macroalgae collection becomes increasingly essential for maintaining ecological balance and maximizing system productivity.</p>
    <p style="margin-bottom: 0;">To address the challenges posed by large-scale operations including spatial complexity, repetitive motion, and time sensitivity, we are exploring autonomous robotic solutions that can perform harvesting tasks with high reliability and precision. Below is an early-result demonstration that mimics harvesting motion in aquaculture tanks, implemented by an undergraduate researcher Shuaib Olanrewaju from our lab. Our ongoing efforts are focused on expanding this capability to mobile ground robots for large-scale field deployment.</p>
  </div>
  <div style="flex: 1 1 300px; min-width: 0;">
    <img src="/images/tank_aquaculture_scene.png" alt="Outdoor aquaculture tanks with macroalgae growing in the water" width="616" height="462" decoding="async" style="display: block; width: 100%; max-width: 460px; height: auto; margin: 0 auto;">
  </div>
</div>

<div class="project-videos" style="display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 20px; width: 100%; max-width: none; margin: 10px 0 20px;">
  <div style="position: relative; min-width: 0; aspect-ratio: 16 / 9; overflow: hidden; background: #000;">
    <video controls playsinline preload="metadata" aria-label="Early macroalgae harvesting motion demonstration" style="position: absolute; inset: 0; display: block; width: 100%; height: 100%; object-fit: contain;">
      <source src="/files/aqu_harvest.mp4" type="video/mp4">
      <a href="/files/aqu_harvest.mp4">Download the harvesting motion demonstration.</a>
    </video>
  </div>
  <div style="position: relative; min-width: 0; aspect-ratio: 16 / 9; overflow: hidden; background: #000;">
    <video controls playsinline preload="metadata" aria-label="Autonomous macroalgae harvesting demonstration" style="position: absolute; inset: 0; display: block; width: 100%; height: 100%; object-fit: contain;">
      <source src="/files/macroalgae-harvesting-demo.mp4" type="video/mp4">
      <a href="/files/macroalgae-harvesting-demo.mp4">Download the autonomous harvesting demonstration.</a>
    </video>
  </div>
</div>
<p style="font-size: 90%; font-style: italic; text-align: center; margin-top: -10px;">
  This research was mainly supported by the <a href="https://hboifoundation.org/HBOI-24-AReport/" target="_blank">Harbor Branch Oceanographic Institute Foundation</a> at FAU as an SLP project.
</p>

### Natural-Language Constraint-Aware Path Planning with Large Language Models
Real-world routing tasks often involve customized constraints that are difficult to handle with a single predefined planning formulation. We develop an LLM-based approach that interprets natural-language planning requests, converts them into structured problem formulations, and uses verification and iterative refinement to generate feasible, improved routes.

Across the tested constrained-routing problems, verification increased the valid-solution rate from 85.63% to 95.38%, while iterative refinement reduced route cost in 64% of the tested cases.

<div style="display: flex; justify-content: center; margin-top: 12px; margin-bottom: 25px;">
  <img src="/images/llm-path-planning-pipeline.svg" alt="Pipeline for natural-language constraint-aware path planning with large language models" style="width: 100%; max-width: 900px; height: auto;">
</div>

---

## Projects During Ph.D. at University of Minnesota - Twin Cities

### Coverage path planning under energy constraints
<div style="overflow:auto">
  <img src="/images/multi-paths.jpg?raw=true" alt="Photo" style="float:left; margin-right: 10px; width: 300px; margin-bottom: 10px;">
  <p style="margin-left: 10px;">
  Effectively deploying autonomous robots in large environments requires strategic planning, especially when energy resources are limited. This project tackles the problem of persistent coverage by mobile robots that must periodically recharge. Instead of relying on a single long path, we develop algorithms to segment the coverage task into multiple energy-feasible paths, each routed through a recharging station. </p>
</div>
Our work includes two approximation algorithms with provable performance guarantees, a strong theoretical foundation for real-world robotic deployment in energy-constrained settings.
<p style="font-size: 80%; font-style: italic; text-align: center; margin-top: -10px;">
  This research was supported by NSF-funded projects led by my Ph.D. advisor.
</p>

### Energy mapping for planning energy-efficient paths with air-to-ground collaboration
<div class="container">
  <img src="/images/energy-mapping.jpg?raw=true" alt="Photo" height="200px" style="margin-bottom: 10px;">
</div>
Energy-efficient navigation is a key challenge in autonomous field robotics, particularly when operating over large, non-uniform terrains. This project addresses the missing piece in energy-aware planning: the generation of accurate energy-cost maps. We leverage aerial–ground collaboration to collect relevant field data and apply machine learning models to infer spatially varying energy costs. These maps enable the application of standard planning algorithms while significantly improving energy efficiency across diverse environments.
<div style="display: flex; justify-content: center; gap: 15px; margin-bottom: 30px; flex-wrap: wrap;">
  <img src="/images/corn-fields.jpg?raw=true" alt="Photo" 
       style="width: 100%; max-width: 640px; height: auto;">
</div>
<p style="font-size: 80%; font-style: italic; text-align: center; margin-top: -10px;">
  This research was supported by NSF-funded projects led by my Ph.D. advisor.
</p>

### Occupancy map inpainting for online robot navigation
<div style="overflow:auto">
  <img src="/images/indoor-nav.jpg?raw=true" alt="Photo" style="float:left; margin-right: 10px; width: 300px; margin-bottom: 10px;">
  <p style="margin-left: 10px;">
  Indoor navigation using sensors with limited field of view and occlusion is a challenging task, especially for small-sized robots.</p>
</div>

Safe and efficient navigation in indoor or cluttered environments often suffers from occlusions and sensor limitations. This project explores a novel learning-based approach to occupancy map inpainting, which predicts the layout of unseen areas based on limited sensory data. Using a two-camera system, we train models to infer missing map regions, allowing the robot to proactively plan paths and avoid potential hazards. Our results show that inpainted maps lead to faster goal-reaching behavior and improved navigation robustness.

<div class="container" style="margin-top: 18px; margin-bottom: 20px;">
  <img src="/images/occupancy-map-inpainting.jpg?raw=true" alt="Occupancy map inpainting for robot navigation" height="200px" style="margin-bottom: 10px;">
</div>

<p style="font-size: 80%; font-style: italic; text-align: center; margin-top: -10px;">
  This project was completed during my internship at Samsung Research America, New York.
</p>


### Agricultural weed control using autonomous robots
Maintaining organic and sustainable agriculture demands alternatives to chemical herbicides, especially for weed control. In this project, we developed an autonomous robotic platform capable of mowing unwanted vegetation in pasturelands. This solution not only reduces chemical usage but also provides scalable, cost-effective weed management. We also prototyped a compact robotic system designed to navigate tight rows in crop fields such as corn. Together, these systems support more eco-friendly farming practices through intelligent automation.

<div class="weed-control-videos" style="display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 20px; width: 100%; margin: 18px 0 24px;">
  <div style="min-width: 0;">
    <div style="position: relative; aspect-ratio: 16 / 9; overflow: hidden; background: #000;">
      <iframe class="fitvidsignore" src="https://www.youtube.com/embed/mVVQWA6jrS4" title="Autonomous pasture mowing demonstration" style="position: absolute; inset: 0; display: block; width: 100%; height: 100%; border: 0;" allow="autoplay; encrypted-media; fullscreen" allowfullscreen></iframe>
    </div>
    <p style="margin: 8px 0 0; font-size: 90%; text-align: center;">Autonomous pasture mowing</p>
  </div>
  <div style="min-width: 0;">
    <div style="position: relative; aspect-ratio: 16 / 9; overflow: hidden; background: #000;">
      <video controls playsinline preload="metadata" poster="/images/cornfield-weed-control-poster.jpg" aria-label="Cornfield weed-control robot demonstration" style="position: absolute; inset: 0; display: block; width: 100%; height: 100%; object-fit: contain;">
        <source src="/files/cornfield-weed-control.mp4" type="video/mp4">
        <a href="/files/cornfield-weed-control.mp4">Download the cornfield robot demonstration.</a>
      </video>
    </div>
    <p style="margin: 8px 0 0; font-size: 90%; text-align: center;">Cornfield robot demonstration (4× speed)</p>
  </div>
</div>

<div style="width: 100%; max-width: 640px; margin: 0 auto 24px;">
  <img src="/images/corn-fields.jpg" alt="Cornfield rows, a compact robot among corn plants, and its view between the rows" width="577" height="205" loading="lazy" decoding="async" style="display: block; width: 100%; height: auto; margin: 0;">
  <p style="margin: 8px 0 0; font-size: 90%; text-align: center;">Field setting, robotic platform, and navigation between crop rows</p>
</div>
<p style="font-size: 80%; font-style: italic; text-align: center; margin-top: -10px;">
  This project was supported by the <a href="https://www.lccmr.mn.gov/projects/2018-index.html" target="_blank">Environment and Natural Resources Trust Fund of LCCMR</a>, Minnesota.
</p>

---
