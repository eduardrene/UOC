# UOC
Practiques Profesionals

Versió del "cube wireframe" amb cilindres i esferes, que permet modificar les variables mitjançant el menu lateral GUI.

He trobat dos problemes:

1-Si per cada cub que coloco a escena reinicio les arrays "sphere" i "cylinder", visualitzo tot de conya, però al crear l'unió i el stl a la funció save() només imprimeix 1 cub (ja que reinicio l'array a cada animació/frame,

2-Si no reinicio l'array i faig el contrari, és a dir, que cada nou cub ompli espais nous de l'array, al ser una animació... s'omple continuament fins que peta, tingui el número de segmenst o de cubs que tingui. Si cliquem sobre save(), moltes vegades es penja directament.

Els he resolt obligant a ocupar un espai de l'array segons el cub que volem visualitzar. A la funció save() eliminem els espais buits de l'array per permetre la unió i creació del stl.

Depenent del nombre de segments, els arxius que es creen son enormes.

Ja em diràs el què...

Ah, per cert, veuràs que he canviat l'aparença, ho he fet durant breaks per deixar de pensar en aquest problema... el fons és clar com tu volies, jejeje.

PD: penjo també un arxiu stl fet a través de scene (enlloc de la unió), no se si tens alguna eina per veure si apareixen errors d'impressió sense imprimir.
