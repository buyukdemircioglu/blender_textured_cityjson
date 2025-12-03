# This repository contains Blender add-on for visualizing textured CityJSON 3D city models of the paper: [Generating photorealistic urban digital twins with Occlusion-Aware texture mapping](https://doi.org/10.1016/j.jag.2025.105002).

![alt text](blender.png)

Example datasets:

[Enschede Textured CityJSON LOD 1.2 Dataset](https://drive.usercontent.google.com/download?id=1HIomrzAQiEE0HgpGLyZ2UbNrG80UVYRA)

[Enschede Textured CityJSON LOD 2.2 Dataset](https://drive.usercontent.google.com/download?id=1OY5vqxYPPgQzs0H7ISwHZxJY841BE98u)

<br>

How to install add-on:

- You can watch [video](https://drive.google.com/file/d/19cG-ptgJLJb3qyrRvlm3SbPwlwd2GsIh/view) (please change quality to 1080p from settings)

<br>

or follow step-by-step guide:

- Download [blender_textured_cityjson.zip](blender_textured_cityjson.zip)
- Install [Blender](https://www.blender.org/download/lts/4-5/) software
- After opening Bender software, go to Edit → Preferences → Add-ons → Click dropdown menu on top-right → Install from disk → Select .zip file
- Go to Edit → Preferences → Add-ons and activate Textured CityJSON Importer
- Press N to open left menu in 3D Viewport then click CityJSON → Import Textured CityJSON → Select textured CityJSON file and import
- Hide or remove Camera, Cube and Light from top-right menu
- Then click View (top-left) → Frame all
- Change view distance with View (top-right) → End from 1000 to 10000
- Press Z or use top-right menu to switch between wireframe, solid and material preview

<br>

Remove grids from background:
- Edit → Preferences → Themes → 3D Viewport → Grid → change Alpha value to 0 (Default 0.502)

Change background to white:
- Edit → Preferences → Themes → 3D Viewport → Theme Space (below) → Gradient colors → change Gradient High/Off value to #FFFFFF (White)

