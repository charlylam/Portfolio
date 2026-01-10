# 💾 Exercices LocalStorage & JavaScript

Projet réalisé dans le cadre de ma formation, axé sur la manipulation du **localStorage** et les bases de JavaScript. L'objectif est de comprendre le stockage local dans le navigateur et de créer des applications web interactives qui persistent les données.

## 🎯 Objectifs du projet

* Comprendre le fonctionnement du localStorage
* Manipuler les données avec JavaScript (CRUD)
* Gérer la persistance des données côté client
* Structurer du code JavaScript propre et maintenable
* Créer des interfaces dynamiques et interactives

## 🧠 Fonctionnalités

### Exercice 1 : Sauvegarde simple
* Saisie et sauvegarde d'une valeur dans le localStorage
* Chargement de la valeur sauvegardée
* Suppression des données stockées
* Gestion des cas où aucune donnée n'existe

### Exercice 2 : Gestion des préférences utilisateur
* Sauvegarde automatique des préférences (nom, couleur, langue, mode sombre)
* Restauration des préférences au chargement de la page
* Valeurs par défaut si aucune préférence n'est définie
* Synchronisation en temps réel

### Exercice 3 : Liste de tâches (Todo List)
* Ajout de tâches avec validation
* Affichage dynamique de la liste
* Modification du statut (terminé/non terminé)
* Suppression de tâches
* Persistance complète des données avec JSON
* Interface responsive et intuitive

## 🛠️ Technologies utilisées

* **HTML5** - Fourni pour l'exercice
* **CSS3** - Fourni pour l'exercice
* **JavaScript** - Logique et interactivité
  * `localStorage` API
  * `JSON.stringify()` / `JSON.parse()`
  * Manipulation du DOM
  * Event listeners
  * Arrow functions
* **Outils** :
  * Git
  * GitHub
  * VS Code

## 📚 Contexte pédagogique

Ce projet a été réalisé dans le cadre d'exercices progressifs de formation JavaScript. Il a été intégré à ce dépôt dans un objectif de portfolio personnel, afin de présenter mes compétences en développement front-end et en manipulation de données côté client.

## ✅ Points d'apprentissage

* Utilisation de l'API localStorage du navigateur
* Sérialisation et désérialisation JSON
* Manipulation avancée du DOM
* Gestion des événements utilisateur
* Création d'éléments HTML dynamiques
* Validation des données utilisateur
* Gestion d'état dans une application web
* Bonnes pratiques JavaScript (DRY, fonctions pures, nommage clair)
* Debugging avec la console navigateur

## 🔧 Concepts clés implémentés

### LocalStorage
```javascript
// Sauvegarde
localStorage.setItem("clé", "valeur");

// Récupération
const valeur = localStorage.getItem("clé");

// Suppression
localStorage.removeItem("clé");
```

### JSON
```javascript
// Conversion objet → texte
localStorage.setItem("tasks", JSON.stringify(tasks));

// Conversion texte → objet
const tasks = JSON.parse(localStorage.getItem("tasks")) || [];
```

### Manipulation DOM
```javascript
// Création d'éléments
const li = document.createElement("li");
li.textContent = "Ma tâche";
list.appendChild(li);

// Event listeners
button.addEventListener("click", () => {
  // Action
});
```
## 👤 Auteur

**[Ton Nom]**

Projet réalisé par **[Charly / Lamena]**
