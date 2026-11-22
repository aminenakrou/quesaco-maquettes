# 🌿 Quésaco – Maquettes interactives

Maquettes interactives d'une application mobile d'identification de la faune et de la flore, pensée pour des collégiens.

**Démo en ligne :** [aminenakrou.github.io/quesaco-maquettes](https://aminenakrou.github.io/quesaco-maquettes/)

## Le principe

Un collégien prend en photo un insecte, une plante ou un arbre. L'application propose une identification, et un expert peut la confirmer en échangeant avec l'élève. Les publications passent par une modération, et un administrateur gère les comptes et les sauvegardes.

## Les quatre rôles

| Rôle | Ce que montre la maquette |
|---|---|
| 🧑‍🎓 Collégien | Scanner un élément (photo + GPS), voir le résultat de l'identification, discuter avec un expert |
| 🛡️ Modérateur | Traiter les contenus signalés, contacter l'élève, transférer une publication à un expert |
| 🔬 Expert | Examiner une observation peu concluante, poser des questions, corriger et valider l'identification |
| ⚙️ Administrateur | Rechercher et supprimer des comptes, gérer les sauvegardes |

Chaque parcours est cliquable : les boutons mènent aux écrans suivants, comme dans l'application réelle.

## Technologies

- React 18 (chargé depuis un CDN) et Babel Standalone
- HTML / CSS, un seul fichier `index.html`
- Publication avec GitHub Pages

## Lancer en local

Ouvrir `index.html` dans un navigateur, ou lancer un petit serveur :

```bash
python -m http.server 8000
```

puis aller sur `http://localhost:8000`.

## Structure du dépôt

```
.
├── .github/workflows/static.yml   # Publication sur GitHub Pages
├── index.html                     # Maquettes interactives (React)
└── README.md
```

## Contexte

Projet de conception réalisé en équipe (équipe ISiatech) à Polytech Lille.
