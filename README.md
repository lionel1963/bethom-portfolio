# BeThom — Portfolio responsive

Intégration HTML5, CSS3 et JavaScript natif construite à partir des captures desktop/mobile fournies.

## Lancer
Ouvrir `index.html` dans un navigateur ou utiliser Live Server.

## Structure
- `index.html` : HTML sémantique (`header`, `nav`, `main`, `section`, `footer`).
- `style.css` : Flexbox, Grid, unités relatives et breakpoints.
- `script.js` : menu mobile, année du footer et préparation d'un e-mail.
- `assets/` : extraits d'images issus de la maquette fournie.

## Breakpoints
- Mobile : 600 px et moins (menu hamburger, colonnes empilées).
- Tablette : 601 à 850 px (grilles réorganisées).
- Desktop : plus de 850 px (colonnes et grilles).

## À personnaliser
- Ajouter le vrai fichier `assets/cv-thomas.pdf` pour activer le téléchargement du CV.
- Vérifier les coordonnées de contact et remplacer les liens de réseaux sociaux de démonstration.
- Les visuels du portfolio sont extraits de la capture de maquette : remplacer par les fichiers originaux si disponibles.

## Formulaire
Le formulaire vérifie les champs puis ouvre le logiciel de messagerie avec un brouillon (`mailto:`). Il ne transmet pas directement les données à un serveur.

## Validation
Tester le HTML avec https://validator.w3.org/ et le CSS avec https://jigsaw.w3.org/css-validator/ avant publication.
