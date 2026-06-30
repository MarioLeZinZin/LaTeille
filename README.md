# 🍾 La Bouteille

Jeu de soirée mobile : une bouteille tourne au centre avec les noms des joueurs autour. Le joueur désigné reçoit **3 cartes** au choix, chacune combinant un **type** et un **thème**.

## Jouer

Ouvre simplement `index.html` dans un navigateur (mobile ou desktop). Aucune installation.

Pour le développement avec live preview :

```bash
python3 -m http.server 4599
# puis ouvrir http://localhost:4599
```

## Contenu

- **Thèmes** : 😜 Fun · 🔥 Hot (3 niveaux : 💋 Soft / 🔥 Moyen / 🌶️ Hard) · 🍻 Alcool
- **Types de cartes** :
  - 🎲 Action ou Vérité
  - ⏱️ Défi chrono (avec compte à rebours)
  - 🎰 Roulette russe (carte sûre… ou piégée)
  - 🗳️ Le verdict (désignation de groupe, unanimité = cul sec)
  - 🙅 Je n'ai jamais
  - 🔄 Chacun son tour (tour de table)

Le contenu lisible (toutes les cartes) est généré dans [`CONTENT.md`](CONTENT.md).

## Structure

| Fichier | Rôle |
|---|---|
| `index.html` | Tout le jeu (UI + logique + contenu dans l'objet `CONTENT`) |
| `assets/bottle.png` | Image de la bouteille |
| `CONTENT.md` | Vue lisible de toutes les cartes (généré) |

> ⚠️ Jeu réservé à un public majeur (thèmes Hot 🔞 et Alcool).
