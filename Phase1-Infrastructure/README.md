
# Phase 1 — Infrastructure & Application vulnérable

## Objectif

Mettre en place un réseau d'entreprise local simulé avec accès internet,
et y héberger DVWA (Damn Vulnerable Web Application) comme cible d'audit.

---

##  Architecture
[Cloud/Internet]

|

[Switch GNS3]

/      |      

[Kali] [Ubuntu  ] [Windows XP]

[Server  ]

---

##  Machines virtuelles

| Machine | OS | Rôle |
|---|---|---|
| Kali Linux | Kali Linux (hôte) | Attaquant / Auditeur |
| Ubuntu Server | Ubuntu Server | Serveur web — héberge DVWA |
| Windows XP | Windows XP | Client du réseau |

---

## Outils utilisés

| Outil | Rôle |
|---|---|
| GNS3 | Simulation réseau — switch central |
| VirtualBox | Virtualisation des machines |
| Apache2 + PHP | Serveur web pour DVWA |
| MySQL | Base de données DVWA |
| DVWA | Application web vulnérable |

---

## 📋 Étapes réalisées

### Étape 1 — Configuration du réseau GNS3
- Ajout des VMs VirtualBox dans GNS3
- Connexion de toutes les machines à un switch central
- Ajout d'un cloud pour l'accès internet
- Vérification de la connectivité entre les machines (ping)

### Étape 2 — Installation de DVWA sur Ubuntu Server
- Mise à jour du système
- Installation Apache2, PHP, MySQL
- Téléchargement et configuration de DVWA
- Accès à DVWA depuis le navigateur de Kali

---

## Résultats

- [ ] Ping entre toutes les machines fonctionnel
- [ ] Accès internet depuis les VMs
- [ ] DVWA accessible via navigateur sur le réseau local
- [ ] Page de login DVWA opérationnelle

---

## 📸 Captures d'écran

*(à ajouter au fur et à mesure)*

---

## 🔗 Phase suivante

[Phase 2 — Capture et analyse du trafic réseau](../Phase 2 - Capture et analyse du trafic réseau/README.md)
