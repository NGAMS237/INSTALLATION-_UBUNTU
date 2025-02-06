# INSTALLATION_UBUNTU
# 🐧 Introduction à Ubuntu

Ubuntu est un système d'exploitation libre et open-source basé sur Linux. Développé par Canonical, il est reconnu pour sa simplicité d'utilisation, sa stabilité et sa sécurité. Ubuntu est largement utilisé dans les serveurs, le cloud computing, l'informatique personnelle et même l'embarqué.

## 📌 Description du Répertoire
Ce dépôt GitHub fournit une documentation détaillée sur l'installation et l'utilisation d'Ubuntu. Il est conçu pour aider les débutants à prendre en main Ubuntu et à maîtriser les commandes essentielles.

### 🔹 Contenu du Répertoire
- **Guide d’installation d’Ubuntu** : Étape par étape pour une installation réussie.
- **Premiers réglages** : Commandes essentielles après installation.
- **Liste des commandes Linux** : Navigation, gestion des fichiers, réseau, etc.
- **Astuces et optimisations** : Personnalisation et amélioration des performances.

## ✅ Pourquoi utiliser Ubuntu ?

- **Gratuit et open-source** : Pas de licence payante, un code source accessible à tous.
- **Stabilité et sécurité** : Moins vulnérable aux virus et aux logiciels malveillants.
- **Communauté active** : Un grand nombre de forums et de ressources en ligne pour l'entraide.
- **Personnalisable** : Compatible avec divers environnements de bureau comme GNOME, KDE, XFCE.
- **Idéal pour le développement** : Prend en charge de nombreux langages de programmation et outils DevOps.

## 📥 Téléchargement et Installation d’Ubuntu

Avant de commencer l’installation, voici ce dont vous aurez besoin :

### 🔹 Prérequis
- Un PC avec au moins **2 Go de RAM** (4 Go recommandés).
- Un espace disque de **25 Go minimum**.
- Une clé USB d’au moins **8 Go**.
- Un fichier ISO d’Ubuntu (téléchargeable sur le site officiel : [ubuntu.com](https://ubuntu.com/)).

### 🔹 Étapes d’Installation

1. **Télécharger l’ISO d’Ubuntu** depuis le site officiel.
2. **Créer une clé USB bootable** avec un outil comme Rufus (Windows) ou BalenaEtcher (Linux/Mac).
3. **Démarrer depuis la clé USB** en accédant au BIOS/UEFI et en sélectionnant le périphérique de démarrage.
4. **Suivre l’assistant d’installation** :
   - Choisir la langue et la disposition du clavier.
   - Sélectionner le type d’installation (normal ou minimal).
   - Créer un utilisateur et définir un mot de passe.
   - Attendre la fin du processus et redémarrer le PC.

## 🚀 Premiers pas après l’installation

Une fois Ubuntu installé, il est conseillé d’effectuer quelques réglages initiaux :

```bash
# Mettre à jour le système
sudo apt update && sudo apt upgrade -y

# Installer des logiciels essentiels
sudo apt install -y curl git vim htop
```

## 📜 Liste des commandes essentielles

| Commande | Description |
|----------|-------------|
| `ls` | Liste les fichiers et dossiers du répertoire courant. |
| `cd nom_du_dossier` | Change de répertoire. |
| `pwd` | Affiche le chemin du répertoire actuel. |
| `mkdir nom_du_dossier` | Crée un nouveau dossier. |
| `rm fichier` | Supprime un fichier. |
| `sudo apt install nom_du_paquet` | Installe un logiciel. |
| `sudo apt remove nom_du_paquet` | Désinstalle un logiciel. |
| `df -h` | Affiche l’espace disque disponible. |
| `ip a` | Affiche l’adresse IP locale. |

🔹 **Prochaines étapes** : Nous allons approfondir chaque commande et voir comment optimiser Ubuntu ! 😊

