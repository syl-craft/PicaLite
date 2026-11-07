# PicaLite

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="readme/picalite-banniere-sombre.png">
  <img src="readme/picalite-banniere-clair.png" alt="PicaLite">
</picture>

PicaLite est une visionneuse et un organiseur de photos et vidéos pour Windows, inspiré de Picasa.
Vos fichiers restent dans leurs dossiers. Parcourez votre collection par dossiers ou chronologie,
préparez une sélection et imprimez plusieurs photos sur une feuille, avec cadrage et repères de coupe.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="readme/demos/01-parcourir-dark.gif">
  <img src="readme/demos/01-parcourir-light.gif" alt="Démonstration : la collection parcourue par dossiers, puis en chronologie, avec le filtre photos ou vidéos" width="960">
</picture>

**[Télécharger PicaLite pour Windows x64](https://github.com/syl-craft/PicaLite/releases/latest/download/PicaLiteApp-win-Setup.exe)**

Le programme d'installation installe le runtime .NET 10 Desktop si nécessaire. Il s'installe pour
votre compte, sans remplacer le dossier du profil. L'application recherche les mises à jour ; vous
décidez de leur téléchargement et du redémarrage. Cette recherche peut être désactivée dans les Paramètres.
Le programme n'est pas signé : Windows SmartScreen peut afficher un avertissement.

## Photos, vidéos et impression

- Navigation par dossiers et chronologie, visionneuse avec zoom et lecture vidéo.
- Sélection commune aux sources, export et rotation JPEG sans réencodage.
- Impression photo : formats personnalisés, cadrage, plusieurs photos par feuille, repères de coupe.
- Interface en français et en anglais, thèmes clair, sombre et système.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="readme/demos/02-visionneuse-dark.gif">
  <img src="readme/demos/02-visionneuse-light.gif" alt="Démonstration : une photo ouverte en grand dans la visionneuse, zoomée, puis la suivante et une vidéo lue sur place" width="960">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="readme/demos/03-selection-export-dark.gif">
  <img src="readme/demos/03-selection-export-light.gif" alt="Démonstration : des photos cochées dans deux dossiers, puis exportées en JPEG avec la progression jusqu’au compte rendu" width="960">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="readme/demos/04-impression-dark.gif">
  <img src="readme/demos/04-impression-light.gif" alt="Démonstration : quatre photos 9 × 13 sur une feuille A4, une photo recadrée et les repères de coupe ajoutés" width="960">
</picture>

Photos de démonstration issues d’[Unsplash](https://unsplash.com), sous [licence Unsplash](https://unsplash.com/license) ;
les auteurs sont cités dans [readme/demos/CREDITS.md](readme/demos/CREDITS.md).

## Modules optionnels

Les moteurs natifs lourds sont téléchargés à la demande depuis **Paramètres → Modules** :
Magick pour les formats avancés, FFmpeg pour les vignettes vidéo et libVLC pour la lecture vidéo.

Le [manifeste des modules](https://github.com/syl-craft/PicaLite/releases/download/modules/manifest.json)
est conservé dans la release permanente `modules`. Les archives, sources et licences sont disponibles
dans les releases `modules-AAAA-MM-JJ`. Ces releases ne remplacent pas la dernière version de l'application.

Les modules conservent les licences de leurs composants, distinctes de celle de PicaLite.
Consultez les textes inclus dans chaque archive et les sources publiées dans la même release :
ImageMagick/Magick.NET et leurs dépendances, FFmpeg en variante LGPL, libVLC et les greffons LGPL retenus.
Les licences et avis des dépendances restent applicables. Leur téléchargement n'accorde aucun droit
supplémentaire sur le code de PicaLite.

Ce dépôt héberge uniquement les visuels de présentation, les distributions et les modules.
Le code source de PicaLite est conservé dans un dépôt privé. Aucune photo personnelle n'est distribuée ici.
