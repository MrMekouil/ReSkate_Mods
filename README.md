# ReSkate Mods

Dépôt de travail pour préparer et développer des mods pour **skate. (ReSkate)**.

L'organisation suit deux principes :

- **À la racine** : les outils, scripts, données de référence légères et documents utiles à plusieurs mods.
- **Dans `mods/`** : un dossier autonome par mod développé.

## Arborescence

```text
ReSkate_Mods/
├── README.md          # Présentation et conventions
├── AGENTS.md          # Règles de travail pour les assistants
├── ROADMAP.md         # Grandes étapes du dépôt
├── .gitignore         # Fichiers locaux à ne pas versionner
└── mods/
    ├── README.md      # Organisation des mods
    └── <nom-du-mod>/   # À créer pour chaque vrai projet
```

L'arborescence ci-dessus montre la **convention cible** : le dossier `<nom-du-mod>/` est un exemple et n'est pas créé tant qu'aucun mod n'a commencé.

## Contenu partagé

Les scripts d'analyse, d'extraction, de conversion, les catalogues et les notes techniques réutilisables pourront être ajoutés à la racine. On ne crée pas de sous-structure complexe avant d'en avoir besoin.

Éviter de versionner des copies volumineuses de fichiers du jeu, des données propriétaires redistribuables sans autorisation, des secrets ou des fichiers temporaires. Préférer les scripts reproductibles et les métadonnées utiles.

## Créer un mod

1. Créer `mods/nom-du-mod/`.
2. Ajouter un `README.md` expliquant l'objectif, l'état du mod, ses dépendances et, une fois vérifiée, sa méthode d'installation.
3. Garder dans ce dossier les sources et ressources propres au mod ; laisser les outils réutilisables à la racine.
4. Documenter ce qui a réellement été testé, sans présenter les hypothèses comme des fonctionnalités confirmées.

Voir [les conventions des mods](mods/README.md) et [la feuille de route](ROADMAP.md).

## État du dépôt

Structure et documentation initiales. Aucun mod n'est encore publié dans ce dépôt ; les outils et méthodes de création seront ajoutés et documentés au fil des essais.
