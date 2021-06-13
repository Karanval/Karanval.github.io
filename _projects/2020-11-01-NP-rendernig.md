---
layout: project
show: true

project_title: "Non-Photorealistic Rendering"
type: "Project"
project_url: "https://github.com/Karanval/npr"
where: "Graphics Programming course"
year: "Autumn 2020"

tags: 
   - "C++"
   - "OpenGL"
   - "CMake"
   - "Shaders"
   - "Solo roject"
   - "uni"

meta:
   keywords: "project, game programming, graphics programming"

image: "/assets/images/projects/npr/celShading.PNG"
image_alt: "NPR image"
images:
   - "/assets/images/projects/npr/celShading.PNG"
   - "/assets/images/projects/npr/blinn-phong.PNG"
   - "/assets/images/projects/npr/edges.PNG"
   - "/assets/images/projects/npr/edgesOnly.PNG"
   - "/assets/images/projects/npr/lineDistortion.PNG"
   - "/assets/images/projects/npr/randomizedDistortion.PNG"
---
In this project I experiment with non-photorealistic rendering, using cel-shading, edge detection and edge distortion. To achieve the different effects I had 3 rendering passes: the first one to create the cel shading based on a number of cels to shade that renders to a texture. The second pass takes the texture  to create the edge dectection and also reders to a texture. The third pass takes the last texture and distorts the edges.

An important aspect for this project was the use of control variables to change the different rendering parameters live, so that the user can experiment with the different effects.