# Secure-Lab-Conception-et-s-curisation-progressive-d-un-r-seau-d-entreprise-local
Ce projet simule la mise en place et la sécurisation progressive d'un réseau d'entreprise local. L'objectif est de partir d'une infrastructure volontairement vulnérable et d'y appliquer, couche par couche, des solutions de sécurité réelles utilisées en entreprise.

---

## Phases du projet

### Phase 1 — Infrastructure & Application vulnérable
Mise en place d'un réseau local avec Ubuntu Server, un client Windows et Kali Linux.
Hébergement de DVWA (Damn Vulnerable Web Application) comme cible d'audit.

### Phase 2 — Capture et analyse du trafic réseau
Analyse du trafic généré entre les machines avec Wireshark.
Identification des flux suspects, protocoles exposés et données sensibles en clair.

### Phase 3 — Déploiement pfSense
Mise en place d'un pare-feu pfSense pour segmenter et filtrer le trafic réseau.
Configuration des règles de filtrage et des interfaces.

### Phase 4 — IDS/SIEM avec Suricata et Wazuh
Déploiement de Suricata pour la détection d'intrusion et Wazuh pour la
centralisation et corrélation des alertes de sécurité.

---

## Outils utilisés

| Outil | Rôle |
|---|---|
| Kali Linux | Machine attaquante / auditeur |
| Ubuntu Server | Serveur cible |
| DVWA | Application web vulnérable |
| Wireshark | Analyse du trafic réseau |
| pfSense | Pare-feu / routeur |
| Suricata | IDS — détection d'intrusion |
| Wazuh | SIEM — corrélation et alertes |
| VirtualBox/GNS3 | Virtualisation et simulation réseau |

---

## Auteur

**Hikwoulbo Talerant** — Ingénieur en Systèmes et Logiciels en Environnement Distribué  
Spécialisation : Cybersécurité & détection réseau  
📧 [hikwoulbotalerant@gmail.com] | 🔗 [www.linkedin.com/in/ing-hikson-talerant-165867272]

---

## Statut du projet

| Phase | Statut |
|---|---|
| Phase 1 — Infrastructure | 🔄 En cours |
| Phase 2 — Analyse trafic | ⏳ À venir |
| Phase 3 — pfSense | ⏳ À venir |
| Phase 4 — Suricata/Wazuh | ⏳ À venir |
