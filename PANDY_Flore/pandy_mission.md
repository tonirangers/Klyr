# Mission : Enquête Approfondie & Rapport Final "Cabinet d'Audit" - PANDY Flore

## Contexte Critique
L'utilisateur a rejeté la V1 du rapport car trop superficielle. Il attend une "pièce de procédure ultra-détaillée" digne d'un cabinet d'audit (type "KLYR Intelligence").
Tu disposes de preuves réelles dans : `CLAW_WORK/KLYR/PANDY_Flore/evidence/`
- `Preuves des dépôts.pdf` (5MB)
- `Preuves.pdf` (1MB)
- Screenshots divers

## Objectif
Produire le rapport définitif : `CLAW_WORK/KLYR/PANDY_Flore/Rapport_Audit_PANDY_2026_FINAL.md`
Ce document doit être FACTUEL, CHIRURGICAL et EXHAUSTIF.

## Protocole d'Exécution (Ralph Loop)
Ne te précipite pas. Prends le temps d'analyser.

### Étape 1 : Analyse des Preuves (ITERATION 1-2)
- Lis/OCR les fichiers PDF et images dans `evidence/`.
- Extrais TOUTES les dates, montants, TXIDs, et adresses.
- Extrais les noms d'entités (mint-firms, Nicolas, etc.).
- LOGUE tes découvertes dans le Dashboard (ex: "[ANALYSIS] Extraction: Dépôt de 400€ identifié le XX/XX...").

### Étape 2 : Reconstruction de la Chronologie (ITERATION 3)
- Croise les preuves avec le récit de la victime.
- Établis la Timeline exacte : Contact -> Dépôt -> "Gains" -> Demande TCN -> Blocage.

### Étape 3 : Traçage On-Chain (ITERATION 4)
- Identifie les circuits E-1, E-2, E-3 (comme mentionné dans le dossier).
- Pour chaque hop, fournis : Date | From | To | Montant | Hash | Type (Wallet Perso vs CEX).
- Sois précis sur les points de sortie (Binance/KuCoin).

### Étape 4 : Rédaction "Cabinet" (ITERATION 5-6)
Structure le rapport FINAL exactement comme suit :
1.  **En-tête Officiel** : Références dossier, dates, statut "CONFIDENTIEL".
2.  **Lexique complet** : (Reprends le tableau standard KLYR).
3.  **Objectif de la Mission** : Ton procédural et pénal.
4.  **Méthodologie CATC KLYR** : Détail des 4 phases (Collecte/Analyse/Traçage/Corrélation).
5.  **Inventaire des Pièces** : Liste exhaustive des fichiers analysés.
6.  **Protagonistes** : Tableau précis (Rôle/ID/Desc).
7.  **Faits Signalés** : Analyse chronologique détaillée (Phases 1 à 4).
8.  **Résultats de l'Enquête (Cœur du rapport)** :
    - Tableaux des flux (E-1, E-2...).
    - Schémas explicatifs (Texte ou Mermaid).
    - Identification formelle des Off-Ramps.
9.  **Conclusion & Réquisitions** : Modèles de lettres pour KuCoin et Binance.

## Instructions de Communication (Dashboard)
- À chaque étape, utilise `broadcastToDashboard` pour dire ce que tu fais.
- Ex: "J'analyse le PDF 'Preuves des dépôts'...", "Je détecte une incohérence dans le montant X...", "Je rédige la section méthodologie...".
- Ne marque "RALPH_DONE" que lorsque le fichier est PARFAIT.

## Fichier de Sortie
`CLAW_WORK/KLYR/PANDY_Flore/Rapport_Audit_PANDY_2026_FINAL.md`
