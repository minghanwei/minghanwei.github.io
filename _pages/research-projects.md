---
permalink: /research-projects/
---

<p></p>

# Selected Research Projects

---

## Projects at Florida Atlantic University

<!-- Example Placeholder -->
### Macroalgae Harvesting for Tank Aquaculture With Autonomous Robots
Macroalgae harvesting plays a critical role in the integrated multi-trophic aquaculture ([IMTA](https://www.fau.edu/hboi/research/aquaculture-innovation/center-for-marine-and-warm-water-aquaculture/research/imta/)) system developed at FAU HBOI. As aquaculture operations scale up, efficient and consistent macroalgae collection becomes increasingly essential for maintaining ecological balance and maximizing system productivity.

To address the challenges posed by large-scale operations including spatial complexity, repetitive motion, and time sensitivity, we are exploring autonomous robotic solutions that can perform harvesting tasks with high reliability and precision. Below is a early-result demonstration that mimics harvesting motion in aquaculture tanks, implemented by an undergraduate researcher Shuaib Olanrewaju from our lab. Our ongoing efforts are focused on expanding this capability to mobile ground robots for full-field deployment in real-world environments.

<div style="margin-top: 10px; margin-bottom: 20px;">
  <video controls style="display: block; margin: 0 auto; width: 100%; max-width: 640px;">
    <source src="/files/aqu_harvest.mp4" type="video/mp4">
  </video>
</div>

---

## Projects During Ph.D. at University of Minnesota - Twin Cities

### Coverage path planning under energy constraints
<div style="overflow:auto">
  <img src="/images/multi-paths.jpg?raw=true" alt="Photo" style="float:left; margin-right: 10px; width: 300px; margin-bottom: 10px;">
  <p style="margin-left: 10px;">
  Effectively deploying autonomous robots in large environments requires strategic planning, especially when energy resources are limited. This project tackles the problem of persistent coverage by mobile robots that must periodically recharge. Instead of relying on a single long path, we develop algorithms to segment the coverage task into multiple energy-feasible paths, each routed through a recharging station. </p>
</div>
Our work includes two approximation algorithms with provable performance guarantees, making it a strong theoritical foundation for real-world robotic deployment in energy-constrained settings.

### Energy mapping for planning energy-efficient paths with air-to-ground collaboration
<div class="container">
  <img src="/images/energy-mapping.jpg?raw=true" alt="Photo" height="200px" style="margin-bottom: 10px;">
</div>
Energy-efficient navigation is a key challenge in autonomous field robotics, particularly when operating over large, non-uniform terrains. This project addresses the missing piece in energy-aware planning: the generation of accurate energy-cost maps. We leverage aerial–ground collaboration to collect relevant field data and apply machine learning models to infer spatially varying energy costs. These maps enable the application of standard planning algorithms while significantly improving energy efficiency across diverse environments.

### Occupancy map inpainting for online robot navigation
<div style="overflow:auto">
  <img src="/images/indoor-nav.jpg?raw=true" alt="Photo" style="float:left; margin-right: 10px; width: 300px; margin-bottom: 10px;">
  <p style="margin-left: 10px;">
  Indoor navigation using sensors with limited field of view and occlusion is a challenging task, especially for small-sized robots.</p>
</div>

<div class="container">
  <img src="/images/occupancy-map-inpainting.jpg?raw=true" alt="Photo" height="200px" style="margin-bottom: 10px;">
</div>
Safe and efficient navigation in indoor or cluttered environments often suffers from occlusions and sensor limitations. This project explores a novel learning-based approach to occupancy map inpainting, which predicts the layout of unseen areas based on limited sensory data. Using a two-camera system, we train models to infer missing map regions, allowing the robot to proactively plan paths and avoid potential hazards. Our results show that inpainted maps lead to faster goal-reaching behavior and improved navigation robustness.


### Agricultural weed control using autonomous robots
Maintaining organic and sustainable agriculture demands alternatives to chemical herbicides, especially for weed control. In this project, we developed an autonomous robotic platform capable of mowing unwanted vegetation in pasturelands. This solution not only reduces chemical usage but also provides scalable, cost-effective weed management. We also prototyped a compact robotic system designed to navigate tight rows in crop fields such as corn. Together, these systems support more eco-friendly farming practices through intelligent automation.

<div style="text-align: center; margin-top: 10px; margin-bottom: 20px;">
  <iframe 
    src="https://www.youtube.com/embed/mVVQWA6jrS4" 
    style="width: 100%; max-width: 640px; aspect-ratio: 16 / 9; border: none;" 
    allow="autoplay; encrypted-media; fullscreen"
    allowfullscreen>
  </iframe>
</div>

<div style="display: flex; justify-content: center; margin-top: 10px; margin-bottom: 20px;">
  <iframe 
    src="https://drive.google.com/file/d/1Ndo3ITq_g58ODMreXcUEOwgSdjZ0zH9u/preview"
    style="width: 100%; max-width: 640px; aspect-ratio: 16 / 9; border: none;"
    allow="autoplay; encrypted-media; fullscreen"
    allowfullscreen>
  </iframe>
</div>

<div style="display: flex; justify-content: center; gap: 15px; margin-bottom: 30px; flex-wrap: wrap;">
  <img src="/images/corn-fields.jpg?raw=true" alt="Photo" 
       style="width: 100%; max-width: 640px; height: auto;">
</div>

---