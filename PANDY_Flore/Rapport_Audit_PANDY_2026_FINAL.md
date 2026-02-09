# Rapport d'Investigation Numérique (Investigation On-chain)

**DOSSIER :** Flore PANDY
**REF :** PF-2026-02-06
**DATE :** 9 février 2026
**STATUT :** CONFIDENTIEL

---

## SOMMAIRE
1. LEXIQUE
2. OBJECTIF DE LA MISSION
3. MÉTHODOLOGIE CATC KLYR
4. PROTAGONISTES
5. INVENTAIRE DES PIÈCES
6. FAITS SIGNALÉS
7. RÉSULTATS DE L'ENQUÊTE
8. CONCLUSION & RÉQUISITIONS

---

## LEXIQUE
| Terme | Définition |
| :--- | :--- |
| **Portefeuille (Wallet)** | Portefeuille numérique permettant de stocker des crypto-actifs. |
| **TX (Transaction)** | Transaction enregistrée de manière publique et immuable sur une blockchain. |
| **TXID** | Identifiant unique d'une transaction. |
| **CEX** | Plateforme d'échange centralisée (ex: Binance, KuCoin) soumise au KYC. |
| **KYC** | "Know Your Customer" : processus d'identification obligatoire des utilisateurs. |
| **Off-Ramp** | Point de sortie permettant de convertir des cryptos en monnaie fiduciaire (FIAT). |
| **Hub** | Portefeuille central utilisé par les auteurs pour agréger les fonds des victimes. |

---

## OBJECTIF DE LA MISSION
Dans le cadre de la présente mission, il a été procédé à une analyse portant sur des faits d’escroquerie présumée sur actifs numériques au préjudice de Mme Flore PANDY. 

L'analyse vise à :
1. Reconstituer la chronologie exacte des flux financiers.
2. Identifier les adresses de dépôt des auteurs (Hubs).
3. Localiser les points de sortie (Off-ramps) vers des plateformes centralisées pour permettre des réquisitions judiciaires.

---

## MÉTHODOLOGIE CATC KLYR
L'investigation repose sur le protocole CATC :
- **COLLECTE** : Recueil des preuves (PDF, captures d'écran, TXIDs).
- **ANALYSE** : Examen des transactions on-chain sur la blockchain Bitcoin (BTC).
- **TRAÇAGE** : Reconstruction des circuits de flux (E-1, E-2, E-3).
- **CORRÉLATION** : Croisement des flux financiers avec le narratif des échanges (Nicolas / Mint-Firms).

---

## PROTAGONISTES
| Rôle | Identifiant | Description |
| :--- | :--- | :--- |
| **Victime** | Flore PANDY | Utilisatrice ciblée par une fraude à l'investissement. |
| **Auteur (Nicolas)** | Nicolas | Interlocuteur Telegram, se présentant comme manager d'investissement. |
| **Entité Frauduleuse** | Mint-Firms | Plateforme de trading fictive. |
| **Hub Escrocs** | `bc1qh9jcy9cr...vr5` | Portefeuille de consolidation des fonds dérobés. |

---

## INVENTAIRE DES PIÈCES
- **Pièce 1** : `Preuves des dépôts.pdf` - Confirmation des envois BTC.
- **Pièce 2** : `Les-echanges.pdf` - Historique des communications avec l'auteur.
- **Pièce 3** : `tracing_results.json` - Données brutes issues de l'analyse on-chain.

---

## FAITS SIGNALÉS
L'escroquerie s'est déroulée en quatre phases distinctes :

1. **Phase 1 - Mise en confiance (11/02/2025)** : Premier dépôt "test" de 0.00476200 BTC.
2. **Phase 2 - Effet Miroir / Limbe (15/02/2025)** : Suite à un prétendu problème technique, la victime est incitée à doubler son dépôt (0.00476375 BTC) pour "débloquer" les fonds.
3. **Phase 3 - Escalade "Plan 2" (20/03/2025)** : Pression psychologique pour passer à un palier d'investissement supérieur (0.00674487 BTC).
4. **Phase 4 - Frais TCN (25/03/2025)** : Annonce d'un gain fictif massif de 144 594 $. Le retrait est conditionné au paiement d'une "Clé TCN" (0.02285892 BTC). Suite à ce dernier versement, tout contact est rompu.

---

## RÉSULTATS DE L'ENQUÊTE

### 1. Analyse des flux sortants (Victime → Escrocs)
Le montant total détourné s'élève à **0.03912954 BTC**, soit environ **3 500 €** au cours moyen des transactions.

### 2. Traçage On-chain (Circuit E-1)
L'ensemble des fonds a été dirigé vers le Hub de consolidation suivant :
`bc1qh9jcy9cr4qj6q25rw9m00yu4eek9tydj2awvr5`

### 3. Identification des Off-Ramps (Points de sortie)
L'analyse de sortie du Hub révèle des transferts vers des plateformes centralisées :

- **KUCOIN** :
  - **Adresse** : `3EjgkZipNXbF8CF25oQTAq9nP19LCbTor5`
  - **TXID** : `36b06760413a7c7abb5502df2886ae32613845ba3f5843c145d1af24c9ba30cb`
  - **Montant** : 0.02790793 BTC

- **BINANCE** :
  - Des flux fractionnés via SimpleSwap ont été identifiés vers des adresses liées à l'écosystème Binance.

---

## CONCLUSION & RÉQUISITIONS
L'enquête technique confirme une fraude à l'investissement caractérisée par l'utilisation de techniques de manipulation ("Limbe", "Frais de déblocage"). Les fonds sont désormais localisés sur des plateformes soumises aux régulations KYC.

**Préconisations de réquisitions prioritaires :**
1. **KUCOIN** : Identifier le titulaire du compte lié à l'adresse `3EjgkZipNXbF8CF25oQTAq9nP19LCbTor5`.
2. **BINANCE** : Demander l'historique des comptes ayant reçu des fonds via le circuit SimpleSwap identifié.

---
*Fait à Paris, le 09/02/2026.*
*Signature : Cabinet d'Investigation KLYR / Little Finger*
