---
title: DirectX Shader Scene
layout: page
accent_image: ../../../../images/Portfolio-Background.jpg
---

This is a university project made in DirectX using C++ and HLSL. In this project I learned how to code shaders running on the graphics card, and the final product features shadows calculated with depth maps, post processing effects, heightmapped terrain and tessellation used to dynamically create LOD based on distance to the camera. This module was definitely one of the hardest in my third year, and I had a lot of fun learning graphics at this lower level.

<img src="../../../../images/Shader-Scene/Shader-Scene-Complete.png" alt="Completed version of shader scene!" width="500" height=auto>

For full details on any problems mentioned on this page follow this link to see the full devlog on github! [Github: DirectX Shader Scene](https://github.com/dippy2214/Custom-Shaders-Scene)
{:.faded}

The most difficult challenge to overcome in this project was undoubtably the tessellation. My program uses this technique to give a higher resolution for objects close to the camera and a lower resolution to objects far away, but this creates some problems. The most glaring of these is the seams between the different resolution areas, since as we transition to more detail on the same model with more triangles, each triangle stops lining up together in a continuous shape.

<img src="../../../../images/Shader-Scene/Tessellation.png" alt="Visual show of the tessellator" width="500" height=auto>

Unfortunately due to time constraints on this project I couldn't completely solve this issue, however I did come up with an algorithm to make this effect less visible in the final product by limiting it to only edges along one axis rather than two. It is a shame I didn't have time to completely solve this problem, as it was very interesting to me, but I am happy that I implemented a partial solution rather than nothing in the time I had. 

This project represents a large lesson in time management for me. Running alongside two other modules, this one was undoubtably the most intensive of the three and required the most work. However, it was very important for me not to get sucked into this project and forget about the other two modules (Gameplay Mechanics in UE5 and Gameplay AI). Balancing these three and my interest in each was demanding but rewarding, and I am happy with the work I have done in all of them.