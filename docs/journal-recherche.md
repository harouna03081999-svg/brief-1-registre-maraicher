# Journal de recherche

> Chaque recherche utile : ce que vous cherchiez, où (cours, [MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript), [Node.js](https://nodejs.org/api/), un camarade, une IA…), ce que vous avez compris. Ce que vous gardez, vous devez pouvoir l'expliquer.


| Ce que je cherchais | Où | Ce que j'ai compris | Utilisé dans |
| --- | --- | --- | --- |
| Comment lire un fichier JSON |Claude (IA) et un camarade(LIADE MARC HENOC EBENEZER)| readFile lit le fichier en texte, JSON.parse le transforme en tableau d'objets utilisable. Il faut await, car la lecture prend du temps. | src/stockage.js (chargerJson) |
| Comment écrire et créer un fichier JSON |Claude (IA) et un camarade(LIADE MARC HENOC EBENEZER)|JSON.stringify(donnees, null, 2) transforme les objets en texte lisible (indenté de 2 espaces), et writeFile l'enregistre : le registre garde sa mémoire. | src/stockage.js (enregistrerJson) |
| Comment le code attend une réponse (async / await, try / catch) |Claude (IA) et un camarade(LIADE MARC HENOC EBENEZER)| await met le code en pause jusqu'au résultat. try / catch attrape une erreur (fichier absent, JSON cassé) et affiche un message clair au lieu de planter.| app.js (main), src/stockage.js |
