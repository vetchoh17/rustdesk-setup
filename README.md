# RustDesk Configuration (Optimized for Windows 10)

Ce dépôt contient un fichier de configuration YAML optimisé pour l'utilisation de **RustDesk** sur **Windows 10**. Ce fichier permet d'améliorer les performances du logiciel de bureau à distance en ajustant la bande passante, le taux de compression vidéo, et les limites d'utilisation des ressources.

## Contenu
- **rustdesk-config.yml** : Fichier de configuration avec des paramètres optimisés pour les serveurs privés.

## Installation et Configuration
1. Téléchargez ou clonez ce dépôt.
2. Modifiez les champs appropriés dans le fichier `rustdesk-config.yml`, comme les informations sur le serveur (ID, relais, etc.).
3. Placez le fichier dans le répertoire de configuration de RustDesk sous Windows 10.

## Paramètres Clés
- **server** : Informations sur le serveur relais et STUN.
- **security** : Protection par mot de passe et chiffrement des connexions.
- **performance** : Optimisation de la bande passante, du taux de compression, et de la qualité vidéo.
- **logging** : Configuration des journaux avec rotation quotidienne.
- **resources** : Limites d'utilisation de la CPU et de la RAM pour éviter les surcharges.
