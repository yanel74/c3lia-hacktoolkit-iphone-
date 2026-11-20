# C3LIA HACKTOOLKIT

Application web progressive (PWA) mobile, thème violet/noir Liquid Glass.

## Installation sur iPhone (sans PC)

1. Publie le contenu de ce dossier dans un dépôt GitHub public.
2. Dans le dépôt, ouvre **Settings → Pages**.
3. Dans **Build and deployment**, choisis **Deploy from a branch**.
4. Sélectionne la branche `main` et le dossier `/(root)`, puis **Save**.
5. Attends la publication. L'adresse sera :

   `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`

6. Ouvre cette adresse dans **Safari** sur l'iPhone.
7. Appuie sur **Partager** → **Sur l'écran d'accueil** → **Ajouter**.
8. Lance C3LIA depuis la nouvelle icône.

## Fonctionnalités

- JSON formatter / validator
- Base64 encode / decode
- SHA-256 avec Web Crypto
- Générateur de mots de passe cryptographiquement aléatoires
- Analyse indicative d'URL hors ligne
- Notes sauvegardées localement
- Aide de démarrage pour bots Discord conformes
- PWA avec cache hors ligne

## Structure

- `index.html` : interface et vues
- `style.css` : thème responsive Liquid Glass
- `app.js` : logique des outils
- `manifest.webmanifest` : configuration PWA
- `sw.js` : cache hors ligne
- `icon.svg` : icône

## Sécurité et limites

Cette application fonctionne côté navigateur et ne nécessite aucun backend Python ni clé API. Les notes sont conservées dans le stockage local du navigateur. Ne stocke pas de secrets sensibles dans les notes.

Les outils sont conçus pour un usage légitime. Le projet ne contient pas de fonctions DDoS, de vol de tokens, d'accès à des comptes tiers, de faux abonnés ou de faux likes.

## Développement

Pour tester localement, sers ce dossier avec un serveur HTTP statique. Les PWA et Service Workers nécessitent HTTPS ou localhost. GitHub Pages fournit HTTPS automatiquement.
