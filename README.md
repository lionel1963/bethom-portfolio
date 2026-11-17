# BeThom — Portfolio responsive

Portfolio réalisé en HTML5, CSS3 et JavaScript natif. Le site est statique : aucune dépendance ni compilation n'est nécessaire.

## Installation et lancement

1. Récupérez le dépôt (clonage Git ou téléchargement de l'archive), puis ouvrez son dossier dans VS Code.
2. Lancez le site de l'une des façons suivantes :
   - ouvrez `index.html` directement dans un navigateur ;
   - ou, dans VS Code, lancez `index.html` avec l'extension Live Server pour bénéficier du rechargement automatique.

La connexion à Internet est nécessaire pour charger la police Heebo depuis Google Fonts. Sans connexion, les polices de secours du système seront utilisées.

## Polices

- **Heebo** (graisses 400, 500, 600, 700 et 800) est la police principale du site. Elle est chargée depuis Google Fonts dans `index.html`.
- **Arial** est la police sans empattement de secours.
- **Georgia** est utilisée pour certains textes de la zone de contact, avec une police serif de secours.

## Structure du projet

- `index.html` : structure sémantique et contenu du portfolio.
- `style.css` : mise en page responsive, typographie et styles.
- `script.js` : menu mobile, année du pied de page et préparation d'un e-mail.
- `assets/` : images et autres ressources du site.

## Responsive

- Mobile : 600 px et moins (menu hamburger, colonnes empilées).
- Tablette : 601 à 850 px (grilles réorganisées).
- Desktop : plus de 850 px (colonnes et grilles).

## À personnaliser

- Le fichier `assets/cv-thomas.pdf` est déjà présent ; remplacez-le par une version à jour si nécessaire, en conservant ce nom et cet emplacement.
- Vérifier les coordonnées de contact et remplacer les liens de réseaux sociaux de démonstration.
- Remplacer les visuels extraits de la maquette par les fichiers originaux, si disponibles.

## Formulaire de contact

Le formulaire vérifie les champs puis ouvre le logiciel de messagerie avec un brouillon (`mailto:`). Il ne transmet pas directement les données à un serveur.

## Validation

Le HTML et le CSS ont été validés avec le [W3C Markup Validation Service](https://validator.w3.org/) et le [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).
