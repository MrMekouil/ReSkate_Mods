# Règles de travail — ReSkate Mods

Ce dépôt sert à construire des outils communs et des mods indépendants pour ReSkate.

## Organisation

- **Racine :** outils, scripts, documentation et références utiles à plusieurs mods.
- **`mods/<nom-du-mod>/` :** tous les fichiers spécifiques à un mod.
- Chaque nouveau mod doit avoir un `README.md` qui indique son but, son état réel et les instructions vérifiées.
- Ne pas déplacer ou refondre les outils existants sans besoin concret.

## Méthode

1. Examiner l'état et les fichiers existants avant toute modification.
2. Préserver les travaux en cours ; éviter les suppressions et réécritures non demandées.
3. Avancer par petites modifications vérifiables. Documenter ce qui est confirmé, hypothétique ou non testé.
4. Préférer des essais **locaux**. Ne pas ajouter ni lancer de GitHub Actions sans autorisation explicite.
5. N'introduire ni dépendance, ni framework, ni système de build sans besoin démontré.
6. Pour une intervention sur un mod, limiter les changements à ce mod sauf nécessité justifiée.

## Modding et ressources

- Ne pas présumer du format, des capacités d'import/export ou de la compatibilité d'un outil sans validation.
- Séparer les fichiers originaux des fichiers modifiés et conserver la provenance des ressources.
- Ne pas commiter de secrets, de sauvegardes personnelles ou de copies de données propriétaires du jeu non autorisées.
- Ne pas publier un mod comme fonctionnel avant un test en jeu ou une validation équivalente documentée.

## Compte rendu d'une intervention

Préciser les fichiers modifiés, les tests effectivement exécutés, les résultats et les limites connues.
