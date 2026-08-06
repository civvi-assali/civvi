 Guide Utilisateur Civvi  tailwind.config = { darkMode: "class", theme: { extend: { "colors": { "on-primary-fixed-variant": "#3c475a", "on-error": "#ffffff", "surface-variant": "#e0e3e5", "on-secondary-container": "#54647a", "on-surface": "#191c1e", "error-container": "#ffdad6", "primary": "#091426", "on-primary-container": "#8590a6", "inverse-on-surface": "#eff1f3", "surface-dim": "#d8dadc", "border-subtle": "#E2E8F0", "surface-container": "#eceef0", "on-surface-variant": "#45474c", "on-secondary-fixed": "#0b1c30", "tertiary-fixed": "#89f5e7", "primary-fixed-dim": "#bcc7de", "on-tertiary-fixed": "#00201d", "secondary-fixed-dim": "#b7c8e1", "on-primary": "#ffffff", "secondary-container": "#d0e1fb", "on-secondary-fixed-variant": "#38485d", "tertiary": "#001815", "surface": "#f7f9fb", "on-tertiary": "#ffffff", "tertiary-fixed-dim": "#6bd8cb", "primary-fixed": "#d8e3fb", "secondary": "#505f76", "outline": "#75777d", "primary-container": "#1e293b", "accent-yellow": "#FDE047", "secondary-fixed": "#d3e4fe", "on-secondary": "#ffffff", "on-background": "#191c1e", "surface-container-highest": "#e0e3e5", "on-primary-fixed": "#111c2d", "on-error-container": "#93000a", "outline-variant": "#c5c6cd", "on-tertiary-container": "#28a094", "surface-bright": "#f7f9fb", "blueprint-line": "#334155", "surface-container-lowest": "#ffffff", "inverse-surface": "#2d3133", "inverse-primary": "#bcc7de", "surface-tint": "#545f73", "tertiary-container": "#002f2a", "on-tertiary-fixed-variant": "#005049", "background": "#f7f9fb", "surface-container-high": "#e6e8ea", "surface-container-low": "#f2f4f6", "error": "#ba1a1a" }, "borderRadius": { "DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem" }, "fontFamily": { "headline-lg": \["Inter", "sans-serif"\], "label-caps": \["Inter", "sans-serif"\], "body-lg": \["Inter", "sans-serif"\], "caption": \["Inter", "sans-serif"\], "display-lg": \["Inter", "sans-serif"\], "headline-md": \["Inter", "sans-serif"\], "headline-lg-mobile": \["Inter", "sans-serif"\], "body-md": \["Inter", "sans-serif"\], "sans": \["Inter", "sans-serif"\] } }, } } @page { size: A4 portrait; margin: 15mm; } body { color: #1e293b; background-color: #f7f9fb; margin: 0; padding: 0; line-height: 1.6; } .page { page-break-after: always; position: relative; height: 270mm; box-sizing: border-box; background: #ffffff; margin: 20px auto; max-width: 210mm; padding: 40px; box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1); border-radius: 8px; } @media print { body { background: none; } .page { margin: 0; box-shadow: none; border-radius: 0; padding: 0; height: auto; min-height: 270mm; } } .header { border-bottom: 2px solid #e2e8f0; padding-bottom: 16px; margin-bottom: 32px; display: flex; justify-content: space-between; align-items: center; } .header h1 { font-size: 24px; margin: 0; text-transform: uppercase; font-weight: 700; letter-spacing: 0.1em; color: #0f172a; } .header .model { font-size: 14px; font-weight: 600; background: #f1f5f9; color: #475569; padding: 4px 12px; border-radius: 9999px; } .title-page { text-align: center; padding-top: 40mm; display: flex; flex-direction: column; align-items: center; } .title-page h1 { font-size: 64px; margin: 0 0 16px 0; letter-spacing: 0.1em; font-weight: 900; color: #0f172a; } .title-page p { font-size: 18px; margin: 0 0 40mm 0; text-transform: uppercase; color: #64748b; font-weight: 600; letter-spacing: 0.05em; } .step-header { display: flex; align-items: center; margin-bottom: 24px; gap: 16px; } .step-number { font-size: 24px; font-weight: 700; color: #ffffff; background-color: #3b82f6; border-radius: 8px; width: 48px; height: 48px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; box-shadow: 0 2px 4px rgba(59, 130, 246, 0.3); } .step-desc { font-size: 16px; font-weight: 600; color: #334155; margin: 0; line-height: 1.3; } .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; } .step-container { background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; display: flex; flex-direction: column; height: 100%; } .center-svg { display: flex; justify-content: center; align-items: center; margin: auto 0; flex-grow: 1; } .ikea-man { stroke: #1e293b; stroke-width: 2; fill: none; stroke-linecap: round; stroke-linejoin: round; } .line-art { stroke: #1e293b; stroke-width: 1.5; fill: none; stroke-linecap: round; stroke-linejoin: round; } .shaded { fill: #f1f5f9; } .shaded-accent { fill: #dbeafe; } .text-svg { font-family: 'Inter', sans-serif; fill: #334155; } .text-svg-bold { font-family: 'Inter', sans-serif; font-weight: 700; fill: #0f172a; } .content-block { background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; padding: 24px; margin-bottom: 24px; } .content-title { font-size: 18px; font-weight: 700; color: #0f172a; margin-bottom: 12px; border-bottom: 2px solid #e2e8f0; padding-bottom: 8px; } .feature-list { list-style-type: disc; padding-left: 20px; color: #475569; margin-top: 12px; } .feature-list li { margin-bottom: 8px; }

![Civvi Logo](https://lh3.googleusercontent.com/aida-public/AB6AXuDxvp2R4BEriQxa6so9ve8ISkGilwLjkilgDAMnzRs0xxAmIbKSz7ZzmJfRXOVB8PtxNy-7S0JdZNSHgvyoX7WFnDC_ipdbUh1ygu4deWNFoQ-2FGdj67bPdXYQe_eZZ5piRE9HWRsBVv1G0QFrLKJ0BoE3mbgyDNPM7ucPWJivj13OdvD84812dBA0unqPjEPkmNpwoVgxUXJucBKKScQY0jDGGspqZC6URuYyYqyHrWBCpiDRUEfHmhncZWFwPa2HoEA)

CIVVI
=====

Guide Utilisateur Complet - v13

Découvrez une nouvelle façon de communiquer localement. Civvi crée des ponts entre le cyber-espace et la nature grâce à un réseau maillé autonome, décentralisé et bienveillant.

Design & Conception par Civvi  
Aucun outil requis

CIVVI
=====

1/4

1

Alimenter le module ESP8266
---------------------------

Civvi fonctionne sur des microcontrôleurs (ESP32/ESP8266) et utilise la technologie ESP-NOW pour créer un réseau de pair-à-pair (P2P) local.

2

Se connecter au réseau Wi-Fi
----------------------------

Wi-Fi \> civvi-XXXX Réseau 2

L'appareil crée son propre réseau Wi-Fi (Point d'Accès) auquel vous vous connectez avec votre smartphone ou ordinateur.

CIVVI
=====

2/4

3

Ouvrir le portail (Écran "0")
-----------------------------

192.168.4.1 CIVVI ACCÉDER

Ouvrez votre navigateur et allez à l'adresse 192.168.4.1. Cliquez sur le bouton pour accéder à l'interface principale.

4

Interface principale (Écran "1")
--------------------------------

1.5 Info Réseau 1.6 Mon Message 1.7 Lignes Voisins 1.9 Rédaction & 1.10 Tris

Le tableau de bord est organisé autour d'une zone centrale de défilement (cibi-textuelle) et de quatre coins pour la navigation.

CIVVI
=====

3/4

5

Navigation (Les 4 Coins)
------------------------

**Haut Gauche \[1.1\] Bleu / Rond :** Accès au **Profil** personnel.

**Haut Droite \[1.2\] Jaune / Segment :** Accès à la **Messagerie** (avec pastille de notif).

**Bas Gauche \[1.3\] Rouge / Triangle :** Accès à la **Configuration** réseau.

**Bas Droite \[1.4\] Violet / Carré :** Retour à l'**Accueil** (Chaîne humaine).

6

Détails d'une ligne (1.7)
-------------------------

👕 1.7.1 📄 1.7.2 Nom 1.7.3 Message... 1.7.4 ✔️ 1.7.5 ✉️ 1.7.7

*   **1.7.1 Profil Visuel :** Affiche l'avatar (silhouette) créé par l'utilisateur.
*   **1.7.2 Intérêts (Doc) :** Ouvre le document Markdown décrivant les centres d'intérêt.
*   **1.7.3 Favoris :** Cliquez sur le pseudo pour l'ajouter/retirer de vos favoris.
*   **1.7.4 Défilement :** Faites glisser manuellement le texte pour le lire.
*   **1.7.7 Message Postal (DTN) :** Laissez un message privé de 150 caractères.

CIVVI
=====

4/4

7

Espaces Personnels
------------------

### Écran 2 : Profil

Personnalisez la façon dont les autres vous voient.

*   **Silhouette :** Choisissez les couleurs et motifs.
*   **Centres d'intérêt :** Éditeur Markdown pour votre présentation.

### Écran 3 : Messagerie

Consultez les messages postaux (privés) reçus. Vous pouvez supprimer un message ou y répondre. La réponse utilise le système d'attente (hors ligne) si nécessaire.

### Écran 4 : Configuration

Gérez les paramètres système :

*   Modifiez le nom du réseau (SSID) et le mot de passe.
*   Configurez un message de redémarrage.
*   Basculez vers le Mode Salon.

8

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
