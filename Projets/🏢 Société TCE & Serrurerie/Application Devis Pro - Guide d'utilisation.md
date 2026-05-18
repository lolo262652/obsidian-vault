# 📱 Application Devis Pro — Guide d'utilisation

> **URL :** http://173.249.10.24:8081/index.html
> **Serveur :** Python (`~/societe-tce-serrurerie/devis-app/serveur.py`)

---

## 🏠 Pages de l'application

| Page | Description |
|------|-------------|
| 📋 **Devis** | Tableau de bord — liste de tous les devis |
| ➕ **Nouveau** | Créer un nouveau devis |
| ⚙️ **Paramètres** | Configuration des travaux et de l'entreprise |

---

## 📝 Créer un devis

1. Clique sur **"Nouveau devis"**
2. Remplis les infos **client** (Nom, Email, Adresse, Tél)
3. Choisis le **type** (TCE ou Serrurerie) et la **TVA**
4. Ajoute des **pièces** (Cuisine, SdB, Salon, Chambre...)
5. Clique sur les **présélections** pour ajouter des travaux, ou saisis-les manuellement
6. Remplis les **quantités et prix**
7. Ajoute le **délai**, l'**acompte**, les **conditions**
8. **Sauvegarde** le devis

## 📤 Envoyer au client

1. Clique sur **"Envoyer"**
2. Le devis est sauvegardé puis envoyé par email
3. Le client reçoit le devis **+ un lien pour signer en ligne**
4. Quand il signe, tu reçois un email de notification ✅

## 🔗 Signature client

- Le client ouvre le lien : `http://173.249.10.24:8081/devis/<ID>`
- Il voit le devis complet
- Il dessine sa signature (souris ou doigt)
- Il clique sur "Signer le devis"
- Tu reçois une notification par email

## ⚙️ Paramétrage des travaux

**Onglet "Travaux par pièce" :**
- Modifie les noms, prix et unités des prestations
- Ajoute ou supprime des prestations
- Ajoute de nouvelles catégories de pièces

**Onglet "Mon entreprise" :**
- Nom de l'entreprise, gérant, adresse
- Téléphone, email, site web
- SIRET, RCS, TVA intracommunautaire
- Assurance RC Pro
- Zone d'intervention
- Logo (PNG/JPG, max 500 Ko)

## 💾 Sauvegarde

- Les devis sont sauvegardés **localement** (navigateur) + **sur le serveur**
- Les paramètres (travaux, entreprise) sont stockés dans le navigateur

## 🖨️ Impression

- Clique sur **"PDF"** → imprime ou enregistre en PDF
- Le devis formaté inclut : en-tête, pièces, totaux, signature, mentions légales

---

⬅️ Retour à [[🏠 Index - Présentation]]
