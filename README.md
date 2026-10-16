# Page d'accueil — mzbe2.github.io

Tableau de bord des applis SUAPS de Marine Zubaloff.

## Mise en ligne
1. Sur GitHub, créez un dépôt **public** nommé exactement **`mzbe2.github.io`** (votre nom d'utilisateur + `.github.io`).
2. Déposez-y `index.html` et `logo-dauphine-sports.png` (*Add file > Upload files*).
3. **Settings > Pages** : branche `main`, dossier `/ (root)`, *Save*.
4. Après 1 à 2 minutes, la page est en ligne sur <https://mzbe2.github.io>.

Les applis existantes (`/progmuscu/`, `/sport-sante-psl/`) continuent de fonctionner : chaque dépôt garde son adresse.

## Ajouter une appli
Dans `index.html`, tout en bas, la liste `APPLIS` contient un bloc par appli. Copiez un bloc, modifiez :
- `nom`, `description`, `points` (liste de fonctionnalités), `etiquettes` ;
- `icone` : `haltere`, `coeur`, `chrono`, `groupe` ou `carnet` ;
- `liens` : `qui` (public), `texte`, `url`, et `qr: true` pour afficher un QR code.

Puis redéposez `index.html` sur GitHub.
