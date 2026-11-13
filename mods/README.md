# Mods

Ce dossier accueillera **un sous-dossier par mod**.

Exemple de future organisation (aucun de ces mods d'exemple n'est créé) :

```text
mods/
├── README.md
├── premier-mod/
│   └── README.md
└── autre-mod/
    └── README.md
```

## Conventions

- Choisir un nom de dossier explicite et stable, de préférence en minuscules avec des tirets.
- Garder les sources, ressources et fichiers propres au mod dans son dossier.
- Placer les outils réutilisables par plusieurs mods à la racine du dépôt.
- Ajouter un `README.md` par mod avec :
  - **Objectif** et description ;
  - **État** (idée, prototype, en test, fonctionnel...) ;
  - **Prérequis** et dépendances si connus ;
  - **Installation/utilisation**, uniquement si vérifiées ;
  - **Tests réalisés** et limites connues.
- Ajouter ensuite des sous-dossiers (`src/`, `assets/`, etc.) seulement s'ils sont nécessaires.

**État actuel :** aucun mod créé dans ce répertoire.
