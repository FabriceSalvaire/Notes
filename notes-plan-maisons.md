Notes Autodesk
- Fusion and Inventor uses the kernel https://en.wikipedia.org/wiki/ShapeManager
  https://ekinssolutions.com/wp-content/uploads/2018/11/GeometryAndBRep-AU2018.pdf
  
- les objets n'ont pas d'id, la fonction id() renvoie le pointeur d'un wrapper et la valeur est souvent identique, implementer un attribut
- la doc pourrait être mieux formater pour les devs
- debug non fonctionnel avec visual studio code, lint ???
- on n'a pas accès à stdout/err pour debug
- l'interface n'est pas pratique pour recharger un addin
- la ligne de commande est très basique versus ipython
- SWIG !!!
- l'API pourrait être plus pythonique ou mieux documenté en ce sens
- si le script par en vrille on ne peut pas le killer

Notes Fusion
- selectionner le mode orthographic sinon il y a un decalage en vue de dessus
- fusion orbit
  use shift + wheel button click to set the orbit center, use right click menu to reset/set
  press shift + wheel button and move to orbit
  constrained orbit is enabled on the lightened circle and the four cross bars : it is only visible when the object is small
  
Formats
 - DWF Format Autocad natif
   exporte les sketchs et objets
 - DXF
 - Autodesk Inventor
 - FBX FilmBox Autodesk
   https://fr.wikipedia.org/wiki/FBX
 - Step Standard ISO
   https://en.wikipedia.org/wiki/ISO_10303
   exporte objets
 - Iges
 - STL
   https://en.wikipedia.org/wiki/STL_(file_format)
 - SketchUp
 - SMT Shape Manager
 - OBJ
   https://fr.wikipedia.org/wiki/Objet_3D_(format_de_fichier)
   ASCII text format
 - SAT Spatial's ACIS solid modeling format
   https://en.wikipedia.org/wiki/ACIS#File_format
   ASCII text format

Schemas
- Plan de masse avec l empreinte de la maison le mur mitoyen est oriente selon l axe y
- Vue de cote indiquant les niveaux de hauteur

Questions
- tracage dalle

A faire
- cave
  finir mur terrasse
- etage
  corriger hauteur mur sous-pente
  profile chassit redondant
  poutre SB a 42 cm du bord du carrelage
- reorganiser en bloc objet vers la fin

----

verifier meuble amis
verifier projection toit
cave bleu
simplifier RDC
mur etage

effacer mur etage inutile
deux splits successifs
escalier decalage de la premiere marche
profile du placo

