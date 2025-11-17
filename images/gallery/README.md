# Dossier Galerie

Ce dossier contient les images affichées dans le carrousel de la galerie.

## Comment ajouter des images

1. Placez vos images dans ce dossier (`images/gallery/`)
2. Formats acceptés : `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp` (insensible à la casse)
3. Modifiez le fichier `gallery-config.js` à la racine du projet pour ajouter vos images

## Exemple de configuration

Dans `gallery-config.js`, ajoutez une entrée dans le tableau `images` :

```javascript
{
  "src": "images/gallery/nom_de_votre_image.jpg",
  "alt": "Description de l'image"
}
```

**Important** : 
- Les chemins doivent commencer par `images/gallery/` pour des raisons de sécurité
- Le fichier `gallery-config.js` est utilisé au lieu de JSON pour éviter les problèmes CORS avec `file://`

