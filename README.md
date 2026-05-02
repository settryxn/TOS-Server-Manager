# Site des Termes de Service - Server Manager

Ce site web statique affiche les Termes de Service (TOS) en français pour le serveur Discord "Server Manager".

## Structure du Projet

- `index.html` : Page principale contenant les TOS.
- `style.css` : Feuille de style pour un design simple et responsive.
- `404.html` : Page d'erreur 404 personnalisée.

## Comment Utiliser

1. Ouvrez le fichier `index.html` dans votre navigateur web préféré.
2. Le site s'affichera avec les TOS du serveur.

## Personnalisation

- Modifiez le contenu dans `index.html` pour ajuster les TOS selon vos besoins.
- Ajustez les styles dans `style.css` pour changer l'apparence.

## Hébergement

Le site est un site statique et doit être déployé à la racine de l'hébergement.

### Netlify

1. Créez un compte sur https://app.netlify.com/
2. Déposez le dossier `tos-site` ou sélectionnez le dépôt Git contenant `index.html` à la racine.
3. Assurez-vous que `index.html` se trouve bien à la racine du projet.
4. Ouvrez l'URL principale fournie par Netlify, par exemple `https://votre-site.netlify.app/`.

> Si vous voyez une erreur 404, c'est généralement que l'URL pointe vers un chemin inexistant. Ouvrez la racine du site plutôt qu'un sous-chemin.

### GitHub Pages

1. Créez un dépôt GitHub public pour ce projet.
2. Poussez `index.html`, `style.css`, `404.html` et `README.md` à la racine du dépôt.
3. Dans les paramètres du dépôt, activez GitHub Pages avec la branche `main` (ou `master`) et le dossier `/ (root)`.
4. Accédez à l'URL fournie, par exemple `https://votre-nom-utilisateur.github.io/nom-du-depot/`.

## Licence

Ce projet est sous licence MIT.