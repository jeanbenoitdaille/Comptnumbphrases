# Comptnumbphrases
Compter le nombre de phrases dans un texte 
Un problème en apparence complexe pour une solution très simple. Comment compter le nombre de phrases dans un texte ?

Aucunement besoin de boucle ou autre structure complexe pour se faire.
Il suffit de se demander ce qui définit une phrase : tout simplement un point.

Il nous suffit donc de compter le nombre de points dans le texte pour compter le nombre de phrase.

Nous utilisons donc la méthode 'count' sur notre chaîne de caractère pour compter le nombre de points :

    lorem.count(".")
