# Le Nain Jaune 🧙

Le jeu de cartes classique, version épique, pour le hub **ChadGangGames**.

- 100 % statique : tout le jeu est dans `index.html` (aucune compilation).
- En ligne via le SDK du hub (`/_sdk.js`) : salles de 3 à 8 joueurs, bots pour compléter, l'hôte fait foi (état complet versionné envoyé avec `keep`), reprise après rechargement, relais si l'hôte part.
- Classement du hub : `ChadGang.finPartie()` appelé par chaque joueur en fin de partie en ligne.
- Hors du hub : solo contre les bots ou à plusieurs sur le même écran (sauvegarde automatique).
- Effets : Nain jaune, grand opéra, combos, pluie de jetons, sons synthétisés (bouton pour couper).

## Mise en ligne

```bash
git init && git add . && git commit -m "Le Nain Jaune"
git branch -M main
git remote add origin https://github.com/<toi>/jeu-nain-jaune.git
git push -u origin main
```

Puis dans le hub : **Admin → Jeux → Ajouter le jeu**, colle le lien du dépôt.
