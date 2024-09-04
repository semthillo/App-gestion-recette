# Gestion de Recettes

## Description du Projet

Ce projet est une application de gestion de recettes développée avec Vue.js, utilisant Pinia pour la gestion d'état et Bootstrap pour le style. L'application permet d'ajouter, modifier, afficher, et supprimer des recettes. Chaque recette contient un titre, des ingrédients, un type, et une image. L'interface utilisateur est conviviale et réactive grâce à Bootstrap.

## Fonctionnalités

- **Affichage des recettes :** Les recettes sont affichées sous forme de cartes Bootstrap avec une image, un titre et un bouton pour voir plus de détails.
- **Ajout de recettes :** Les utilisateurs peuvent ajouter de nouvelles recettes en remplissant un formulaire.
- **Modification de recettes :** Les utilisateurs peuvent modifier les détails d'une recette existante.
- **Suppression de recettes :** Les utilisateurs peuvent supprimer une recette de la liste.
- **Affichage des détails :** Les détails d'une recette sont affichés dans une fenêtre modale  Bootstrap.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les éléments suivants sur votre machine :

- [Node.js](https://nodejs.org/) 
- [npm](https://www.npmjs.com/)

## Installation

Suivez les étapes ci-dessous pour configurer et démarrer le projet localement.

### 1. Cloner le Dépôt

Clonez ce dépôt sur votre machine locale en utilisant Git :

```bash
git clone https://github.com/semthillo/App-gestion-recette.git
```
### 2. Accéder au Répertoire du Projet

Accédez au répertoire du projet :

```bash
cd App-gestio-recette
```

### 3. Installer les Dépendances
Installez les dépendances nécessaires avec npm :

```bash
npm install
```

### 4. Démarrage de l'Application
Une fois les dépendances installées, vous pouvez démarrer l'application en mode développement :

```bash
npm run dev
```

### 5. Instructions pour Ajouter une Recette
Cliquez sur le bouton "Ajouter une nouvelle recette" sur la page d'accueil.
Remplissez le formulaire avec le titre, les ingrédients, le type, et l'image de la recette.
Cliquez sur "Enregistrer" pour ajouter la recette à la liste.

### 6. Instructions pour Modifier ou Supprimer une Recette
Sur la carte de la recette, cliquez sur le bouton "Plus d'info".
Dans le modal qui s'ouvre, vous pouvez soit cliquer sur "Modifier" pour éditer la recette, soit sur "Supprimer" pour la retirer.



### Technologies Utilisées

Vue.js - Framework JavaScript pour créer des interfaces utilisateur
Pinia - Gestionnaire d'état pour Vue.js
Bootstrap - Framework CSS pour la création d'interfaces utilisateur réactives

### Auteur

[Seme Thillo](https://github.com/semthillo)