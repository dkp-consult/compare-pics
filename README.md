# Synthese et présentation du projet

L'idée est de mettre un place un repo qui permet de faire de coder de voir le résultat en direct (live server), mais aussi de comparer avec le rendu souhaité. L'idée était de me faire ça et de pas en parler, et puis je me suis dis que d'autres personnes étaient peut-être soulée de par savoir comparer leurs css avec le résultat attendu.

Au départ, c'était simplement pour le 100Days CSS Challenge, mais je me suis motivé et je me suis dis qu'il devait y avoir un moyen de rendre le tout utilisable pour plus et je me suis dis que partager ses avancées, sa conceptions était une bonne idée.

Ca fonctionnera, ou pas, on verra.

# But de sa publication :

Le but de l'avoir publié n'est pas d'avoir quelqu'un qui refactorise tout, quelqu'un qui débug les choses ou autres. Le but est vraiment d'avoir un regard extérieur, quand je bloque de chercher, essayer, échouer et recommencer.
Mais aussi prendre les avis des uns et des autres sur les pistes d'améliorations, les choses à faire differrements, etc.
Je n'ai aucun soucis à rendre l'idée communautaire avec la participation d'autres dev, mais j'essayerais avant tout de comprendre et d'avancer.

# Histoire

Lorsque j'ai vu Grafikart réalisé le CSS Battle, son canvas de comparaison m'a tapé dans l'oeil et je me suis dis que c'était trop pratique. Parce que cela permet de coder dans son IDE et de voir le rendu par rapport à ce qui est demandé.

Récemment, j'ai lancé le 100Days CSS Challenge, j'ai été surpris d'utiliser des propriétés que je pensais trop complexe pour mes dix petits doigts, du coup, je me suis dis, allons-y faisons ça.

Hors je trouvais que c'était la galère de comparer sur deux espaces différents et que du coup, la comparaison était approximative. J'ai donc voulu utiliser le canvas de Grafikart pour comparer le tout. Après 1h30 à essayer de faire passer un ifmare dans son système, j'ai laissé tomber et je pense que la structure utilisant les images bloque (surtout au niveau de la superposition).

Donc j'ai un peu cherché et j'ai trouvé qu'il existait un système de slider pour comparer (comme sur Frontend Mentor), un coup de google plus tard, j'ai chopé la ressource de W3S avec le slider tout fait, j'ai regardé le code et BAMMMMMM, bcp plus de javascript que je ne peux en pondre pour l'instant, du coup, j'ai pas tout compris. Mais j'ai pompé le code, purement et simplement, juste pour voir s'il était possible de remplacer les images par des iframes... et la réponse est O-U-I !

J'ai donc voulu mettre en place un système me permettant d'utiliser des iframes pour comparer. La récupération des iframes Codepen étant génante par l'overlay, j'ai fait un folder avec l'ensemble des challenges afin d'avoir le slider qui prend ma zone de travaille et la zone de rendu souhaité.

Et petit à petit, je pense à des choses qui seraient pratique à mettre en place..

# Ressources utilisées :

- Grafikart canvas : https://gist.github.com/Grafikart/b66c512360515b0727f7253a0b6b8f68

- W3S slider : https://www.w3schools.com/howto/howto_js_slideshow.asp

- 100 Days CSS Challenge : https://100dayscss.com/

# To do :
- Création des 100 CSS Challenge (folder ou 1 fichier)
- Faire une présentation plus jolie et lisible
- Expliquer le fonctionnement et essayer de le rendre le + simple possible
- Créer le carnet de bord de mon apprentissage dans cette idée
- Convertir automatiquement le SCSS en CSS dans une balise style ?

# Piste d'amélioration :

- Permette une menu de sélection du CSS Challenge (JS avec un changement dans l'iframe)
- Réecrire le JS pour le slider
- Ecrire le readme en anglais également
- Mettre en place une synthèse du fonctionnement
- UI / UX pourrie
- Trouver d'autre chose à implémenter
- Table des matières pour README
- Synthèse des apprentissage lié au projet
- Superposition des layouts avec animation ; opacity => NOK

# Problème à régler :

- Animation absente (fichier js nok ?)
- Bug du slider
