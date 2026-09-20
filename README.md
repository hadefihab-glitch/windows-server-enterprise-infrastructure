# 🖥️ Windows Server Enterprise Infrastructure

## 📌 Présentation du projet

Dans le cadre de ce projet, j’ai mis en place une infrastructure réseau d’entreprise virtualisée avec VirtualBox.

L’objectif était de créer un environnement permettant de centraliser la gestion des utilisateurs, des ordinateurs, des adresses IP et des règles de sécurité.

L’infrastructure repose principalement sur **Windows Server**, avec l’intégration de **Active Directory Domain Services (AD DS), DNS, DHCP, GPO et File Server**, ainsi que **pfSense** pour la gestion du réseau.

## 🛠️ Technologies utilisées

- Windows Server
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Group Policy (GPO)
- File Server
- pfSense
- Windows Client
- VirtualBox

## ⚙️ Réalisations

Au cours de ce projet, j’ai réalisé :

- Installation et configuration de Windows Server
- Mise en place d’Active Directory
- Création et organisation des OU
- Création des utilisateurs et groupes de sécurité
- Configuration du service DNS
- Configuration d’une plage DHCP
- Intégration d’un poste Windows au domaine
- Création et application de stratégies GPO
- Configuration des interfaces WAN et LAN de pfSense
- Tests de connectivité et validation de l’infrastructure

---
# 📸 Captures du projet

## 01 — Services Windows Server
![Services Windows Server](screenshots/01-windows-server-services.png)

## 02 — Configuration de la plage DHCP
![DHCP](screenshots/02-dhcp-address-pool.png)

## 03 — Configuration WAN et LAN de pfSense
![pfSense WAN LAN](screenshots/03-pfsense-wan-lan.png)

## 04 — Interface Web pfSense
![pfSense Dashboard](screenshots/04-pfsense-dashboard.png)

## 05 — Configuration réseau du serveur
![Server Network](screenshots/05-server-network-configuration.png)

## 06 — Organisation des OU et des utilisateurs
![Active Directory](screenshots/06-active-directory-ou-users.png)

## 07 — OU Direction et utilisateur
![OU Direction](screenshots/07-ou-direction-user.png)

## 08 — Groupe de sécurité GRP-RH
![GRP-RH](screenshots/08-grp-rh-security-group.png)

## 09 — Configuration de la GPO Direction
![GPO Direction](screenshots/09-gpo-direction.png)

## 10 — Validation de la GPO Direction
![GPO Validation](screenshots/10-gpo-direction-validation.png)

## 11 — Configuration IP du poste client
![Client IP](screenshots/11-client-ip-configuration.png)

## 12 — Vérification de l'utilisateur du domaine
![Domain User](screenshots/12-domain-user-verification.png)

## 13 — Connexion de l'utilisateur Active Directory
![AD Login](screenshots/13-active-directory-login.png)
