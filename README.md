# parcel — PWA & Déploiement Vercel

Ce dossier contient l'application **parcel** prête à être déployée sur **Vercel** :

- `index.html` : simulation de fluide WebGL en boucle, recadrage `1080×1920` / `1920×1080`, export vidéo et télécommande repliable.
- `manifest.json` : configuration PWA (nom `parcel`, mode plein écran `standalone`, icône).
- `sw.js` : *Service Worker* pour le cache et l'usage hors ligne.
- `icon.svg` : icône vectorielle de l'application.

## Déployer sur Vercel

1. Crée un compte gratuit sur [vercel.com](https://vercel.com).
2. Envoie ce dossier via **Vercel CLI** (`npx vercel --prod` dans le dossier `parcel/`) ou via un dépôt Git connecté dans **Add New → Project**.
3. Ouvre l'URL `https://...` fournie par Vercel sur ton téléphone, puis ajoute-la à l'écran d'accueil.
