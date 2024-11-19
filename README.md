![image](https://github.com/user-attachments/assets/ab54a4f3-4ea6-492b-bec8-e158a915a17c)

# Fake Volumetric Light Shader
![Unity Version](https://img.shields.io/badge/Unity-6000.0.27%27LTS%2B-blueviolet?logo=unity)
 
A simple fake volumetric light shader effect. It was created for Serious Point Games as part of my studies in shader development. 
It is meant to be for Unity URP (6000.0.27f1) but it can work in some older unity versions (like 2022) and other pipelines (like Built-In).

This method of using a material shader to fake volumetric lighting is often used to save on computer resources & computational power, 
to be able to run on lower end devices better, or sometimes it can be due to the designer's artistic direction for the game.

You can refer to the effect's documentation for more info (should be in the repo and its release as a PDF file).

## Features
- Be able to add a noise texture to the light, using a custom noise texture or a built-in simple noise texture
- Replicates the look of a volumetric light, specialized specifically for spot lights
- The color of the light can be customized

## Example[s]
![image](https://github.com/user-attachments/assets/9ab5895e-8e63-4a1d-bf29-5d48652cc655)
<br>
The Look of the shader effect in the dark

## Installation
1. Clone repo or download the folder and load it into an unity project.
2. Create a new material from the shadergraph, or use the provided one if you want to.
3. Drag the material onto the mesh object/gameobject that you want to apply the effect on, or go to the object’s inspector panel
and change its material to the material with the volumetric spotlight shader.
4. Optionally, you can use one of the prefabs to have a volumetric spotlight by going to the prefab folder and drag one of them into the scene.

## Credits/Assets used
Some of the shadergraph code is based on MrTriPie’s Unity Volumetric Light Shader Graph
for LWRP Youtube Video [-Youtube Video Link-](https://www.youtube.com/watch?v=rihJzWq7sE4).
<br>
<br>
The provided volumetric light shaft mesh is also from MrTriPie's Unity Volumetric Light
Shader Graph for LWRP Youtube Video tutorial through its provided download link.
