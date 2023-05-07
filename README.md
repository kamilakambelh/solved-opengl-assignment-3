Download Link: https://assignmentchef.com/product/solved-opengl-assignment-3
<br>
Task

Write an OpenGL program that displays a simple textured 3D scene with lighting. Using AntTweakBar, create a Graphical User Interface (GUI) for the user to control the various settings. Figure I shows an example of the scene taken from two different viewpoints with different properties.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/02/624.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/02/624.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>




The 3D scene (3 marks)

o Construct a room with four walls and a floor (no ceiling). Create the room by specifying vertex positions, surface normals and texture coordinates.

The room should contain:

• Two paintings, which are hung on separate walls

A rotating ornament (load a mesh from a model file) on top of a cube pedestal in the centre of the room

A tinted glass room partition somewhere in the room




Your program should have a movable camera that the user can control using keyboard and mouse input. To keep camera rotation separate from interaction with the GUI, only allow camera rotation when the right mouse button is pressed and held.

Lighting and textures (2 marks)

o The room should be lit.

• A single light source is sufficient Allow the user to adjust the position/direction of the light source

o Use different images to texture each of the following:

• Walls

Floor

Pedestal

Paintings

Normal mapping (2 marks)

Render the walls ofthe room with normal mapping.

Cube environment mapping (2 marks)

Render the ornament (on the pedestal) using cube environment mapping.

Allow the user to control the intensity of cube reflection.

Translucent surface (2 marks)

The tinted glass room partition (use a plane with alpha blending) should be a translucent surface.

o Using the GUI, the user should be able to control the amount of translucency and the colour of the tint.

Screen capture (2 marks) When the user presses ‘O’ , your program should take a screen capture and save it into an image file.

o Also, when the user presses ‘9’, take a screen capture and display this image as one of the paintings in the room. Reflective surface (2 marks)

The floor of the room should a reflective surface. Use the stencil buffer and blending for this.

Provide an option in the GUI for the user to control the intensity of the reflection.