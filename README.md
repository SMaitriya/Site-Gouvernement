Site : https://smaitriya.github.io/Site-Gouvernement/
GIT REPO : https://github.com/SMaitriya/Site-Gouvernement


HEADER (FLEX) :

- flex avec justify-content: space-between et align-items: center pour aligner l'image et la barre de recherche.

NAV (FLEX) :

- display: flex sur nav ul.
- Liste principale en flex avec align-items: center et justify-content: center.
- Sous-liste en flex-direction: column, display: none (sans hover), et display: flex (en hover), avec z-index: 1.
- Items de la sous-liste alignés en flex-start.

Accueil (FLEX) :

- display: flex.

Section (GRID + FLEX) (Main et Aside) :

- Section display: grid, grid-template-columns: 3fr 1fr, avec gap: 10px.
- Titre "Tableau de bord" en grid-column: 1 / -1 et display: flex pour centrer dans son conteneur.
- Texte sous le h1 en grid-column: 1 / -1 pour occuper toute la largeur de la grille.
- grid-container en display: grid avec grid-template-columns: repeat(3, 1fr) pour créer trois colonnes.
- À l'intérieur du container, éléments en display: flex, avec align-items: flex-start et flex-direction: column.
- Titres pour Actualités et Astuces en flex pour centrer.


Footer (BOOTSTRAP) :

- Utilisation de Bootstrap avec des classes de type row.
- display: flex pour centrer, ul avec list-unstyled pour retirer les puces, et quelques ajustements de style dans le HTML.
- Première colonne avec <div class="col-md-1"> pour l'image, et <div class="col-md-2"> pour les autres colonnes.
- Autres styles gérés dans le fichier CSS.


@media responsive :

- Header : flex-wrap: wrap et flex-direction: row.
- Nav : flex-wrap: wrap et flex-direction: column.
- Accueil : centré avec justify-content: center.
- Section : grid-template-columns: 1fr pour une seule colonne.
- Main : grid-template-columns: 1fr pour une seule colonne.
- Section h1 : justify-content: center.
- Footer row : text-align: center.

