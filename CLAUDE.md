# Guides - Contexte projet

## Description
Site statique de guides et tutoriels techniques, deploye via GitHub Pages.

## Stack
- HTML/CSS statique (pas de framework)
- GitHub Actions pour le deploiement
- Theme Tokyo Night (voir assets/style.css)

## Conventions
- Contenu redige en francais
- Commentaires de code en anglais
- Nommage en snake_case (fichiers, dossiers, classes CSS)
- Un dossier par guide dans guides/

## Branches
- main : production (deploiement automatique)
- dev : developpement courant
- feature/ et fix/ : branches de travail

## Workflow
1. Developper sur dev ou feature/
2. PR vers main pour publier
3. Le deploiement GitHub Pages se declenche automatiquement sur push main
