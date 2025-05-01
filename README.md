# Automatisation avec un script shell

## Objectif

Apprendre à créer et exécuter des scripts shell pour automatiser des séquences de commandes. Cet exercice vous initiera aux bases des scripts shell, ce qui vous aidera à automatiser des tâches répétitives au fur et à mesure de votre progression dans votre parcours de programmation.

## Commandes à Apprendre

- `chmod` - Modifier les permissions des fichiers
- `./` - Exécuter un script
- `bash` ou `sh` - Exécuter un script avec un shell spécifique
- Syntaxe des scripts shell (variables, commentaires, etc.)

## Exercice

### Partie 1: Création d'un script de configuration de projet

Créez un script shell appelé `setup_c_project.sh` qui effectue automatiquement les opérations suivantes:

1. Crée une nouvelle structure de dossiers pour un projet C avec les dossiers suivants:

   ```
   ./mon_nouveau_project/
   ├── src/
   ├── includes/
   ├── lib/
   └── docs/
   ```

2. Crée des fichiers standard:
   - Un fichier `main.c` vide dans le répertoire `src`
   - Un fichier `project_name.h` vide dans le répertoire `includes`
   - Un fichier `README.md` vide dans la racine du projet
3. Initialise le README.md avec le contenu suivant:

   ```
   # Nom du Projet: [project_name]

   Créé le: [date actuelle]
   Auteur: [votre nom d'utilisateur]

   ## Description

   Ceci est un projet C créé à l'aide d'un script de configuration automatisé.
   ```

### Partie 2: Test du Script

1. Rendez votre script exécutable
2. Testez votre script en créant un nouveau projet
3. Vérifiez que tous les dossiers et fichiers ont été créés correctement

### Partie 3: Documentation

Créez un fichier appelé `script_explanation.txt` à la racine di dossier qui explique:

1. Comment rendre un script exécutable
2. Comment exécuter un script
3. Ce que fait chaque commande dans votre script
4. Comment transmettre des arguments à un script
5. Ce que signifie la ligne shebang (`#!/bin/bash`)

## Résultat Attendu

- Un script shell fonctionnel qui crée la structure du projet lorsqu'il est exécuté
- Structures de dossiers et fichiers correctement créés pour le projet de test
- Explications claires dans le fichier `script_explanation.txt`

## Conseils

- Ajoutez des commentaires à votre script pour expliquer ce que fait chaque section
