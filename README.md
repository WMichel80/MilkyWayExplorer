# 🚀 MilkyWayExplorer

Sandbox MMORPG (Cross-Platform: Linux / Windows)

Salut ! Je travaille actuellement sur MilkyWayExplorer, un MMORPG sandbox cross-platform inspiré par World of Warcraft, Minecraft et Boundless. Le jeu utilise un moteur 3D entièrement développé en C++.
🎮 Features

Le jeu se concentre sur les mécaniques suivantes :

    🌍 Open World Procédural – Un univers immense à explorer.
    🪐 Planètes générées procéduralement – Chaque monde est unique.
    🏗 Construction Voxel – Créez et personnalisez vos structures.
    ⚔ PvP / PvE – Combattez d'autres joueurs ou des ennemis contrôlés par l'IA.
    👥 Multijoueur Massif – Interagissez avec une grande communauté.
    💰 Économie Dynamique – Un marché vivant et évolutif.
    🏰 Factions / Teams – Alliez-vous pour dominer la galaxie.
    🗝 Quêtes et Donjons – Des défis variés à relever seul ou en groupe.

📖 Lore (Mode Solo)

Vous incarnez un astronaute perdu dans l'espace qui doit survivre, explorer différentes planètes et trouver un moyen de rentrer sur Terre.

Chaque planète possède son propre environnement et ses défis :

    🏜 Désertique
    🌱 Habitable
    ☠ Hostile
    📊 Difficulté variable

🛠 Modding & Outils

Le jeu est conçu pour être entièrement moddable et accessible aux créateurs :

    API Lua (SOL2) : Pour scripter vos propres mécaniques et mods.
    Éditeur Voxel Art : Un outil est en cours de développement pour faciliter la création de contenu (assets, décors, etc.).

📦 Alpha V1.1 (Technical Test)

Cette version est une version technique destinée à valider les infrastructures du jeu. Elle ne contient pas encore le gameplay final, mais permet de tester les fondations du projet.
Avancement du projet :

################################################################################
##                       PROJET MILKYWAY - MODULE TODO LIST                   ##
################################################################################
MODULES                                     | ACHEVÉ % | INTÉGRÉ % | STATUT
--------------------------------------------|----------|-----------|------------
Launcher and UpdateManager                  |    50%   |    50%    | En cours
ConnectionManager                           |   100%   |   100%    | OK
ConfigManager                               |   100%   |   100%    | OK
DictionaryManager                           |   100%   |   100%    | OK
PluginManager (LUA/SOL2)                    |    15%   |    10%    | En cours
ChatManager                                 |   100%   |    95%    | En cours
TemplateManager                             |   100%   |   100%    | OK
StartMenu / InGameMenu                      |    40%   |    40%    | En cours
SoundMusicManager                           |   100%   |   100%    | OK
PlayerManager                               |   100%   |     0%    | En cours
PermList                                    |   100%   |     0%    | En cours
GroupManager                                |   100%   |     0%    | En cours
CommandDispatcher                           |   100%   |     0%    | En cours
GalaxyManager                               |     0%   |     0%    | ToDo
WorldManager                                |    20%   |     0%    | En cours
DrawManager                                 |    90%   |     0%    | En cours
WorldEditManager                            |     0%   |     0%    | ToDo
ClaimManager                                |     0%   |     0%    | ToDo
TeamManager                                 |   100%   |     0%    | En cours
ObjectManager and Editor                    |     0%   |     0%    | ToDo
Biomes and NoiseManager                     |     0%   |     0%    | ToDo
VegetationManager                           |     0%   |     0%    | ToDo
ItemManager                                 |     0%   |     0%    | ToDo
WeaponsManager                              |     0%   |     0%    | ToDo
ChestManager                                |     0%   |     0%    | ToDo
                        Passage en version Béta
CraftingSys                                 |     0%   |     0%    | ToDo
Enchantments / Magic / Witch                |     0%   |     0%    | ToDo
MiniMapSys and Compass                      |     0%   |     0%    | ToDo
EnemiesAIManager                            |     0%   |     0%    | ToDo
Spawner and EnemiesManager                  |     0%   |     0%    | ToDo
Warp and PortalsManager                     |     0%   |     0%    | ToDo
Day/Night / Weather / Seasons               |     0%   |     0%    | ToDo
MonumentManager                             |     0%   |     0%    | ToDo
Vehicles (Car, Train, Space)                |     0%   |     0%    | ToDo
ElectronicSystem                            |     0%   |     0%    | ToDo
DialogWindows (Score, Input)                |     0%   |     0%    | ToDo
KitsManager                                 |     0%   |     0%    | ToDo
EcoSys / Shops / Trade                      |     0%   |     0%    | ToDo
RandomRewardsSys                            |     0%   |     0%    | ToDo
DungeonManager                              |     0%   |     0%    | ToDo
JobManager                                  |     0%   |     0%    | ToDo
EventsSystem                                |     0%   |     0%    | ToDo

--------------------------------------------------------------------------------

Fichiers disponibles :

    MilkyWayExplorer (Linux)
    MilkyWayExplorer.exe (Windows)

⚠️ Comment tester le Chat ?

Le système de chat est opérationnel, mais il nécessite une manipulation spécifique pour être testé en local :

    Lancez le launcher une première fois en mode Serveur.
    Lancez le launcher une deuxième fois en mode Client.

🚧 Statut du projet

Le projet est en développement actif. Une version Alpha pour les premiers tests arrive bientôt.

🤝 Contribuer

Je recherche des personnes intéressées pour contribuer au projet. Si vous avez des compétences dans les domaines suivants, contactez-moi :

    🎵 Musique
    🔊 Sound Design
    🎨 Voxel Art
    💡 Idées de Gameplay

📜 Licence & Copyright

Ce projet est un logiciel propriétaire.

© 2024 Michel Weniger - Tous droits réservés.

Le code source du moteur et du jeu n'est pas public. En téléchargeant ce logiciel, vous obtenez une licence d'utilisation non exclusive.

Autorisations :

    ✅ Usage personnel : Vous pouvez installer et jouer au jeu pour votre usage personnel.
    ✅ Modding : Vous êtes autorisé à modifier les fichiers de configuration et à créer des mods via l'API Lua (SOL2) fournie à cet effet.

Restrictions :

    🚫 Redistribution : Il est interdit de redistribuer le launcher, les exécutables du jeu ou les assets (graphismes, sons, modèles 3D), que ce soit gratuitement ou contre paiement.
    🚫 Usage commercial : Vous ne pouvez pas utiliser ce logiciel ou ses assets à des fins commerciales.

Le but est de protéger le travail effectué tout en permettant à la communauté de créer du contenu via les outils officiels.
