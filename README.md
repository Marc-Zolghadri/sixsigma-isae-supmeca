# SixSigma in ISAE-Supmeca — by MarcZolghadri

Site statique adapté à GitHub Pages. Contient le site Six Sigma initial et un espace `jmp/` avec les procédures issues de `Lean Six Sigma avec JMP 002.pptx`.

## Publication GitHub Pages
1. Décompresser l’archive.
2. Ouvrir le dépôt `Marc-Zolghadri/sixsigma-isae-supmeca`.
3. Téléverser **tout le contenu** de ce dossier, en respectant l’arborescence, à la racine du dépôt. Les fichiers HTML doivent être à la racine ; les feuilles CSS/JS dans `assets/`, les procédures dans `jmp/`.
4. Sur GitHub, `Settings → Pages → Deploy from a branch → main → /(root)` puis `Save`.
5. Pour éviter les difficultés de glisser-déposer de dossiers depuis l’interface web, il est conseillé d’utiliser GitHub Desktop pour synchroniser directement le dossier complet (ou Git dans un terminal).

## Maintenance
- Chaque fiche JMP est une page HTML autonome dans `jmp/`.
- Les fichiers partagés `assets/jmp.css` et `assets/jmp.js` assurent présentation et recherche.
- Modifications du contenu possibles sans dépendances ni compilation.
- Les menus / interfaces doivent être confirmés pour la version JMP utilisée.

## Remarques scientifiques
Le PowerPoint comporte des passages imprécis (p-value et normalité, formulation de la significativité, effets causaux, test de Kruskal-Wallis, confusion possible sur le sens de certains tests). Les fiches avertissent de ces limites et ne valident pas aveuglément ces assertions.
