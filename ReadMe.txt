Le problème :
A ce point de contrôle, on vous demande d'écrire un algorithme qui lit une phrase, qui se termine par un point,
caractère par caractère, et de déterminer :
 

Instructions
La longueur de la phrase (le nombre de caractères).
Le nombre de mots dans la phrase (en supposant que les mots sont séparés par un seul espace).
Le nombre de voyelles dans la phrase.
Vous devez garder à l'esprit que :

Chaque caractère sera traité séparément.
Le dernier caractère est le point.
Utilisez trois variables comme compteurs.

La solution:
-Pour commencer j'ai initialise mes compteurs: cptC pour compter les caractère et cptV pour les voyelles a 0, 
par contre pour le cptM qui comptabilise les mot a 1 parcequ'on commence par un mot dans la phrase.
-Je lis la phrase et j'initialise mon caractère l a la premiere lettre.
-J'ai utilise une boucle while avec la condition d'arret <> '.', tanque je ne suis pas arrivee à la fin de la phrase
je commence par 
      *incrémenter le cptC;
      * je fais deux tests et je compare le caractère courant a l'une des voyelles en miniscule ou majuscule;
       si je suis arrivée a un espace cela veut dire un mot, 
       j'incrémenter mes compteurs une fois trouver
- A la sortie de la boucle cela veut dire fin de phrase: arrivee au point, j'incremente mon cptC pour comtabiliser 
le point qui est un caractère qui n'a pas ete traiter par la boucle, 
-enfin on affiche les resultats: les trois compteurs

 





