# SAÉ12 – S'initier aux réseaux informatiques

> SAÉ de 1ère année – BUT Réseaux & Télécommunications  
> Université de Guyane – IUT de Kourou

---

## 📌 Description du projet

Projet réalisé dans le cadre de la SAÉ12 : **configuration d'un point d'accès WiFi (hotspot)** sur un **Raspberry Pi 4** en utilisant des outils Linux dédiés à la gestion réseau.

Le projet se décompose en deux parties :
- Une **présentation/étude** d'un paquet réseau Linux
- Un **déploiement complet** du hotspot avec compte-rendu et démonstration

---

## 🎯 Compétences travaillées

- Prise en main du **Raspberry Pi 4** sous Linux
- Configuration d'un **point d'accès WiFi** avec `hostapd`
- Attribution d'adresses IP via un serveur **DHCP** (`dnsmasq` / `isc-dhcp-server`)
- Mise en place de règles de **pare-feu et sécurité** (`iptables`, `fail2ban`)
- Segmentation réseau avec les **VLANs**
- Rédaction d'une **documentation technique** (compte-rendu de déploiement)
- **Démonstration live** du fonctionnement du hotspot

---

## 🛠️ Stack technique

![Raspberry Pi]
![Linux]
![Bash]

**Paquets Linux utilisés :**

| Paquet | Rôle |
|---|---|
| `hostapd` | Création du point d'accès WiFi |
| `dnsmasq` | Serveur DNS et DHCP léger |
| `iptables` | Pare-feu et routage NAT |
| `fail2ban` | Protection contre les attaques par force brute |
| `isc-dhcp-server` | Attribution dynamique d'adresses IP |

---

## 🗂️ Contenu du répertoire

```
Project-Sae-S-initier-aux-reseaux-informatiques/
├── compte-rendu/      # Documentation du déploiement
├── presentation/      # Support de présentation (partie 1)
└── README.md
```

---

## 🎓 Contexte académique

- **Formation** : BUT Réseaux & Télécommunications – 1ère année
- **Module** : SAÉ12 – S'initier aux réseaux informatiques
- **Établissement** : Université de Guyane – IUT de Kourou
- **Encadrants** : C. Jean & A. Hovsepian

---

*Répertoire à visée pédagogique – projet réalisé en contexte de formation.*
