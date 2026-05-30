# Fonctionnalités demandées

- Typewriter pour l'en-tête
  - Description : effet « machine à écrire » pour le titre principal de la page d'accueil.
  - Où l'ajouter : `src/index.html` (en-tête) + nouveau fichier `src/js/typewriter.js` ou script inline.
  - Notes : prévoir options de vitesse, pause entre phrases et boucle optionnelle. Utiliser `setTimeout`/`requestAnimationFrame` ou une petite classe JS réutilisable.

- Galerie filtrable
  - Description : grille de projets filtrable par catégorie avec option lightbox pour voir un projet en grand.
  - Où l'ajouter : `src/projects/index.html` et `src/projects/style.css` (ou `projects/style.css`).
  - Notes : implémenter les filtres en JS (data-attributes), et une lightbox légère (modal) en vanilla JS.

- Formulaire de contact
  - Description : validation front-end, retour d'erreur utilisateur, et envoi AJAX (`fetch`) vers une API ou service (Formspree, Netlify, etc.).
  - Où l'ajouter : `src/Contact/index.html` + `src/Contact/style.css`.
  - Notes : valider email/texte, afficher messages d'erreur success/fail, sauvegarder brouillon localement (optionnel) avec `localStorage`.
