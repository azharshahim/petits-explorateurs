# Petits Explorateurs

Application de jeux pour toute la famille, de **0 à 99 ans**, en **français**, **anglais** et **créole mauricien**.
L'enfant choisit son âge, son pseudo et son personnage, puis l'appli propose les jeux adaptés.

## Contenu

- **Jeux éducatifs** : couleurs, animaux, comptage, formes, additions, tables de multiplication, orthographe, lire l'heure, fractions, conjugaison, équations, sciences, histoire-géo, langues, jeux de mémoire.
- **Arcade** : esquive au doigt (Attrape-friandises), plateforme (Saute-aventure), course de kart en 3D (Grand prix), blocs (Blocs), tir (Mission étoiles). On ramasse des friandises pour passer au niveau suivant.
- **Créer** : gratte et découvre, coloriage, peinture à la main, bulles magiques (dès 0 an), touche et écoute les animaux.
- **En famille** : morpion, 4 en ligne, serpents et échelles, petits chevaux (2 à 4 joueurs, contre l'ordinateur ou entre humains).
- **Trophées** : une collection de trophées à débloquer.
- **Contrôle parental** : temps d'écran par jour, heure du coucher, code parent (menu engrenage > Espace parents).
- Réglages (engrenage) : jour / nuit, volume, musique, effets, voix, langues.
- Tout est enregistré sur l'appareil, rien n'est envoyé en ligne.

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
