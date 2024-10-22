VOILE ROTATIVE



Voilure d'éolienne à axe vertical vectorielle.


Version 0.01 "Pelton-like" : 

Modifiable sous Blender, le mesh est définit via deux courbes de bézier :

. La première est verticale et n'est pas une courbe mais une simple ligne droite, composée de 3 points de contrôle, dont le point central subit une rotation autour de l'axe Z (propriété Tilt) de 75 degrés. 

. La seconde représente la section. 


Un allésage central doit être ajouté via une opération booléenne de type "différence" entre : le mesh de la voile, et un cylindre du diamètre voulu (la barre choisie), placé au centre de la scène, possédant une hauteur suffisante pour dépasser de la barre traversant verticallement cet objet (sur Z). 


La forme obtenue est à transformer en mesh avant export en .STL et impression 3D. 


Par exemple sur mon prototype, j'ai choisi une barre de 5mm, un diametre de 200mm pour chaque voile, ce qui implique une hauteur de 193mm.

Empilable verticalement : addition du couple de chaque voile.

Redimmensionnable       : si vous disposez d'une grande imprimante.

Modifiable              : fichier source disponible. (via Blender https://www.blender.org/ )

Licence                 : This work is licensed under Creative Commons Attribution-NonCommercial 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc/4.0/

Please give some hits over here, ty : https://www.3DLibre.com
Par Luis David Campos Venancio (aka Meta_4), Portugal.
