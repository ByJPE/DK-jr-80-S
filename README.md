# 🦍 Donkey Kong Jr. Rétro

Jeu d'arcade en HTML/JavaScript inspiré de *Donkey Kong Jr.* — un seul fichier, aucune dépendance, jouable sur **ordinateur et smartphone**.

▶️ **Jouer en ligne** : `https://<ton-pseudo>.github.io/donkey-kong-jr-retro/` (après activation de GitHub Pages, voir plus bas)

## Fonctionnalités
- Pixel art dans le style de l'arcade : poutres, lianes, fruits, cage de DK, clé, îlots-arbres et eau
- Effet CRT : scanlines, vignetage, léger scintillement
- **10 niveaux** de difficulté croissante : lianes de plus en plus courtes (il faut sauter de l'une à l'autre), plus d'ennemis et plus rapides, moins d'îlots et de fruits
- Snapjaws bleus et rouges, oiseaux, fruits qui tombent sur les ennemis
- Bonus de temps, 3 vies, meilleur score sauvegardé dans le navigateur
- Contrôles clavier et tactiles (croix directionnelle + bouton SAUT, affichés seulement sur appareils tactiles)

## Commandes
| Action | Clavier | Tactile |
|---|---|---|
| Se déplacer / grimper | Flèches ou WASD | Croix directionnelle |
| Sauter | Espace ou Z | Bouton SAUT |
| Démarrer / rejouer | Entrée ou Espace | Toucher l'écran |

**But** : atteindre la clé en haut pour libérer Papa. Tomber à l'eau ou toucher un ennemi fait perdre une vie. Toucher un fruit le fait tomber sur la liane et élimine les snapjaws en dessous.

## Lancer en local
Ouvrir `index.html` dans un navigateur. Aucun serveur ni installation nécessaire.

## Publier avec GitHub Pages
1. Créer un dépôt `donkey-kong-jr-retro` sur GitHub, puis, dans ce dossier :
   ```bash
   git init
   git add .
   git commit -m "Donkey Kong Jr. rétro : première version"
   git branch -M main
   git remote add origin https://github.com/<ton-pseudo>/donkey-kong-jr-retro.git
   git push -u origin main
   ```
2. Sur GitHub : **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`**.
3. Le jeu est disponible quelques minutes plus tard à l'adresse indiquée en haut.

## Mentions
Projet de fan, non officiel, sans lien avec Nintendo. *Donkey Kong* et *Donkey Kong Jr.* sont des marques de Nintendo. Aucun asset officiel n'est utilisé : tous les sprites sont redessinés en pixel art dans le code. Le code est publié sous licence MIT (voir `LICENSE`).
