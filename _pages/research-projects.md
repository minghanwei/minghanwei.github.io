---
permalink: /research-projects/
---

<p> </p>
# Selected Research Projects:

## Coverage path planning under energy constraints
<div style="overflow:auto">
  <img src="/images/multi-paths.jpg?raw=true" alt="Photo" style="float:left; margin-right: 10px; width: 300px; margin-bottom: 10px;">
  <p style="margin-left: 10px;">
  A practical robot works under energy constraints. To cover a large area, it may not be able to finish the task in one iteration. It needs to visit a recharging station to get recharged and then continue the work. Multiple paths need to be planned, and the robot needs to be recharged between two paths.</p>
</div>
We have presented two approximation algorithms to this problem with theoretical proof for the performance guarantee compared to the optimal solution.


## Energy mapping for planning energy-efficient paths with air-to-groud collaboration

<div class="container">
  <img src="/images/energy-mapping.jpg?raw=true" alt="Photo" height="200px" style="margin-bottom: 10px;">
</div>
To apply existing planning algoirthms to find energy-optimal paths, energy-cost maps are required. Howevern, how to obtain energy-cost maps, especially for large non-uniform fields, has not been sufficiently solved.

We use the collaboration between aerial and ground robots for data-collection, and apply learn-based methods to predict energy-cost maps for the given environments.

## Occupancy map inpainting for online robot navigation
<div style="overflow:auto">
  <img src="/images/indoor-nav.jpg?raw=true" alt="Photo" style="float:left; margin-right: 10px; width: 300px; margin-bottom: 10px;">
  <p style="margin-left: 10px;">
  Indoor navigation using sensors with limited field of view and occlusion is a challenging task, especially for small-sized robot.</p>
</div>

<div class="container">
  <img src="/images/occupancy-map-inpainting.jpg?raw=true" alt="Photo" height="200px" style="margin-bottom: 10px;">
</div>
We use a learning-based method to predict the occupancy of unseen areas around the robot (occupancy map inpainting). The training data is collected using a two-camera setup, where the high camera, which can see a larger area, is used to supervise the training. With the inpainted occupancy map, the robot reaches goal locations faster, compared to using the raw maps.

## 4. Agricultural weed control using autonomous robots
Using robotic mowers instead of chemical herbicides for removing weeds in agricultural lands can not only reduce costs, but also protect our natural environment and keep the field organic. In this project, we developed a robotic platform for mowing weeds in pastures. A demo video is available [here](https://www.youtube.com/watch?v=27WGiFynvvg).
<div class="container">
  <img src="/images/cowbot-in-pasture.jpg?raw=true" alt="Photo" height="50px" style="margin-bottom: 10px; align-items: center;">
</div>

We also implemented a smaller platform that could navigate through narrow space such as corn rows.
<div style="display: flex; justify-content: center; margin-top: 10px; margin-bottom: 20px;">
  <iframe src="https://drive.google.com/file/d/1Ndo3ITq_g58ODMreXcUEOwgSdjZ0zH9u/preview" 
          width="560" height="315" allow="autoplay">
  </iframe>
</div>

<!-- Line 2: Three Images Centered in a Row -->
<div style="display: flex; justify-content: center; gap: 15px; margin-bottom: 30px;">
  <img src="/images/corn-fields-1.jpg?raw=true" alt="Corn field top view" height="200px">
  <img src="/images/corn-fields.jpg?raw=true" alt="Robot in corn field" height="200px">
  <img src="/images/corn-fields-2.jpg?raw=true" alt="Corn row path" height="200px">
</div>