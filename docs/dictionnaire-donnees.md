# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ      |   Signification                | Type  | Règle de validation          |  Unité           |  Exemple  |
| -----------| -------------------------------| ----  |  ----------------------------|  ----------------|  ---------|
| `id`       | Identifiant unique             | texte | Texte(majuscules)            | Aucun            | O01       |
| `date`     | Date de l'operation            | texte | AAAA-MM-JJ                   | Aucun            | 2026-11-03|
| `parcelle` | surface delimité               | texte | Texte(majuscules)            | Aucun            | P1        |
| `culture`  | plante cultivée sur la parcelle| texte | texte(minuscule)             | Aucun            | tomate    |
| `operation`| intervention humaine           | texte | une des 5 valeurs            | Aucun            | arrosage  |
| `coutFCFA` | Depense enregistrée            | nombre| un nombre positif ou nul     | FCFA             |  3000     |


**Listes de valeurs autorisées** : semis, repiquage, arrosage, désherbage, récolte.

**Sources** :  SUJET.md (section « Les données »), donnees/operations.json, fiche de référence agronomique remise par le coach.

