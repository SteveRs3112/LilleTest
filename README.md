# Lille — le planning

Appli web d'une seule page : planning de la journée à Lille, avec horloge, étape en cours, liens d'itinéraire et restaurants à compléter.

## Mettre en ligne avec GitHub Pages

1. Créer un dépôt sur GitHub (par exemple `lille-planning`), public.
2. Y déposer **tous les fichiers** du dossier : `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` et `apple-touch-icon.png` (bouton **Add file → Upload files**), puis **Commit changes**.
3. Aller dans **Settings → Pages**.
4. Dans **Source**, choisir **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
5. Après une minute environ, l'adresse s'affiche en haut de la page : `https://VOTRE-PSEUDO.github.io/lille-planning/`.

Partagez ce lien avec le groupe. Sur téléphone, « Ajouter à l'écran d'accueil » pour l'ouvrir comme une appli.

## Modifier le planning

- Dans l'appli : bouton **Choisir le restaurant** ou **Modifier** sur chaque étape. Ces changements restent sur le téléphone de la personne qui les fait.
- Pour que tout le monde voie la même version : modifier la liste `DEFAULT_STEPS` dans `index.html` sur GitHub (icône crayon), puis enregistrer. Chacun peut ensuite cliquer **Revenir au planning d'origine** pour récupérer la nouvelle version.

## Installer l'appli sur le téléphone

- **Android (Chrome)** : ouvrir le lien, menu ⋮ → **Installer l'application** (ou **Ajouter à l'écran d'accueil**).
- **iPhone (Safari obligatoirement)** : ouvrir le lien, bouton Partager → **Sur l'écran d'accueil**.
- **Ordinateur (Chrome ou Edge)** : icône d'installation à droite de la barre d'adresse.

Une fois installée, l'appli s'ouvre en plein écran avec son icône, et reste consultable sans connexion.
