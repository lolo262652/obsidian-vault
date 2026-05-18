# 👥 Clients — Gestion & Suivi

## 📝 Fiche client type

```
Nom / Société : ________________________
Adresse : ______________________________
Téléphone : ____________________________
Email : ________________________________
Secteur : ☐ Particulier  ☐ Professionnel
Source : ☐ Bouche-à-oreille  ☐ Google  ☐ Pages Jaunes  ☐ Autre

**Chantier :** _________________________
**Adresse chantier :** _________________
**Montant devis :** _____ € TTC
**Date devis :** ___/___/_____
**Devis accepté ?** ☐ Oui  ☐ Non  ☐ En attente
**Date début travaux :** ___/___/_____
**Date fin prévue :** ___/___/_____
**Montant facturé :** _____ € TTC
**Solde :** ☐ Payé  ☐ En attente  ☐ Relancer
```

## 📊 Suivi des chantiers

### Tableau de bord
| Client | Travaux | Devis | Accepté | Début | Fin | Payé | Statut |
|--------|---------|:-----:|:-------:|:-----:|:---:|:----:|:------:|
| | | | ☐ | | | ☐ | |
| | | | ☐ | | | ☐ | |
| | | | ☐ | | | ☐ | |

### Statuts possibles
- 📌 **Prospect** — Devis envoyé, en attente
- ✅ **Confirmé** — Devis accepté, planification en cours
- 🔧 **En cours** — Chantier démarré
- ✅ **Terminé** — Travaux finis, facture émise
- 💰 **Soldé** — Paiement reçu complet
- ❌ **Perdu** — Devis refusé ou abandonné

## 🔄 Relances automatiques
- 7 jours après devis → « Avez-vous une question sur le devis ? »
- 30 jours après facture impayée → Relance paiement
- 6 mois après chantier → « Besoin d'un entretien ? »

## 📁 Documents par client
Créer un dossier par client avec :
1. `[Client] - Devis N°XXX.md`
2. `[Client] - Facture N°XXX.md`
3. `[Client] - Photos chantier.md`

---

⬅️ Retour à [[🏠 Index - Présentation]]
