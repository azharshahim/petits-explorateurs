# Petits Explorateurs

Application éducative pour enfants de 2 à 14 ans, en **français**, **anglais** et **créole mauricien**.
On choisit l'âge de l'enfant et l'appli propose les jeux adaptés à son niveau.

## Contenu

- **Jeux éducatifs** : couleurs, animaux, comptage, formes, additions, tables de multiplication, orthographe, lire l'heure, fractions, conjugaison, équations, sciences, histoire-géo, langues, jeux de mémoire.
- **Arcade** : esquive au doigt (Attrape-friandises), plateforme (Saute-aventure), course de kart en 3D (Grand prix), blocs (Blocs), tir (Mission étoiles). On ramasse des friandises pour passer au niveau suivant.
- Mode jour / nuit, son et musique, étoiles gagnées enregistrées sur l'appareil.

## Utilisation

Un seul fichier, `index.html`, sans dépendance : il suffit de l'ouvrir dans un navigateur.

Pour l'installer sur un téléphone comme une vraie appli (Android, iPhone, ordinateur), il faut le publier en ligne en HTTPS, par exemple avec GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / root), puis ouvrir l'adresse sur le téléphone et choisir « Ajouter à l'écran d'accueil ».
Après la première visite, l'appli fonctionne sans connexion grâce à `sw.js`.

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | L'application complète |
| `manifest.webmanifest` | Nom, couleurs et icônes pour l'installation |
| `sw.js` | Mode hors ligne |
| `icons/` | Icônes de l'appli |

## Personnages et droits

Les jeux d'arcade reprennent des mécaniques classiques (plateforme, tir, course, blocs) avec des personnages et des noms originaux.
