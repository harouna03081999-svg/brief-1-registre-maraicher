# Fiche individuelle

> Une page, avant la livraison. 
# Prénom et nom: HAROUNA BAMBA
# Compte GitHub: harouna03081999-svg!

1. **Une fonction que j'ai écrite**, et comment elle marche : trierParCout (dans src/recherche.js).
   Elle reçoit le registre et renvoie une copie triée par coût croissant. [...operations] fabrique la copie, pour que sort ne modifie pas le registre d'origine. sort reçoit un comparateur numérique, (a, b) => a.coutFCFA - b.coutFCFA : un résultat 
   négatif place a avant b. Sans comparateur, sort comparerait des textes et placerait 15000 avant 2000.


2. **Une difficulté, et sa solution** : En lançant le menu, ce que je tapais s'affichait deux fois (1 donnait 11) et le choix « Ajouter » plantait avec « Cannot read properties of undefined ». La première cause était ouvrirSaisie() appelé dans afficherMenu, donc à chaque tour de boucle : plusieurs lecteurs de clavier s'ouvraient. Je l'ai déplacé pour qu'il ne soit appelé qu'une fois au début de main. La seconde cause était la fonction ajouter incomplète : la saisie envoyée à ajouterOperation n'avait que l'identifiant. J'ai ajouté les six questions.


3. **L'entraide** (qui m'a aidé, qui j'ai aidé, sur quoi) : 

   *Ceux qui m'ont aidé :*
   - LIADE MARC HENOC EBENEZER : lecture/écriture du fichier JSON (stockage.js) ·
   - YAO YEBOUAH JEAN CLAUDE MONDESIR : règles de vérification d'une opération (verifierOperation) · recherche et tri ·
   - DADIE EBEY JEAN-MARIE MICHEL : test de mon programme comme camarade testeur · problème de saisie en double dans le menu (ouvrirSaisie)

   *Ceux que j'ai aidés :*
   - KOUTOUAN AKUI ANGE CYRIACK : comprendre async/await
   - AGBEKE ALICE : comprendre filter et find 
   - VIEGNEROU KOFFI BOGAR : écrire la fiche agronomique  corriger une erreur dans app.js · faire un git commit
   - ISMAEL AMUSA : remplir le dictionnaire des données 

 J'ai utilisé un assistant IA (Claude) pour comprendre les notions (async/await, sort, objets), relire mon code et diagnostiquer mes erreurs. Il m'a aussi fourni du code que j'ai retapé et adapté, et il est cité dans docs/journal-recherche.md. 
