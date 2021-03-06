# FilamentExtruder

<img src="https://github.com/Digifabturing/FilamentExtruder/blob/master/extr01.jpg" width="100%"/>

### Introduction:

The Claystruder project is part of the digifabTuring research, that are a research
cluster focused about digital fabrication + robotic automation and material research
applied in the field of architecture, interaction design and art.
digifabTuring rises from a collaboration between several partners: Fablab Torino,
Officine Arduino, Co-de-iT with COMAU and Toolbox Coworking.

We have adapted an FDM Extruder system (E3D Titan) to use it with a COMAU NJ60 anthropomorphic arm.

We have developed a Grasshopper definition to, that allow the user to generate the
printing toolpath in a simple way. The definition was created to:
- transform toolpath curves into data to control a 6 axis robot movements
- convert the data to COMAU robot programming language PDL2
- do a raw preliminary check of possible collisions between the robot and
  surrounding objects (basically the work area plane)
- control a clay extruder and simulate its material extrusion path and deposition

<img src="https://github.com/Digifabturing/FilamentExtruder/blob/master/extr03.jpg" width="100%"/>
<img src="https://github.com/Digifabturing/FilamentExtruder/blob/master/extr00.jpg" width="100%"/>


A project of [digifabTuring](http://digifabturing.tumblr.com/)
Developed by:

  Stefano Paradiso from [FablabTorino](http://fablabtorino.org/)/[Officine Arduino](http://local.arduino.cc/torino/), Andrea Graziano, Marco Palma and Alessio Erioli from [Co-de-iT](http://www.co-de-it.com/)
