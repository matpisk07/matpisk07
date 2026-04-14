# Salut, je suis Mattia Pischedda ! 👋

### Étudiant en L1 Cursus Master Ingénierie (CMI) Électronique à Sorbonne Université 🎓

Passionné par l'électronique embarquée, la culture Maker et l'informatique, je conçois des systèmes complets, du prototypage hardware jusqu'au développement firmware. Je suis actuellement candidat au **poste de Médiateur Étudiant (Espace Prototypage) pour l'année 2026/2027 à Sorbonne Université**.

---

##💡 Ma Philosophie Maker & Open Source
Je ne me contente pas de faire fonctionner un projet : mon but est que d'autres puissent le reproduire et l'améliorer. C'est pourquoi je m'efforce de **documenter** mes dépôts (schémas, reverse engineering, instructions de déploiement) et de publier mes travaux sous licence **GNU GPLv3**. J'aime l'idée de rendre la technique accessible au plus grand nombre.

---

## 🛠 Compétences Techniques

**Microcontrôleurs & IoT**
* **Espressif :** ESP32-S3, ESP8266.
* **Arduino/Atmel :** Leonardo, Mega 2560, Nano 33 BLE Sense.
* **RP2040 :** Raspberry Pi Pico.

**Développement & Logiciels**
* **Langages :** C++ (Arduino), Python (Algorithmique & Scripting).
* **Versioning :** Git & GitHub (Workflow en ligne de commande).
* **Concepts C++ :** Machines à états finis, Gestion non-bloquante (`millis`), Structures de données.
* **Web & Réseau :** API REST, Serveur Web embarqué, Protocoles UART/SPI/I2C.

**Cloud, Linux & Infrastructure**
* **Administration Cloud :** Gestion VPS (Oracle Cloud), Configuration VPN (Tailscale/WireGuard), Linux/Bash.
* **Outils de Production :** Déploiement Node.js, PM2, Nginx (Reverse Proxy), Sécurisation SSL.
* **Home Lab (Local) :** NAS (Ubuntu Server sur vieux PC), Streaming multimédia (Jellyfin).

---

## 🚀 Projets Phares

### 🔐 Coffre-fort RFID Autonome
*Système de contrôle d'accès avec gestion de base de données locale.*
* **Hardware :** Arduino Leonardo, Module RC522 (SPI), Stepper Motor, LED RGB, Haut-Parleur.
* **Algorithme :** Architecture basée sur une **Machine à États** (Startup, Veille, Admin, Accès) pour une fiabilité totale.
* **Fonctionnalité :** Mode "Master Card" permettant d'ajouter ou supprimer des badges utilisateurs dynamiquement sans ordinateur.
* [Voir le projet](https://github.com/matpisk07/RFID-Autonomous-Safe)

### 📡 Radar à Ultrasons & Visualisation PC
*Cartographie d'obstacles en temps réel.*
* **Hardware :** Arduino Leonardo, Capteur US-100, Stepper Motor.
* **Technique :** Utilisation du mode UART pour obtenir une mesure de distance précise (grâce à la compensation de température intégrée).
* **Interface :** Communication Série vers un script **Processing** pour l'affichage graphique type "radar".
* [Voir le projet](https://github.com/matpisk07/Ultrasonic-Radar-Visualization)

### 📸 Intervallomètre WiFi pour mon Sony RX100M2 (Reverse Engineering et lecture de documentation Sony)
*Contrôle de caméra via WiFi en contournant l'application propriétaire.*
* **Hardware :** Arduino Nano ESP32 (**ESP32-S3**), Écran LCD 16x2.
* **Technique :** Création d'un **Portail Captif** pour la configuration (HTML/CSS embarqué) et envoi de commandes JSON (`setShootMode`, `actTakePicture`) à l'API Sony.
* **Fonctionnalité :** Calcul automatique de la durée du timelapse et feedback utilisateur sur LCD.
* [Voir le projet](https://github.com/matpisk07/Sony-WiFi-Intervalometer)

### 🐀 TV Rat - Bot de Veille Intelligente
*Robot de recherche Leboncoin avec filtrage par apprentissage automatique.*
* **Architecture :** Node.js, Express, PM2.
* **Fonctionnalité :** Scan 24/7, calcul de distance GPS et **IA collaborative** (Naive Bayes) qui apprend des votes utilisateurs pour trier les annonces pertinentes.
* **Développement & Infra :** Projet codé avec l'assistance d'une IA et déployé de A à Z en seulement **6 heures**. Auto-hébergé sur mon serveur personnel sur **Oracle Cloud** avec configuration complète : domaine personnel **Cloudflare**, Reverse Proxy **Nginx** et certification **SSL**.
* 🌐 **Live Demo :** [tv-rat.matpisk.com](https://tv-rat.matpisk.com)
* [Voir le code source](https://github.com/matpisk07/TV-Rat)

---

## 🏠 Home Lab & Infrastructure
En parallèle de l'électronique, je gère ma propre infrastructure IT pour expérimenter :
* **Serveur NAS Personnel :** Réemploi d'un PC reconditionné sous **Ubuntu Server**, hébergeant **Jellyfin** pour le streaming de médias.
* **Cloud & Hosting :** Instance **Oracle Cloud** (VPS) gérée sous Linux, utilisée pour l'hébergement de services Web (Nginx, SSL). Elle sert également de passerelle VPN **Tailscale (WireGuard)** pour l'accès distant sécurisé et le contournement de restrictions géographiques.

---

### 📫 Me contacter
Je suis ouvert aux opportunités de stage et aux collaborations !

[![LinkedIn: Mattia PISCHEDDA](https://img.shields.io/badge/LinkedIn-Mattia%20PISCHEDDA-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matpisk07/)
