# Compteur de points

Feuille de score numérique pour jeu de plateau : 5 catégories de paysage (Arbres, Roches, Champs, Maison, Rivière) + points de cartes, avec historique des parties et classement des joueurs.

Une seule page HTML, sans dépendance ni serveur. Fonctionne hors-ligne et s'installe sur l'écran d'accueil du téléphone.

## Fonctions

- **Partie** : saisie par joueur, sous-totaux catégories / cartes, total, classement en direct (bandeau en haut, cliquable).
- **Saisie rapide** : `Entrée` passe à la case suivante ; sur la dernière carte remplie, `Entrée` ajoute une nouvelle carte.
- **Historique** : détail de chaque partie, correction d'une partie enregistrée, suppression, export / import en JSON.
- **Classement** : victoires, parties, % de victoires, moyenne, record, podiums, part des points venant des catégories ou des cartes. Tri par victoires, points cumulés ou moyenne.

Les données restent dans le navigateur (`localStorage`). Pour changer d'appareil : *Historique → Exporter*, puis *Importer* sur l'autre appareil.

## Utilisation

- En ligne : via GitHub Pages (voir l'URL du dépôt, rubrique *Pages*).
- Hors-ligne : ouvrir `index.html` directement dans un navigateur.
- Sur téléphone : ouvrir l'URL puis « Ajouter à l'écran d'accueil ».

## Publier avec GitHub Pages

*Settings → Pages → Build and deployment* : source **Deploy from a branch**, branche `main`, dossier `/ (root)`.
