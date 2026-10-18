# BlenderManager

**BlenderManager** est une application Windows qui centralise vos installations de Blender et votre bibliothèque de projets `.blend`.

> **État du projet : Alpha.** L'application est en cours de développement : certains comportements et formats de données peuvent encore évoluer.

## Téléchargement

Téléchargez l'archive correspondant à la version voulue depuis une page de version, extrayez-la dans le dossier de votre choix, puis lancez `BlenderManager.exe`.

| Version | Téléchargement |
| --- | --- |
| Alpha 1.5 (recommandée) | [Voir la version](https://github.com/FofeoLVR/BlenderManager-Releases/releases/tag/v0.1.5-alpha) |
| Alpha 1.4 | [Voir la version](https://github.com/FofeoLVR/BlenderManager-Releases/releases/tag/v0.1.4-alpha) |
| Alpha 1.3 | [Voir la version](https://github.com/FofeoLVR/BlenderManager-Releases/releases/tag/v0.1.3-alpha) |
| Alpha 1.2 | [Voir la version](https://github.com/FofeoLVR/BlenderManager-Releases/releases/tag/v0.1.2-alpha) |
| Alpha 1.1 | [Voir la version](https://github.com/FofeoLVR/BlenderManager-Releases/releases/tag/v0.1.1-alpha) |
| Alpha 1.0 | [Voir la version](https://github.com/FofeoLVR/BlenderManager-Releases/releases/tag/v0.1.0-alpha) |

Toutes les préversions restent disponibles dans la page [Releases](https://github.com/FofeoLVR/BlenderManager-Releases/releases).

## Prérequis

- Windows 10 ou Windows 11 en 64 bits.
- Le **.NET Desktop Runtime 10 en 64 bits** est nécessaire pour les builds Alpha actuels.
- Blender n'est pas inclus dans l'application : BlenderManager peut détecter une installation existante ou télécharger des versions officielles.
- Une connexion Internet est nécessaire pour rechercher et télécharger des versions de Blender en ligne.

## Fonctionnalités

### Gérer plusieurs installations de Blender

- Ajouter manuellement une installation en choisissant son exécutable `blender.exe`.
- Détecter automatiquement des installations locales, y compris dans les dossiers système usuels et les dossiers d'analyse ajoutés dans les paramètres.
- Consulter les installations enregistrées depuis une bibliothèque claire et les ouvrir directement dans l'Explorateur.
- Consulter les versions Windows x64 publiées par Blender.org, puis les télécharger et les extraire depuis l'application.
- Installer les versions téléchargées dans un dossier d'installation géré, configurable dans les paramètres.
- Repérer lorsqu'une mise à jour est disponible pour une version gérée.
- Désinstaller une version installée par BlenderManager ou retirer une installation externe de la bibliothèque sans supprimer ses fichiers.
- Suivre la progression des téléchargements et extractions.

### Organiser sa bibliothèque de projets

- Afficher les projets Blender enregistrés sous forme de cartes.
- Ouvrir un projet avec la version de Blender associée.
- Révéler le fichier d'un projet dans l'Explorateur Windows.
- Ajouter un fichier `.blend` existant à la bibliothèque.
- Choisir ou corriger l'installation de Blender associée à un projet.
- Réparer le chemin d'un projet qui a été déplacé.
- Trier la bibliothèque par date de création, nom ou dernière ouverture.
- Retirer un projet de la bibliothèque sans supprimer le fichier `.blend` du disque.

### Créer et importer des projets

- Créer un nouveau projet en choisissant son nom, son emplacement et la version de Blender à utiliser.
- Créer un simple fichier `.blend` ou une arborescence de projet complète.
- Démarrer avec les préréglages **Projet vierge** ou **Personnage**.
- Ouvrir automatiquement le projet après sa création si l'option est activée.
- Importer un projet existant et l'ouvrir immédiatement si désiré.

### Miniatures et aperçu

- Choisir une miniature personnalisée aux formats PNG, JPG, JPEG ou BMP.
- Générer une miniature avec Blender depuis le projet, lorsqu'une caméra active est présente dans la scène.
- Conserver les miniatures de la bibliothèque séparément des fichiers de projet.

### Paramètres et interface

- Interface moderne avec cartes, boutons personnalisés et thèmes **Sombre**, **Clair** et **Minuit**.
- Interface disponible en français et en anglais.
- Définir la page de démarrage, l'ouverture maximisée et le dossier par défaut des nouveaux projets.
- Choisir une installation Blender préférée et un préréglage de projet par défaut.
- Activer ou désactiver la détection des installations et la recherche de versions en ligne au démarrage.
- Configurer des confirmations avant de retirer des projets ou des installations Blender.

## Démarrage rapide

1. Installez le .NET Desktop Runtime 10 x64 si nécessaire.
2. Extrayez l'archive de BlenderManager et lancez `BlenderManager.exe`.
3. Dans les paramètres, choisissez un dossier d'installation géré si vous souhaitez télécharger Blender depuis l'application.
4. Ajoutez une installation existante ou lancez une détection locale.
5. Créez un projet ou ajoutez un fichier `.blend` existant à votre bibliothèque.

## Données locales

Les réglages, la liste des installations, la bibliothèque de projets et les miniatures sont enregistrés localement dans :

`%LOCALAPPDATA%\Vector III Studio\BlenderManager`

Sauvegardez ce dossier avant une réinstallation de Windows ou avant de modifier manuellement ses fichiers.

## Limites de l'Alpha

- Des bugs ou des comportements incomplets peuvent subsister.
- Les fonctions de téléchargement dépendent des archives publiées par Blender.org.
- Conservez une copie de vos projets importants : BlenderManager organise et lance vos projets, mais ne remplace pas une stratégie de sauvegarde.
- Les fichiers de projet et les installations Blender restent votre responsabilité ; vérifiez toujours le dossier sélectionné avant une désinstallation.

## Code source et confidentialité

Ce dépôt est un dépôt de **distribution binaire uniquement** : il contient les applications compilées et les archives de versions.

BlenderManager est un projet propriétaire ; le code source, les fichiers `.slnx` et les fichiers de développement ne sont pas publiés ici.

## Signaler un problème

Pour signaler un bug, suggérer une fonctionnalité ou demander de l'aide, ouvrez une [issue](https://github.com/FofeoLVR/BlenderManager-Releases/issues) en indiquant la version de BlenderManager, votre version de Windows et les étapes permettant de reproduire le problème.
