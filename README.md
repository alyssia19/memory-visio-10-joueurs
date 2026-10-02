# Memory — Jouons ensemble

Memory multijoueur pensé pour une partie en visioconférence.

## Règles
- 2 joueurs = 9 paires
- chaque joueur supplémentaire ajoute 1 paire
- donc 2→9, 3→10, …, 10→17 paires
- les scores individuels sont affichés, sans classement ni comparaison
- lorsqu'une paire est ratée, les deux cartes restent visibles 3 secondes avant de se retourner
- fin de partie : message de remerciement + bouton Revanche
- photos réelles, sans emojis ni dessins

## Fonctionnement
Le jeu est une page web statique et utilise PeerJS pour relier directement les navigateurs. Pour une partie à distance, la personne qui crée la partie doit garder son onglet ouvert pendant la partie. Le bouton « Copier le lien » transmet un lien d'invitation unique aux autres participants.

## Publication
Le dépôt peut être publié avec GitHub Pages :
Settings → Pages → Deploy from a branch → main → /(root) → Save.

URL attendue :
https://alyssia19.github.io/memory-visio-10-joueurs/
