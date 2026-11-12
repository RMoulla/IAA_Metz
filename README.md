# Formation IAA — Metz

**L’IAG pour chefs de projet, analystes, développeurs et architectes SI**

**3 et 4 novembre 2026 · Redha Moulla**

Ce dépôt rassemble les exercices et ressources pratiques de la session.

## Accès rapide

| Ressource | Accès |
| --- | --- |
| TP Prompting : rédaction, extraction et analyse de données | [Lire les exercices](TP_Prompting.ipynb) · [Ouvrir dans Colab](https://colab.research.google.com/github/RMoulla/IAA_Metz/blob/main/TP_Prompting.ipynb) |
| Données pour l’exercice d’analyse immobilière | [Télécharger selogerdata.csv](https://raw.githubusercontent.com/RMoulla/IAA_Metz/main/selogerdata.csv) |
| Skill : passer d’un besoin aux spécifications | [Lire le Skill](SKILL.md) |

## Télécharger les fichiers

Ouvrez le fichier souhaité, puis utilisez **Download raw file** sur sa page GitHub. Pour un fichier texte affiché dans le navigateur, enregistrez-le en conservant son nom et son extension.

Pour récupérer l’ensemble du dépôt, utilisez **Code → Download ZIP**, puis décompressez l’archive.

## Réaliser le TP Prompting

Le [notebook](TP_Prompting.ipynb) contient quatre exercices :

1. Rédiger un post LinkedIn en respectant des contraintes de structure, puis critiquer la réponse.
2. Comparer les réponses à deux formulations pour observer l’effet du ton.
3. Extraire les informations d’un texte et produire un JSON structuré.
4. Analyser un fichier de données et présenter les résultats.

Les cellules contiennent des **consignes à lire et des prompts à copier dans votre assistant IA**. Ce TP ne nécessite aucune exécution de code ni configuration de clé API. Vous pouvez le consulter directement sur GitHub ; Colab est une autre façon de le lire et d’en conserver une copie.

Pour l’exercice 4 :

1. Téléchargez [selogerdata.csv](selogerdata.csv).
2. Joignez ce fichier à une conversation dans un assistant capable d’analyser des fichiers.
3. Copiez le prompt de l’exercice.
4. Examinez les tableaux, les graphiques et les limites de l’analyse ; demandez des précisions sur les résultats qui vous paraissent incertains.

## Passer d’un besoin aux spécifications

Le fichier [SKILL.md](SKILL.md) propose une méthode pour clarifier un besoin d’application ou une évolution fonctionnelle, puis rédiger des spécifications avec des critères d’acceptation observables.

Utilisez-le dans un outil prenant en charge les Skills, ou joignez son contenu à votre assistant en lui demandant d’appliquer la méthode à votre besoin.

L’entretien prévoit **cinq questions maximum, validation comprise**, posées une à une. Le document produit précise l’objectif, le périmètre, le parcours utilisateur, les exigences, les données et les points restant à clarifier.

Pour commencer, décrivez le problème métier et le résultat attendu. Relisez ensuite les spécifications et vérifiez que les critères d’acceptation correspondent à votre besoin.
