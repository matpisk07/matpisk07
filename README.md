# Salut, je suis Mattia Pischedda ! 👋

### Étudiant en L1 Cursus Master Ingénierie (CMI) Électronique à Sorbonne Université 🎓

Passionné par l'électronique embarquée et l'informatique, je conçois des systèmes complets, du prototypage hardware jusqu'au développement firmware. Je suis à la recherche d'un **stage technique de 6 semaines (Juin-Juillet)** pour valider ma première année.

---

## 🛠 Compétences Techniques

**Microcontrôleurs & IoT**
* **Espressif :** ESP32-S3, ESP8266.
* **Arduino/Atmel :** Leonardo, Mega 2560.
* **RP2040 :** Raspberry Pi Pico.

**Développement & Logiciels**
* **Langages :** C++ (Arduino), Python (Algorithmique & Scripting).
* **Concepts C++ :** Machines à états finis, Gestion non-bloquante (`millis`), Structures de données (Enums, Arrays).
* **Web & Réseau :** Serveur Web embarqué (Captive Portal), API REST/JSON, Protocoles UART/SPI/I2C.
* **Outils :** Arduino IDE, Linux (Commandes de base & Installation).

**IT & Maintenance Hardware**
* **Assemblage & Réparation :** Montage de PC fixes et Serveurs, Remplacement de composants, Diagnostic de pannes matérielles.
* **Support :** Installation d'OS (Windows/Linux), Dépannage et résolution de conflits logiciels.

---

## 🚀 Projets Phares

### 📸 Intervallomètre WiFi pour mon Sony RX100M2 (Reverse Engineering et lecture de documentation Sony)
*Contrôle de caméra via WiFi en contournant l'application propriétaire.*
* **Hardware :** Arduino Nano ESP32 (**ESP32-S3**), Écran LCD 16x2.
* **Technique :** Création d'un **Portail Captif** pour la configuration (HTML/CSS embarqué) et envoi de commandes JSON (`setShootMode`, `actTakePicture`) à l'API Sony.
* **Fonctionnalité :** Calcul automatique de la durée du timelapse et feedback utilisateur sur LCD.
* [Voir le code >](#)

### 🔐 Coffre-fort RFID Autonome
*Système de contrôle d'accès avec gestion de base de données locale.*
* **Hardware :** Arduino Leonardo, Module RC522 (SPI), Stepper Motor, LED RGB, Haut-Parleur.
* **Algorithme :** Architecture basée sur une **Machine à États** (Startup, Veille, Admin, Accès) pour une fiabilité totale.
* **Fonctionnalité :** Mode "Master Card" permettant d'ajouter ou supprimer des badges utilisateurs dynamiquement sans ordinateur.
* [Voir le code >](#)

### 📡 Radar à Ultrasons & Visualisation PC
*Cartographie d'obstacles en temps réel.*
* **Hardware :** Arduino Leonardo, Capteur US-100, Stepper Motor.
* **Technique :** Utilisation du mode UART pour obtenir une mesure de distance précise (grâce à la compensation de température intégrée).
* **Interface :** Communication Série vers un script **Processing** pour l'affichage graphique type "radar".
* [Voir le code >](#)

---

## 🏠 Home Lab & Infrastructure
En parallèle de l'électronique, je gère ma propre infrastructure IT pour expérimenter :
* **Serveur NAS Personnel :** PC reconditionné sous **Ubuntu Server**, hébergeant **Jellyfin** pour le streaming de médias.
* **Cloud & Sécurité :** Déploiement d'une instance **Oracle Cloud** configurée avec un VPN **Tailscale (WireGuard)** pour l'accès distant sécurisé et le contournement de restrictions géographiques.

---

### 📫 Me contacter
Je suis ouvert aux opportunités de stage et aux collaborations !

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/matpisk07/)
