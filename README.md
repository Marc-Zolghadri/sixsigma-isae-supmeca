# SixSigma in ISAE-Supmeca, by MarcZolghadri

Site pédagogique statique (HTML, CSS, JavaScript) destiné à GitHub Pages.

## Tester en local

Ouvrir `index.html` dans un navigateur. Aucune installation nécessaire.

## Publier sur GitHub Pages

1. Créer un dépôt GitHub public, par exemple `sixsigma-isae-supmeca`.
2. Déposer **le contenu de ce dossier à la racine du dépôt** : `index.html`, les cinq autres pages HTML et le dossier `assets/` (pas le ZIP lui-même).
3. Dans le dépôt : **Settings → Pages → Build and deployment**.
4. Choisir **Deploy from a branch**, branche `main`, dossier `/(root)`, puis **Save**.
5. Attendre la publication ; l’adresse habituelle sera `https://VOTRE-IDENTIFIANT.github.io/sixsigma-isae-supmeca/`.
6. Pour modifier le site, remplacer les fichiers dans le même dépôt : l’URL reste la même.

## Architecture

- `index.html` : accueil
- `hypotheses.html` : H0, Ha et règles
- `choisir-test.html` : guide de choix
- `p-value.html` : p-value
- `distributions.html` : lois et calculatrices
- `niveaux-z.html` : niveaux Z
- `assets/style.css` : design commun
- `assets/site.js` : calculs et interactions

## Précautions

Site pédagogique de démonstration. Vérifier la validité des hypothèses et des calculs avant usage décisionnel. Pas de collecte de données, pas de serveur et pas de dépendance externe.
