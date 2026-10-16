# Page PoDeSo

Page statique de présentation du projet Interreg PoDeSo, avec le téléchargement de la lettre d'intérêt.

## Contenu
- `index.html` : la page (aucune dépendance externe, aucun traqueur).
- `carte-podeso.webp` et `carte-podeso-600.webp` : la carte, en deux tailles.

## Publier avec GitHub Pages
1. Créer un dépôt (par exemple `podeso`) et y déposer ces trois fichiers à la racine.
2. Dans le dépôt : Settings > Pages > Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. La page est en ligne après une ou deux minutes à l'adresse `https://<compte>.github.io/podeso/`.

Pour l'ajouter au site du FabLab (dépôt Interlab), copier les trois fichiers dans un dossier `podeso/` du site.

## À adapter
- Lien de téléchargement de la lettre : cherchez `export?format=docx` dans `index.html` (deux occurrences).
- Aperçu LinkedIn : remplacez `content="carte-podeso.webp"` (balise `og:image`) par l'adresse complète de l'image une fois la page en ligne, par exemple `https://<compte>.github.io/podeso/carte-podeso.webp`.
