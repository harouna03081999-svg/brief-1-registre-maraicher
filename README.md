# Registre des opérations maraîchères

> Projet individuel du SAS DFS, brief 1 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte

✏️ *En cinq à huit phrases : qui utilise l'outil (son métier, son geste professionnel), son besoin, ce qu'il saisit, ce que le programme lui affiche, ce que l'outil ne fait pas.*

Ce registre est destiné à la responsable d'une exploitation maraîchère pédagogique, qui observe ses parcelles, identifie la culture et l'opération réalisée, puis note la date et le coût. Aujourd'hui elle écrit tout dans un carnet papier : les oublis sont fréquents et retrouver une intervention est long. Son besoin est de saisir ses opérations dans un terminal, de les retrouver et de totaliser les dépenses par parcelle. Elle saisit pour chaque opération un identifiant, une date (AAAA-MM-JJ), une parcelle, une culture, un type d'opération (semis, arrosage, désherbage, repiquage ou récolte) et un coût en FCFA. Le programme affiche la liste des opérations, les résultats de recherche et de tri, et une synthèse : total des dépenses, total par parcelle, coût minimum et maximum. L'outil n'enregistre aucun revenu, donc il ne calcule ni bénéfice ni rentabilité.


## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-1-registre-maraicher.git
cd brief-1-registre-maraicher
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

✏️ *Cochez seulement ce qui marche : `- [x]`.*

- [x] Données lues et enregistrées dans `donnees/operations.json`
- [ ] Ajouter une opération, saisies invalides refusées sans arrêter le programme
- [x] Lister les opérations, message si le registre est vide
- [x] Rechercher par identifiant ou par parcelle ; filtrer par culture
- [x] Trier par coût ou par date
- [x] Synthèse : total, nombre et total par parcelle, coût minimum et maximum
- [x] Bonus : supprimer et modifier une opération (choix 6 et 7)
- [x] Bonus : tri par coût décroissant, parcelle la plus coûteuse

## Données

✏️ *Le fichier, le nombre d'opérations, les champs (voir [docs/dictionnaire-donnees.md](docs/dictionnaire-donnees.md)), les unités. Rappelez qu'elles sont fictives.*

## Limites

✏️ *Au moins trois. Par exemple : le registre enregistre des dépenses, pas les revenus, il ne mesure donc pas la rentabilité.*

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

✏️ *Prénom et Nom :HAROUNA Bamba
 compte GitHub : 
 Entraide : avec qui, sur quoi.*

*Ceux qui m'ont aidé :*
   - LIADE MARC HENOC EBENEZER : lecture/écriture du fichier JSON (stockage.js) ·
   - YAO YEBOUAH JEAN CLAUDE MONDESIR : règles de vérification d'une opération (verifierOperation) · recherche et tri ·
   - DADIE EBEY JEAN-MARIE MICHEL : test de mon programme comme camarade testeur · problème de saisie en double dans le menu (ouvrirSaisie)

   *Ceux que j'ai aidés :*
   - KOUTOUAN AKUI ANGE CYRIACK : comprendre async/await
   - AGBEKE ALICE : comprendre filter et find 
   - VIEGNEROU KOFFI BOGAR : écrire la fiche agronomique  corriger une erreur dans app.js · faire un git commit
   - ISMAEL AMUSA : remplir le dictionnaire des données 
