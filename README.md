# Outils Mission

Application web (un seul fichier `index.html`) d'outils pour les missions à l'étranger :
heures de mission et annexes Excel, check-list voyage, MAD, résumé, notes, carnet de tir,
connecteurs, couples de serrage, balistique et export.

**En ligne :** https://keops7996.github.io/gestion/

## Données

- L'application est distribuée **vide** : aucune donnée personnelle ni base de données dans ce dépôt.
- Les données saisies restent **sur l'appareil** (stockage du navigateur) et, si tu le connectes,
  dans un dossier `db` de ton choix (Chrome / Edge / Brave avec l'option *File System Access*).
- Rien n'est envoyé vers un serveur. La base Balistique (.xlsx) se charge localement.

## Installation

- **PC (Chrome / Edge / Brave)** : ouvrir le lien, puis icône « Installer » dans la barre d'adresse.
- **Android** : menu ⋮ → « Installer l'application ».
- **iPhone / iPad (Safari)** : Partager → « Sur l'écran d'accueil ».
- Hors-ligne : après la première ouverture, l'app fonctionne sans réseau.
- Variante autonome : télécharger `index.html` et l'ouvrir directement.

## Mise à jour

Remplacer `index.html` puis incrémenter `CACHE` dans `sw.js`.
