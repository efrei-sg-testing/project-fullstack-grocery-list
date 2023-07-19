# Projet Groceries

Votre objectif est de créer un site permettant de gérer une liste de courses.
Il permettra d'ajouter et de retirer des choses à acheter.

## Technologies

- Implémenter une API JSON pour récupérer les courses, en créer et en supprimer
- Afficher les courses à faire et permettre de les modifier
- Stockage dans un fichier JSON ou dans une DB Relationelle (par ex. sqlite pour faire simple)

Déjà installés :
**Frontend dans /frontend**

- React
- Jest, (Cypress)

- Installer les dépendances `npm install`
- Lancer le projet `npm start`
- Lancer les tests `npm test`
- Ouvrir cypress `npx cypress open`

**Backend dans /backend**

- Jest `npm test`
  - Vous pouvez écrire les tests unitaires, d'intégration et end-to-end avec jest. Pour les tests end-to-end, utilisez `fetch()` avec Jest
- Express `npm start`
- ESlint, Prettier
- Babel, Babel-node, pour utiliser une syntaxe moderne sans soucis. `npx babel-node fichier.js` pour exécuter un fichier particulier avec babel.

## Fonctionnalités de base

- Stocker et afficher une liste de courses
- Ajouter un élément
- Enlever un élément

## Fonctionnalités supplémentaires (idées, n'hésitez pas à implémenter les votres)

- Choisir et afficher la catégorie d'un élément: Ranger les choses à acheter dans une catégorie (Legumes, Fruits, conserves...)
- Avoir un système de gestion d'utilisateur (connexion, création de compte)

## Barème et notation

- Le plus important est la qualité du code et la qualité des tests. **Préférez implémenter moins de fonctionnalités mais mieux.**

| Topic                       | Points     |
| --------------------------- | ---------- |
| Project features            | 8          |
| Unit tests                  | 4          |
| E2E et/ou Integration tests | 4          |
| Code quality : naming       | 1          |
| Code quality : general      | 3          |
| Git usage                   | +2 (Bonus) |
