# Redux avec Vanilla JavaScript

## Description

Ce projet illustre l'utilisation de **Redux** pour la gestion d'état dans une application web construite avec **JavaScript Vanilla**. Il s'agit d'une interface simple permettant de simuler l'achat de produits (téléphones et tablettes) tout en mettant à jour dynamiquement les stocks affichés à l'écran.

## Fonctionnalités

- Visualisation des stocks disponibles pour chaque produit.
- Simuler l'achat de téléphones et de tablettes.
- Mise à jour en temps réel de l'interface utilisateur grâce à **Redux**.

## Structure des fichiers

- **`index.html`** : Contient la structure HTML de l'application.
- **`style.css`** : Gère le style visuel de l'application.
- **`script.js`** : Implémente la logique de l'application, incluant la configuration et l'utilisation de Redux.

## Dépendances

Ce projet utilise **Redux** via un CDN. La librairie est incluse dans le fichier HTML :

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/redux/4.2.0/redux.min.js"></script>
```

## Installation et exécution

### 1. Clonez le dépôt GitHub sur

```bash git clone
https://github.com/pricilliaedou/exo2-Redux.git

```

## Installation et configuration

### 1. Accéder au dossier

Allez dans le répertoire du projet cloné : cd exo2-Redux

## Fonctionnement

- L'application affiche initialement le stock disponible :
  - Téléphones : 5
  - Tablettes : 10
- Cliquez sur les boutons "Acheter" pour réduire le stock correspondant.
- La mise à jour des stocks est gérée par Redux et reflétée en temps réel dans l'interface utilisateur.

### 1. Structure HTML

Chaque produit est affiché dans un conteneur avec :

- Une image.
- Un texte indiquant la disponibilité.
- Un bouton pour effectuer l'achat.

### 2. Style CSS

- Mise en page centrée et responsive.
- Boutons stylisés avec des effets au survol.

### 3. Code Redux

- Actions :

* BUY_PHONE
* BUY_TABLET

- Réducteur :

* Met à jour l'état en fonction de l'action déclenchée.

- Store :

* Configure l'état initial et gère les abonnements pour refléter les modifications dans l'interface.

## Contributions

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.
