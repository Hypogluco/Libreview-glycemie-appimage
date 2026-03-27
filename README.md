# 🩸 HypoGluco-App

Application légère pour afficher votre glycémie LibreView directement sur le bureau Linux, Windows et Mac OS

⚠️ **Projet non officiel** – non affilié à Abbott / LibreView.

---

## ✨ Fonctionnalités

* 📡 Récupération automatique des données LibreView
* 🖥️ Affichage en widget discret sur le bureau
* 🔄 Mise à jour automatique (toutes les 60 secondes)
* 🎯 Couleur selon glycémie :

  * 🔴 < 70 → hypoglycémie
  * 🟢 70–180 → normal
  * 🟠 > 180 → hyperglycémie
* 📌 Position mémorisée
* 🔒 Mode verrouillage (anti-déplacement)
* 🔍 Taille de police ajustable à la molette
* ⚡ Rafraîchissement manuel (clic molette)
* ❌ Quitter avec triple clic

---

## 📦 Installation

**HypoGluco** est une application multiplateforme, disponible pour **Windows** et **Linux**. Aucune installation n'est nécessaire.

### 🔽 Pour Windows :

1. Télécharger le fichier `HypoGluco.exe` depuis **Releases**.
2. Double-cliquez sur l'exécutable pour lancer l'application.

### 🔽 Pour macOS :
Télécharger le fichier .zip depuis la section Releases.
Décompresser le fichier et Glisser-déposer l'application HypoGluco dans votre dossier Applications.
Lancer l'application depuis le dossier Applications.

### 🔽 Pour Linux (AppImage) :

1. Télécharger le fichier `.AppImage` depuis **Releases**.
2. Rendre le fichier exécutable :

   ```bash
   chmod +x HypoGluco.AppImage

   
## 🔐 Première utilisation

Lors du premier lancement :

* entrez vos identifiants LibreView
* ils sont stockés localement sur votre machine

🔽 Pour macOS :
Télécharger le fichier .app depuis la section Releases.
Glisser-déposer l'application HypoGluco dans votre dossier Applications.
Lancer l'application depuis le dossier Applications.

---

## 🖱️ Utilisation

| Action             | Effet                       |
| ------------------ | --------------------------- |
| Clic gauche        | Déplacer                    |
| Clic droit         | Verrouiller / déverrouiller |
| Molette            | Changer taille du texte     |
| Clic molette       | Rafraîchir                  |                 
| Triple clic gauche | Quitter                     |

---


# 📸 3. Screenshot 


<img width="950" height="246" alt="display" src="https://github.com/user-attachments/assets/efc9a981-88c3-464e-90e4-fad6e559c08d" />
<img width="1000" height="374" alt="login" src="https://github.com/user-attachments/assets/08f1cbd8-7825-4fe1-bc34-adc8f46a7186" />



## ⚠️ Limitations connues

* L’icône du fichier `.AppImage` peut apparaître générique sous GNOME (normal)
* Dépend de l’API LibreView (peut changer côté serveur)
* Nécessite une connexion internet

---

## 🛠️ Technologies

* Python 3
* PyQt5
* Requests
* PyInstaller
* AppImage

---

## 🔄 Mises à jour

Téléchargez simplement la nouvelle version dans **Releases**.

Aucune installation requise.

---

## ❤️ Contribution

Ce projet est distribué gratuitement pour aider les personnes diabétiques.

Les contributions, idées et retours sont les bienvenus.

---

## ⚖️ Avertissement

Ce logiciel :

* n’est pas un dispositif médical
* ne remplace pas un avis médical
* est fourni tel quel, sans garantie

---
