___________      Voile Rotative     ___________


       (translation to english incoming)

       
___________ EOLIENNE A AXE VERTICAL ___________



Version 0.03 : Electric module almost complete (needs work on gear_output to fix a motor shaft with 2.5mm screws and nuts).

Modifiable sous Blender, le mesh est définit via deux courbes de bézier :

. La première est verticale et n'est pas une courbe mais une simple ligne droite, composée de 3 points de contrôle, dont le point central subit une rotation autour de l'axe Z (propriété Tilt) de 75 degrés. 

. La seconde représente la section. 


Un allésage central doit être ajouté via une opération booléenne de type "différence" entre : le mesh de la voile (dupliquer puis convertir en mesh), et un cylindre du diamètre voulu (le pivot), placé au centre de la scène, possédant une hauteur suffisante pour dépasser de la voile (sur Z, attention à X et Y). 

Exemple : diamètre du cylindre 5 mm => voile redimensionnée pour atteindre 20cm sur Z => créer un cylindre de 21 cm de hauteur. 


Exporter en .STL et imprimer en 3D. 


Empilable verticalement : addition du couple de chaque voile.

Redimensionnable       : si vous disposez d'une grande imprimante ou souhaitez tester une miniature de 5 cm en 30 exemplaires...

Modifiable              : fichier source .blend disponible. (modifiable avec Blender https://www.blender.org/ )

Licence                 : This work is licensed under Creative Commons Attribution-NonCommercial 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc/4.0/

Merci de visiter : https://www.3DLibre.com
Par Luis David Campos Venancio (aka Meta_4), Portugal.
