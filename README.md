# Death-Counter-Twitch
Death counter for OBS/Streamlabs

---------------------------------------------------------------------------------------------------------------------------------

# FR # 

1. Introduction

- Ce guide explique comment intégrer un fichier HTML personnalisé dans Streamlabs OBS et OBS Studio pour afficher des overlays, widgets ou autres éléments interactifs.
  

2. Pré-requis

- Streamlabs OBS ou OBS Studio installé

- Un fichier HTML fonctionnel

- Une connexion internet si le fichier dépend de ressources en ligne
  

3. Ajouter le fichier HTML dans OBS/Streamlabs

- Ouvrir OBS/Streamlabs OBS

- Ajouter une source "Navigateur" :

  - Cliquez sur le bouton "+" dans la section "Sources"

  - Sélectionnez "Navigateur" et nommez la source

- Configurer la source :

  - Dans l’URL, entrez le chemin du fichier HTML (exemple : file:///C:/chemin/vers/fichier.html)

  - Définissez la résolution (ex : 1920x1080)

  - Activez "Interagir" si besoin d’interactivité

- Appliquer et positionner l'élément
  

4. Problèmes fréquents et solutions

- Fichier non affiché : Vérifiez que le chemin est correct

- Problèmes de style CSS/JS : Activez "Actualiser le cache de la page" dans OBS


-----------------------------------------------------------------------------------------------------------------------------

English Version

1. Introduction

- This guide explains how to integrate a custom HTML file into Streamlabs OBS and OBS Studio to display overlays, widgets, or other interactive elements.
  

2. Requirements

- Streamlabs OBS or OBS Studio installed

- A functional HTML file

- Internet connection if the file relies on online resources
  

3. Adding the HTML file to OBS/Streamlabs

- Open OBS/Streamlabs OBS

- Add a "Browser" source:

  - Click the "+" button in the "Sources" section

  - Select "Browser" and name the source

- Configure the source:

  - In the URL field, enter the file path (example: file:///C:/path/to/file.html)

  - Set the resolution (e.g., 1920x1080)

  - Enable "Interact" if interaction is needed

- Apply and position the element


4. Common Issues and Solutions

- File not displaying: Check if the path is correct

- CSS/JS issues: Enable "Refresh browser when scene becomes active" in OBS

