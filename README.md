# 💼 Générateur de Factures Pro

> Application web pour freelances : créez, sauvegardez et exportez vos factures professionnelles en quelques secondes.

![Statut](https://img.shields.io/badge/statut-actif-brightgreen)
![Type](https://img.shields.io/badge/type-outil%20freelance-blue)
![Public](https://img.shields.io/badge/public-freelances%20%26%20ind%C3%A9pendants-orange)
![Technos](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS-yellow)

---

## 📖 À propos

**Générateur de Factures Pro** est une application web conçue pour les **freelances et indépendants**. Elle permet de créer des factures complètes, conformes et professionnelles, **sans logiciel payant, sans inscription**.

Tout se passe dans le navigateur : vous remplissez le formulaire, la facture se construit en temps réel, puis vous l'exportez en **PDF**, **PNG** ou vous l'imprimez.

---

## ✨ Fonctionnalités

### 🏢 Informations émetteur
- Nom / Entreprise, adresse, email, téléphone
- **BCE / TVA** et **N° TVA**
- **IBAN** pour le paiement

### 👤 Gestion client
- Nom, adresse, email, BCE / TVA
- **Carnet de clients** (sauvegarde des coordonnées)

### 📄 Facture
- **Numéro de facture** automatique (ex : 2026-001)
- **Statut** (en attente, payée, etc.)
- **Date d'émission** et **date d'échéance**
- **Devise** (€, $, etc.)
- **Délai de paiement** en jours

### 📋 Prestations
- Lignes illimitées : description, quantité, prix unitaire, total
- Calcul automatique des totaux

### 💰 Totaux
- **TVA** personnalisable (%)
- **Remise** (%)
- Calcul automatique : sous-total, TVA, total

### 📝 Notes & Conditions
- Notes libres
- Instructions de paiement
- Mentions légales

### ✍️ Signature
- Upload d'image de signature (émetteur et/ou client)
- Suppression possible

### 📱 QR Code de paiement
- Génération d'un QR code (lien, IBAN, etc.)

### 🎨 Apparence
- **Couleur d'accent** personnalisable
- **Logo** optionnel

### 💾 Actions
- **Sauvegarder** la facture
- **Télécharger en PDF**
- **Télécharger en PNG**
- **Imprimer**
- **Dupliquer** une facture
- **Nouvelle facture**
- **Historique** des factures
- **Raccourcis clavier** : `Ctrl+S` (sauver), `Ctrl+P` (PDF), `Échap` (fermer)

---

## 🖥️ Aperçu

*(Ajoute ici une capture d'écran de l'application)*

![Aperçu du Générateur de Factures](screenshot.png)

🔗 **Démo en ligne** : [à ajouter après déploiement]
https://factures-pro.netlify.app/
---

## 🛠️ Technologies utilisées

- **HTML5** — structure de l'interface
- **CSS3** — design, responsive, thème clair/sombre
- **JavaScript** — logique, calculs, aperçu temps réel, export, QR code

*(Ajoute ici si tu utilises des bibliothèques : jsPDF, html2canvas, qrcode.js, etc.)*

---

## 🚀 Lancer le projet en local
bash
# 1. Cloner le repo
git clone https://github.com/Stephanie-VanSchoor/facture-freelance-.git

# 2. Entrer dans le dossier
cd facture-freelance-

# 3. Ouvrir index.html dans un navigateur
# ou lancer un serveur local :
python -m http.server 8000
