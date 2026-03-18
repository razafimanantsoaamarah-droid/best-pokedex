
# Pokédex Application - ReactJS & PokéAPI
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/24de1657-7525-430d-bbe7-e26a7ae7eee2" />

Ce projet consiste en la création d'une application web dynamique permettant d'explorer l'univers Pokémon. Développée en ReactJS, l'application consomme les données de la PokéAPI (v2) et propose une
interface moderne, fluide et responsive.

## Technologies Utilisées

* **Frontend :** ReactJS (Hooks), React Router v6, Tailwind CSS.
* **Gestion d'état :** Context API (Favoris) et LocalStorage.
* **Données :** PokéAPI (REST), Axios / Fetch.
* **DevOps & CI/CD :** GitHub Actions, ESLint, Vercel / Netlify.
* **Outils :** Git, Vite.js / Create React App.

---

## Architecture du Projet

Le projet suit une structure modulaire pour garantir la maintenabilité et la séparation des préoccupations :

```text
/src
  /api          # Services d'appels API et configuration
  /assets       # Ressources statiques (images, polices)
  /components   # Composants réutilisables (Cards, UI Elements)
  /context      # Gestion de l'état global (Favoris)
  /hooks        # Hooks personnalisés (Fetch, LocalStorage)
  /pages        # Vues principales (Home, Details, Favorites)
  /styles       # Configuration CSS et thèmes
  /utils        # Fonctions utilitaires (formatage de données)
```

---

## Fonctionnalités (MVP)

1.  **Exploration :** Liste complète des Pokémon avec pagination ou scroll infini.
2.  **Recherche :** Filtrage dynamique par nom ou par numéro d'index.
3.  **Fiche Détail :** Vue approfondie incluant les statistiques, les types, le poids et la taille.
4.  **Système de Favoris :** Possibilité de marquer des Pokémon, avec sauvegarde persistante via le LocalStorage.
5.  **Interface Responsive :** Optimisation complète pour mobile, tablette et desktop.

---

## Installation et Utilisation

### Prérequis
* Node.js 
* NPM ou Yarn

### Procédure
1.  Cloner le dépôt :
    ```bash
    https://github.com/razafimanantsoaamarah-droid/best-pokedex
    ```
2.  Installer les dépendances :
    ```bash
    npm install
    ```
3.  Lancer l'application en mode développement :
    ```bash
    npm start
    ```
4.  Générer le build de production :
    ```bash
    npm run build
    ```

---

## Déploiement

L'application est déployée automatiquement via une pipeline CI/CD. Toute modification fusionnée sur la branche `main` déclenche un nouveau déploiement sur la plateforme cible.

---

**Projet réalisé dans le cadre de la formation HEI**
