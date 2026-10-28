# TREIIZE CITY — Saison 1

La ville du gaming ivoirien : on y rencontre, on y apprend, on y joue.

## Ouvrir le site

Double-clique sur `index.html` : il s'ouvre dans ton navigateur.

Pour le voir comme sur un téléphone dans Chrome : appuie sur **F12**, puis sur l'icône de téléphone en haut à gauche du panneau.

## Le parcours

Accueil → création du perso (`profil.html`) → **Le Hub** (`hub.html`) → Love Zone (`match.html`) → Messages (`chat.html`).

## Les fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | Accueil : logo TREIIZE avec le double I vert, bouton START |
| `profil.html` | Création du perso : pseudo, jeux, plateforme, style, 18+ |
| `hub.html` | **Le Hub** : ton personnage, la carte de la ville, les quêtes, les badges, l'actu |
| `match.html` | **Love Zone** : cartes des joueurs, GG, écran « C'est un match » |
| `chat.html` | Messages avec défi de jeu, signalement / blocage |
| `boutique.html` | **Le Marché** (prévu en Saison 3, pas encore dans le menu) |
| `css/style.css` | Couleurs et styles communs (change `--accent` pour la couleur principale) |
| `js/xp.js` | **Le personnage** : XP, rangs, quêtes de la semaine, badges |
| `js/nav.js` | La barre du bas. Pour ouvrir un nouveau quartier, ajoute sa ligne ici |
| `js/stockage.js` | Mémoire du navigateur (provisoire, remplacée par Supabase) |
| `js/joueurs.js` | Les 3 joueurs de démonstration (inventés) |

## Rangs et XP

| Rang | XP minimum |
|---|---|
| Rookie | 0 |
| Soldat | 200 |
| Pro | 600 |
| Légende | 1500 |

Quêtes de la semaine (remises à zéro chaque lundi) : compléter son profil (+100), donner 3 GG (+60), accepter un défi (+80), envoyer 5 messages (+50). Tout se règle en haut de `js/xp.js`.

## Ce qui est provisoire

- Les joueurs et l'actu de la ville sont inventés.
- Le profil et l'XP sont gardés seulement dans ton navigateur.
- Les réponses dans le chat sont simulées.

## Prochaine étape

Relier le site à **Supabase** : vraies inscriptions, vrais profils, XP enregistrée sur le compte.
