# 🎛️ BSB-LAN Documentation & Configuration

Ce dépôt rassemble ma documentation personnelle des paramètres de régulation Siemens ainsi que mes fichiers de configuration pour l'interface **[BSB-LAN](https://github.com/fredlcore/BSB-LAN)**.

---

## 📌 À propos de BSB-LAN

[BSB-LAN](https://github.com/fredlcore/BSB-LAN) est une solution matérielle et logicielle *open-source* basée sur ESP32 (ou Arduino) permettant d'interfacer des régulateurs de chauffage Siemens (utilisant les bus **BSB**, **LPB** ou **PPS**) avec des systèmes domotiques via MQTT, HTTP ou Modbus.

* 🌐 **Site officiel & Documentation :** [https://bsb-lan.github.io/](https://docs.bsb-lan.de/fr/index.html)
* 🐙 **Dépôt GitHub du projet :** [fredlcore/BSB-LAN](https://github.com/fredlcore/BSB-LAN)

---

## 📁 Contenu du dépôt

```text
.
├── attrs/                     # Fiches de documentation par paramètre Siemens/BSB-LAN
│   ├── 1600.md                # Mode de fonctionnement ECS
│   ├── 1610.md                # Consigne nominale ECS
│   ├── 1612.md                # Consigne réduite ECS
│   ├── 1620.md                # Libération ECS (HC / Programme horaire)
│   ├── 5950.md                # Entrée logique H1
│   └── 5970.md                # Entrée logique H2
└── BSB_LAN_custom_defs.h      # Définitions custom personnelles BSB-LAN
