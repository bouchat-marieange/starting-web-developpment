# starting-web-developpment
8-exercice-summary (Exercice HTML-CSS - La Prairie)

## Mon code réalisé pour l'exercice récapitulatif 

J’ai particulièrement aimé cet exercice, car j’ai le design épuré de cette page. Je le trouve très complet, car il fait appel à de nombreuses propriétés css et nécessite de les combiner entre elles. Je ne comprends pas par contre pourquoi dans ce design, le haut des affiches n’est pas aligné en haute ou en bas avec les titres et textes en rapport avec ces affiches. L’alignement à cet endroit me semble étrange ! J’ai tenté de le reproduire, mais sans succès !


## Difficultés rencontrées

Dans la réalisation de cet exercice, j’ai rencontré plusieurs difficultés : 
 
 * utilisation des polices icônes du site http://fontawesome.io/. J’ai dû chercher un moment avant de comprendre comment intégrer leurs codes dans la page, modifier leur taille et leur couleur.
 * dans le menu social, j’ai dû m’y reprendre à plusieurs fois avant de trouver le moyen de centrer les icônes avec le texte correspondant puis a centré l’ensemble. J’ai fini par utiliser un positionnement semblable à ceux d’un menu horizontal fait à partir de ul li a.
 * j’ai encore des progrès à faire dans le positionnement float. Ce type de positionnement me pose régulièrement des problèmes de décalage de contenu. J’ai régler le problème ici en utilisant une div vide entre chaque div de film (affiche + titre et contenu) contenant l’instruction clear : both, pour éviter que le float ne continue sur les autres éléments sans contrôle de ma part (même si j’ai remis un float identiques sur les parties suivantes). Il doit y avoir un moyen plus propre et plus concis de faire cela. Étant donné l’alignement entre texte et image je ne pense pas non plus qu’il ai été fait avec un positionnement en tableau. Notre formateur nous a demandé tant que possible d’éviter le positionnement flexbox pour les positionnements simples. Celui-ci à cependant l’avantage de générer moins de problèmes et de conflits entre les éléments selon ma pratique. Mais cela est probablement dû à mon manque de maîtrise pour l’instant du positionnement float.
J'ai finalement réussi à reproduire l'alignement entre affiches et textes mais en ciblant précisément les titres ou les paragraphes de certaines div de film précise. 
Lorsque j'ai copier mon code enregister dans le docs et envoyer sur GitHub et GitHub page (via docs), il reste un problème d'affichage du texte dans la partie alien qui n'est pas présente dans mon code d'origine et qui effectue le retour à la ligne du dernier mot du texte.Pourtant c'est bien la dernière version du code que j'ai collée dans docs?

 ## Ce que je vais mettre en place pour y remédier

 * Approfondissement du mode de positionnement flexbox jusqu’à bien maîtriser celui-ci.
 * Bien lire la documentation du site http://fontawesome.io/, ainsi que les différentes manières de le mettre en place (lien vers site ou téléchargement de bibliothèque) et de manipuler les icônes, car c’est vraiment un outil très intéressant dont on aura besoin régulièrement.
