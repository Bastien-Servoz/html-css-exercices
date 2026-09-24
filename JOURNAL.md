# Journal de bord

## Jour 1

- Date : 21/09/2026
- Ce que j'ai fait : création du dépôt, README, GitHub Pages, exercice-01 en ligne
- Ce qui m'a bloqué : Mauvaise configuration de la clé SSH, j'ai du la supprimer et en refaire une pour faire en sorte que tout fonctionne correctement. Ce que j'ai appris : vérifier avec ssh -T git@github.com que la clé fonctionne avant de cloner ».
- Objectif de la prochaine session : lancer le premier cours de From Scratch

## Jour 2

- Date : 22/09/2026
- Mise en place de la structure `td-html/` pour ranger les TD du cours HTML, un sous-dossier par TD (`td-01/`, `td-02/`, `td-03/`).
- TD 1 : tableau HTML complexe avec fusions de cellules (colspan/rowspan).
- Petite galère de manipulation : le dossier `td-html/td-01/` avait été créé par erreur à l'intérieur de `exercice-01/` au lieu de la racine du dépôt. Corrigé en déplaçant le dossier et en committant le changement.
- Mise à jour du sommaire dans le README avec le lien vers le TD 1.

— TD 2 : structure d'une maquette de site

- Créé `td-html/td-02/index.html`
- Travail sur l'architecture HTML d'une page : organisation en blocs `<div>` avec des classes,
  pensés pour faciliter le stylage CSS à venir
- Vérifié localement (file:///), affichage conforme

— TD 3 : intégration d'une maquette professionnelle

- Créé `td-html/td-03/index.html`
- Intégration d'une maquette plus poussée que le TD 2 : plus de contenu, d'images et de liens
- Vérifié localement (file:///), affichage conforme
- Ajout du dossier `td-html/td-correction/` pour y déposer les corrections du formateur
- Ajout de la correction du TD 3 dans `td-html/td-correction/`

## Jour 3

- Date : 23/09/2026
  Cours CSS (partie 1/2)

- Début du nouveau point de cours, dispensé en 2 parties, dédié au CSS
- Terminé la première partie du cours
- Installation et configuration des extensions/plugins indispensables pour la suite :
  - Extensions VS Code
  - Extensions Chrome

  ### Notions CSS vues aujourd'hui

- **Polices** : import de police externe via `@import url(...)` (Google Fonts) et déclaration de police locale avec `@font-face`
- **Texte** : `text-transform`, `letter-spacing`, `text-align`, tailles en `rem`, `text-shadow`, `font-family`
- **Boîtes** : centrage avec `margin: 0 auto`, bordures (`border`, `border-radius`), ombre de boîte (`box-shadow`), fond en `rgba`
- **Flexbox** : répartition équitable des éléments (`justify-content: space-around`), centrage vertical/horizontal (`justify-content` + `align-items`)
- **Grid** : mise en page en colonnes (`grid-template-columns`), et grille nommée avec `grid-template-areas` (ex : formulaire avec zones `i1`, `i2`, `ta`, `vi`, `bt`)
- **Positionnement** : `position: relative` sur le parent pour contenir un enfant en `position: absolute`, usage de `top`, `right`, `left`, `transform: translateX(-50%)` pour centrer un élément positionné
- **Interactivité** : `cursor: pointer`, `transition`, effet `:hover`
- **Responsive** : media queries (`@media screen and (max-width: ...)`) pour adapter la mise en page (grid → block, flex-direction en colonne) selon la largeur d'écran

- Prochaine étape : partie 2 du cours CSS
