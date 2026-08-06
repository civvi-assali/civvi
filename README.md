 Guide Utilisateur Civvi  

![Civvi Logo](https://lh3.googleusercontent.com/aida-public/AB6AXuDxvp2R4BEriQxa6so9ve8ISkGilwLjkilgDAMnzRs0xxAmIbKSz7ZzmJfRXOVB8PtxNy-7S0JdZNSHgvyoX7WFnDC_ipdbUh1ygu4deWNFoQ-2FGdj67bPdXYQe_eZZ5piRE9HWRsBVv1G0QFrLKJ0BoE3mbgyDNPM7ucPWJivj13OdvD84812dBA0unqPjEPkmNpwoVgxUXJucBKKScQY0jDGGspqZC6URuYyYqyHrWBCpiDRUEfHmhncZWFwPa2HoEA)

CIVVI
=====

Guide Utilisateur Complet

Découvrez une nouvelle façon de communiquer localement. Civvi crée des ponts entre voisins grâce à un réseau maillé autonome, décentralisé et bienveillant.

Design & Conception par Civvi  
Aucun outil requis

CIVVI
=====

Alimenter le module ESP32
---------------------------

Civvi fonctionne sur des microcontrôleurs (ESP32/ESP8266) et utilise la technologie ESP-NOW pour créer un réseau de pair-à-pair (P2P) local.


Se connecter au réseau Wi-Fi
----------------------------

Wi-Fi \> civvi-XXXX Réseau 2

L'appareil crée son propre réseau Wi-Fi (Point d'Accès) auquel vous vous connectez avec votre smartphone ou ordinateur.

CIVVI
=====


Ouvrir le portail (Écran "0")
-----------------------------

192.168.4.1 CIVVI ACCÉDER

Ouvrez votre navigateur et allez à l'adresse 192.168.4.1. Cliquez sur le bouton pour accéder à l'interface principale.


Interface principale (Écran "1")
--------------------------------

1.5 Info Réseau 1.6 Mon Message 1.7 Lignes Voisins 1.9 Rédaction & 1.10 Tris

Le tableau de bord est organisé autour d'une zone centrale de défilement (cibi-textuelle) et de quatre coins pour la navigation.

CIVVI
=====


Navigation (Les 4 Coins)
------------------------

**Haut Gauche \[1.1\] Bleu / Rond :** Accès au **Profil** personnel.

**Haut Droite \[1.2\] Jaune / Segment :** Accès à la **Messagerie** (avec pastille de notif).

**Bas Gauche \[1.3\] Rouge / Triangle :** Accès à la **Configuration** réseau.

**Bas Droite \[1.4\] Violet / Carré :** Retour à l'**Accueil** (Chaîne humaine).


CIVVI
=====


Espaces Personnels
------------------

### Écran 2 : Profil

*   **Centres d'intérêt :** Éditeur Markdown pour votre présentation.

### Écran 3 : Messagerie

Consultez les messages postaux (privés) reçus. Vous pouvez supprimer un message ou y répondre. La réponse utilise le système d'attente (hors ligne) si nécessaire.

### Écran 4 : Configuration

Gérez les paramètres système :

*   Modifiez le nom du réseau (SSID) et le mot de passe.
*   Configurez un message de redémarrage.
*   Basculez vers le Mode Salon.


Modes de Fonctionnement
-----------------------

📡

### Mode Relais (P2P)

Le mode par défaut. Votre module participe au réseau maillé décentralisé.

*   Vous diffusez une seule "pensée" à la fois.
*   Vous captez les pensées des voisins à portée radio.
*   Interface complète avec profils, messagerie différée.

💬

### Mode Salon

Un mode de discussion locale instantanée.

*   **L'Hébergeur :** Gère le salon et peut le fermer pour repasser en P2P.
*   **Les Visiteurs :** Se connectent au Wi-Fi "NomDuReseau-salon".
*   Interface simplifiée concentrée sur l'historique du chat en temps réel.
