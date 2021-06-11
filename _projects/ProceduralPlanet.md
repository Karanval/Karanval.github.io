---
layout: project

project_title: "Procedural Generation of Planet Terrain"
type: "Project"
project_url: "https://github.com/Karanval/aig_pcg"
where: "Algorithms in Games"
year: "Spring 2020"

tags: 
   - "Unity"
   - "C#"
   - "PCG"
   - "Noise"
   - "Animation"

meta:
   keywords: "project, game programming, algorithms in games"

image: "/assets/images/projects/proceduralPlanet/planets2.gif"
image_alt: "Dreamers image"
images:
   # - "/assets/images/projects/proceduralPlanet/planets2.gif"
   - "/assets/images/projects/proceduralPlanet/planets.gif"
   - "/assets/images/projects/proceduralPlanet/resolutions.PNG"
   - "/assets/images/projects/proceduralPlanet/shapes.PNG"
   - "/assets/images/projects/proceduralPlanet/oceanAnimation.PNG"
   - "/assets/images/projects/proceduralPlanet/planetNoise.gif"
   - "/assets/images/projects/proceduralPlanet/planetNoise2.gif"
---
This is about procedural generation of planets, where I took a large focus on customization of colors and shapes. The planets are created starting from a cube and then modifying its vertoces to be a sphere, once that is done, a noise can be added to the vertices (with certain control variables) to give them different altitudes. 

The planets have an ocean, where the original sphere is drawn, but the dept is kept so that it can be used for painting the shore (artistic purposes).

The planets can be animated, either in using a noise that doesn't move the vertices, or one that breaks them to create new shapes.