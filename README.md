# Blender-based Visualization of NASA JPL CNEOS Fireball Dataset

Blender3D is a CGI tool. Here, we use it for data visualization.

![still image demo 1](blender/output/still.001.png)

![still image demo 2](blender/output/still.002.png)

## Full Animation:
![blender animation](blender/output/orbit.001/output0001-0100.mp4)

## Workflow
Use the following blender addon for loading in the CSV file generated by `data/Download And Format CNEOS Fireball Data.ipynb` and then displaying as particle system using geometry nodes:

https://github.com/simonbroggi/blender_spreadsheet_import?tab=readme-ov-file

The blender file in `blender/main.blend` will know how to display the outputs of the notebook. This blender file also knows how to composite in the color spectrums, and shade the area with the topography in the data folder.

## Acknowledgments

A useful demo by CG Figures which deserves credit:

https://www.youtube.com/watch?app=desktop&v=wrLZ6SIE_7c

