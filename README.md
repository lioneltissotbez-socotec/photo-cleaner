# Soco Diag - Photo Cleaner

Application PWA pour préparer des images à intégrer dans LICIEL : import image/PDF, photo, capture écran, crop, nettoyage, mode simple/expert et export JPG LICIEL.

## Déploiement GitHub Pages

1. Créer un dépôt GitHub, par exemple `soco-diag-photo-cleaner`.
2. Déposer tous les fichiers de ce dossier à la racine du dépôt.
3. Dans GitHub : **Settings → Pages**.
4. Dans **Build and deployment**, choisir :
   - Source : **Deploy from a branch**
   - Branch : **main**
   - Folder : **/root**
5. Ouvrir l’URL GitHub Pages générée.

## Installation comme application

### Chrome
Menu **⋮ → Enregistrer et partager → Installer Soco Diag - Photo Cleaner**.

### Edge
Menu **⋯ → Applications → Installer ce site en tant qu’application**.

## Offline

L’application est mise en cache par `sw.js` après le premier chargement depuis GitHub Pages. Elle peut ensuite s’ouvrir depuis l’icône du bureau sans réseau.

Note : l’import PDF utilise PDF.js depuis CDN dans cette version. Pour un mode 100 % autonome PDF compris, ajouter les fichiers PDF.js localement et remplacer les URL CDN par des chemins locaux.
