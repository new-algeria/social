# Dépôt technique des visuels des réseaux sociaux de New Algeria

Ce dépôt sert uniquement à rendre des images et des vidéos accessibles à Buffer le temps de créer un post.
Il ne doit **jamais être référencé** ni lié depuis un site, un post ou un README.

## Règles
- Publication par GitHub Pages depuis `main` (accord du propriétaire pour pousser directement sur `main`).
- Fichiers dans `m/<identifiant aléatoire de 8 caractères>/` : jamais de nom de dossier parlant, jamais de page qui les liste.
- `index.html` et `404.html` restent vides avec `noindex, nofollow, noarchive, noimageindex`.
- Buffer garde l'adresse du fichier (il ne le copie pas à la création) : **laisser le dossier `m/<id>/` jusqu'à la publication du post, puis le supprimer** (le lendemain). Noter l'identifiant et la date de publication dans `m/suivi.md`.
- Aucun secret, aucune donnée personnelle, aucune image sans droits : photos libres (avec crédit) ou fournies par le propriétaire ;
  vidéos d'autres créateurs seulement avec leur accord.
- Les sources des visuels (modèles HTML, script de rendu) vivent dans `modeles/` ; les visuels rendus, eux, ne restent pas.

## Format des posts (DA du propriétaire)
- **Mettre l'Algérie en valeur à chaque post** : photo de l'Algérie en slide 1 quand c'est possible (paysage, ville, monument, fierté nationale), angle positif, chiffres qui parlent des Algériens.
- Carrousels de 5 slides 1080 × 1350, photo réaliste et accrocheuse en haut de la slide 1.
- **Les photos sont toujours choisies et fournies par le propriétaire** (il a l'œil) : ne jamais en chercher ni en choisir une soi-même. Pour un nouveau post, lui demander la photo ; en attendant, préparer les textes et le reste du carrousel.
- Titres qui finissent par « en Algérie 🇩🇿 ». Données OpenStreetMap : « estimé(e)s ».
- Jamais de chiffre inventé : tout est recalculé depuis les vraies données de data-dz, source citée.
- **Classements entre pays : jamais le Maroc devant l'Algérie** (rivalité). Un classement où le Maroc apparaît n'est publié que s'il est derrière l'Algérie ; sinon, on change d'angle (progression dans le temps, classement par wilaya, autre indicateur). Pas non plus de « 5ᵉ d'Afrique » qui sous-entend des voisins devant.
- Instagram : 5 hashtags au plus, « lien en bio ». TikTok : « lien en bio ». Facebook : lien direct.
- On renvoie toujours vers data-dz, jamais vers une contribution à OpenStreetMap.
- Posts **programmés directement** dans Buffer (Instagram, Facebook), pas de brouillon : le propriétaire signale s'il ne valide pas un post.
- **TikTok : toujours en mode rappel** (`schedulingType: notification`) : le propriétaire publie lui-même depuis l'appli pour ajouter un son tendance. Instagram et Facebook restent en publication automatique.
