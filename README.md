Rotating Sail : Vertical Axis Wind-Turbine
By Luis David de Campos Venancio (aka Meta_4), 
Santiago-do-Cacem, Portugal. 2025-04. 
Version: Alpha 0.03
https://www.3DLibre.com


Licence: This work is licensed under Creative Commons Attribution-NonCommercial 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc/4.0/


__________________________________________


Vertically stackable: you can put 3 rotating sails or more on the same axis = More TORQUE with low wind.


Scalable: if you own a BigRep (or some other big 3D-printer), scale it as you like. Thought, at small scales you can make it thicker. And at bigger scales, it might need reinforcements.


Editable with Blender, the "rotating sail" is defined by 2 bézier curves:

. The first one is vertical and is not a curve but a straight line, composed of 3 control points.
The central control point has a tilt rotation angle of 75°.

. The second bézier curve is the section of the rotating sail. Yes you can try other shapes, and see the result in real time with Blender. But then you have to try it in real conditions.

To transform it to a 3D-printable mesh, you have to convert the sail with the menu "Object / Convert / Mesh" after duplicating it in order to keep a backup, as shown in the #1 screenshot.

To create the vertical axis hole, just add a vertical cylinder and use a boolean modifier on the sail as shown in the #2 screenshot.

Export to .STL then 3D-print with the settings you like. 


Change log:
0.01 : only the rotating sail is here
0.02 : thicker version
0.03 : Added all the rest... including the electric module (needs work on gears_0-01.output to fix a motor shaft with 2.5mm screws and nuts). Sorry about the dimensions/scale problem. Correcting it ASAP (but not fatal).
