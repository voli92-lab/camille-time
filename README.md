# Compteur de notre histoire ♥

Un compteur en temps réel (ans, mois, jours, heures, minutes, secondes) depuis le 4 janvier 2025 à 04:02:00.

## Utilisation

Ouvre simplement `index.html` dans ton navigateur. Aucune installation nécessaire.

## Mettre en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub et envoie-y `index.html` et `README.md`.
2. Va dans **Settings → Pages**.
3. Dans **Source**, choisis la branche `main` et le dossier `/ (root)`, puis enregistre.
4. Après environ une minute, ton site est disponible à l'adresse `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## Changer la date

Dans `index.html`, modifie cette ligne (le mois commence à 0 : janvier = 0) :

```js
var START = new Date(2025, 0, 4, 4, 2, 0);
```
