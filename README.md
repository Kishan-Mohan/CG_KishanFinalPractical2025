# CG_KishanFinalPractical2025
Computer Graphics Final Exam Practical - Kishan Mohanakanth 100921637
In this Unity project, the game chosen is the odd number one, creating Wario Land 3 in Unity 6.2 3D. The following shaders implemented are the Stencil, Toon, water, and polygon surface deformation shaders. The wario model is made and textured by me (my GDW character model) 

Second half shader, Water shader: The water shader is done in shader lab code, and it is applied to the water plane object in the scene. To create this type of water I changed the tint in the Base Colour property to match with the reference image, to get the number of waves I changed the value on the frequency, speed and amplitude. I noticed that in the screenshot of the game there are these little triangle points that look like water waves in retro games. 
First half shader, Toon Shader: The Toon shader is done in a shader graph, and it is applied to the player model called “Wario”  and the enemy capsule in the scene. To create this type of effect I added a custom toon ramp with large spaces for the gradients. To create the outline of the object I changed the game's light source rotation to fit with the sample. 
Stencil: The Stencil shader is added to the Donut stencil object in the scene and it's applied to make the hole see through for the donut just like real life donuts. 
Polygon Surface Deformation: This shader is implemented to the background wall where all the mountains are behind Wario scroll or move according to Wario position, by adding a stone texture and by messing with the scales X and Y I was able to match it with the sample screenshot. 

Stencil Diagram: In the PDF 

