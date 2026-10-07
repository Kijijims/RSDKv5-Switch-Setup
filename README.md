Le rôle du package : Le package fourni sur ton GitHub contient le moteur exécutable du jeu (RSDKv5.nro) et le fichier de configuration (Settings.ini). Il prépare l'emplacement sur la carte SD dans /switch/RSDKv5/.

Ce que fait le joueur : Une fois le package téléchargé via l'HB App Store, le joueur doit récupérer le fichier Data.rsdk depuis sa propre copie légale du jeu (sur PC/Steam) et le placer dans le dossier sdcard:/switch/RSDKv5/.

Le lancement : Dès que Data.rsdk est présent, le moteur charge les graphismes, musiques et niveaux originaux pour lancer le jeu directement depuis le Homebrew Menu.
### 🧩 Comment ajouter des Mods :
1. Créez un dossier nommé `mods` dans le répertoire du jeu : `sdcard:/switch/ DOSSIER RSDKv5/mods/`
2. Placez vos  mods à l'intérieur du dossier `mods`.
3. Assurez-vous que l'option des mods est activée dans le fichier `Settings.ini`(`devMenu=y` ou `upm=true` selon votre configuration)
