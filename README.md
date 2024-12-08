
---

# ZACCK MART - E-commerce App

ZACCK MART est une application e-commerce réalisée en utilisant React. Elle permet aux utilisateurs de naviguer dans une boutique en ligne, d'ajouter des articles à leur panier, et de passer à la caisse.

## Fonctionnalités

- **Affichage des produits** : Les utilisateurs peuvent voir une liste de produits avec leurs images, noms et prix.
- **Ajouter au panier** : Les utilisateurs peuvent ajouter des produits à leur panier et voir le nombre d'articles dans le panier.
- **Panier** : Le panier affiche les produits ajoutés, leurs prix et permet de retirer des articles.
- **Authentification** : Options de connexion et d'inscription pour les utilisateurs.
- **Navigation fluide** : Accès facile aux pages `Home`, `Product`, `About`, et `Contact`.

## Captures d'écran

### Page du panier
![Cart Page](image.png)

Dans cette page, l'utilisateur peut voir deux produits :
- iPhone 11 à 750$
- iPhone 12 Mini à 950$

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/votre-repository.git
   ```

2. Accédez au répertoire du projet :
   ```bash
   cd React-Ecommerce-App
   ```

3. Installez les dépendances :
   ```bash
   npm install
   ```

4. Lancez l'application :
   ```bash
   npm start
   ```

   L'application sera accessible à l'adresse `http://localhost:3000`.

## Scripts Disponibles

- `npm start` : Lance l'application en mode développement.
- `npm run build` : Crée une version optimisée pour la production.

## Technologies utilisées

- **React.js** : Framework JavaScript pour la construction de l'interface utilisateur.
- **CSS** : Pour la mise en page et le style.
- **React Router** : Pour la navigation entre les pages.
- **State Management** : Gestion des états avec `useState` et `useReducer`.
- **LocalStorage** : Sauvegarde du panier pour conserver les produits ajoutés.

## Structure du Projet

```
├── public
│   └── index.html
├── src
│   ├── components
│   │   ├── Header.js
│   │   ├── ProductList.js
│   │   ├── Cart.js
│   ├── pages
│   │   ├── Home.js
│   │   ├── Product.js
│   ├── App.js
│   └── index.js
└── package.json
```

## Améliorations futures

- **Système de paiement** : Intégrer un système de paiement sécurisé.
- **Page de profil utilisateur** : Pour que les utilisateurs puissent voir et gérer leurs commandes.
- **Filtres et catégories** : Ajouter des filtres de produits pour faciliter la recherche.
