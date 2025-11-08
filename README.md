# Panorama des boutiques de montagne

Ce dépôt contient une page d'accueil statique ("single page") qui met en avant une sélection de boutiques spécialisées dans les sports de montagne. L'interface se présente sous la forme d'une mosaïque de tuiles : chacune affiche l'aperçu du site marchand obtenu via **thum.io** et redirige, dans un nouvel onglet, vers la boutique correspondante.

## Fonctionnalités principales
- **Grille responsive** : les tuiles s'adaptent automatiquement à la largeur de l'écran, de l'ordinateur de bureau au smartphone.
- **Mode clair/sombre automatique** : la palette suit la préférence du système grâce à `prefers-color-scheme`.
- **Mises en avant visuelles** : chaque carte combine une capture du site marchand et le nom de la boutique pour faciliter l'identification rapide.
- **Interactions soignées** : une légère animation au survol met en évidence la carte sélectionnée.

## Ajouter ou modifier une boutique
1. Ouvrez `index.html`.
2. Dupliquez l'un des blocs `<a class="card">…</a>` situés dans la `<div class="grid">`.
3. Remplacez l'URL de la boutique dans l'attribut `href`.
4. Ajustez l'URL de la capture `img` (format `https://image.thum.io/get/width/600/crop/600/URL_DU_SITE`).
5. Modifiez le texte contenu dans `<span>` pour refléter le nom affiché.

## Déploiement sur GitHub Pages
1. Poussez la branche contenant `index.html` sur GitHub.
2. Activez GitHub Pages depuis les paramètres du dépôt en sélectionnant la branche à publier.
3. Le site sera accessible via `https://<votre-utilisateur>.github.io/<nom-du-depot>/`.

## Développement local
Aucune dépendance n'est requise. Il suffit d'ouvrir `index.html` dans votre navigateur pour prévisualiser la page.

## Licence
Ce projet est fourni "tel quel". Vous pouvez l'adapter librement pour votre propre annuaire de boutiques de montagne.
