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

## 🖥️ Services Windows Server

Configuration des principaux services Windows Server.

![Services Windows Server](screenshots/windows-server-services.png)

---

## 🌐 Configuration de la plage DHCP

Configuration de la plage d’adresses DHCP sous Windows Server.

![Configuration DHCP](screenshots/Configuration%20de%20la%20plage%20d’adresses%20DHCP%20sous%20Windows%20Server.png)

---

## 🔥 Configuration WAN et LAN de pfSense

Configuration des interfaces réseau WAN et LAN de pfSense.

![Interfaces pfSense](screenshots/Configuration%20des%20interfaces%20réseau%20WAN%20et%20LAN%20de%20pfSense.png)

---

## 🔐 Interface Web d’administration de pfSense

Accès au tableau de bord Web de pfSense.

![Tableau de bord pfSense](screenshots/Interface%20Web%20d’administration%20de%20pfSense%20–%20Tableau%20de%20bord.png)

---

## 👥 Organisation Active Directory

Création des OU RH et Direction et gestion des utilisateurs dans Active Directory.

![Active Directory](screenshots/Création%20des%20OU%20RH%20et%20Direction%20et%20gestion%20des%20utilisateurs%20dans%20Active%20Directory.png)

---

## 👤 OU Direction

Création de l’OU Direction et ajout de l’utilisateur Ahmed Directeur.

![OU Direction](screenshots/Création%20de%20l’OU%20Direction%20et%20ajout%20de%20l’utilisateur%20Ahmed%20Directeur.png)

---

## 👥 Groupe de sécurité GRP-RH

Ajout des utilisateurs RH au groupe de sécurité GRP-RH.

![GRP-RH](screenshots/Ajout%20des%20utilisateurs%20RH%20au%20groupe%20de%20sécurité%20GRP-RH.png)

---

## 🔒 Configuration de la GPO Direction

Configuration de la GPO Direction avec restriction du Gestionnaire des tâches.

![GPO Direction](screenshots/Configuration%20de%20la%20GPO%20Direction%20–%20Restriction%20du%20Gestionnaire%20des%20tâches.png)

---

## ✅ Vérification de la GPO-DIRECTION

Vérification de l’application de la GPO-DIRECTION sur l’utilisateur Ahmed Directeur.

![Validation GPO](screenshots/Vérification%20de%20l’application%20de%20la%20GPO-DIRECTION%20sur%20l’utilisateur%20Ahmed%20Directeur.png)

---

## 💻 Configuration IP du poste Ahmed Directeur

Vérification de la configuration IP du poste Ahmed Directeur et de la passerelle pfSense.

![Configuration IP](screenshots/Vérification%20de%20la%20configuration%20IP%20du%20poste%20Ahmed%20Directeur%20et%20de%20la%20passerelle%20pfSense.png)

---

## 🌐 Vérification de la configuration réseau

Vérification de la configuration réseau DHCP et de la passerelle pfSense.

![Configuration réseau](screenshots/Vérification%20de%20la%20configuration%20réseau%20DHCP%20et%20de%20la%20passerelle%20pfSense.png)

---

## 👤 Vérification de la connexion au domaine

Vérification de la connexion de l’utilisateur Ahmed Directeur au domaine Active Directory.

![Connexion domaine](screenshots/Vérification%20de%20la%20connexion%20de%20l’utilisateur%20Ahmed%20Directeur%20au%20domaine%20Active%20Directory.png)

---

## 🔑 Connexion Active Directory

Connexion réussie d’un utilisateur Active Directory sur un poste client.

![Connexion Active Directory](screenshots/Connexion%20réussie%20d’un%20utilisateur%20Active%20Directory%20sur%20un%20poste%20client.png)
