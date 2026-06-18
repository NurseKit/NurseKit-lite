---
{"dg-publish":true,"permalink":"/Calculs Doses/Exercices Débit Perfusion/","tags":["calculs-doses","ue-4-4","exercices","débit"],"dg-note-properties":{"nom":"Calculs de doses - Débits de perfusion","type":"Exercices pratiques","tags":["calculs-doses","ue-4-4","exercices","débit"],"revision":"2026-06-14"}}
---


> [!tip] Méthode générale
> - **En mL/h** : Débit = Volume (mL) / Durée (h)
> - **En gtt/min** : Débit = [Volume (mL) × Facteur chute] / Durée (min)
> - Macrogouttes : facteur 20 gtt/mL | Microgouttes : facteur 60 gtt/mL

---

## Exercice 1 : Paracétamol IV simple

**Situation clinique :**
M. Bernard, 58 ans, hospitalisé en chirurgie orthopédique après une prothèse de hanche. Le médecin prescrit du paracétamol IV pour la douleur post-opératoire.

**Prescription :** Paracétamol 1g IV dans 100 mL, à passer en 15 min

**Question :** Quel débit programmer en mL/h sur la pompe à perfusion ?

> [!success]- Correction
> **Données :**
> - Volume : 100 mL
> - Durée : 15 min = 15/60 h = 0,25 h
>
> **Calcul :**
> Débit = Volume / Durée = 100 mL / 0,25 h = **400 mL/h**
>
> **Vérification :** 400 mL/h × 0,25 h = 100 mL ✓ → Ce débit élevé est normal pour un passage rapide sur 15 min.

---

## Exercice 2 : Amoxicilline en perfusion

**Situation clinique :**
Mme Dupont, 72 ans, traitée pour une pneumonie bactérienne. Elle a une voie veineuse périphérique au bras gauche.

**Prescription :** Amoxicilline 2g IV, dilué dans 100 mL de NaCl 0,9%, à passer en 30 min

**Question :** Quel débit programmer en mL/h ?

> [!success]- Correction
> **Données :**
> - Volume : 100 mL
> - Durée : 30 min = 0,5 h
>
> **Calcul :**
> Débit = 100 / 0,5 = **200 mL/h**
>
> **Vérification :** 200 mL/h × 0,5 h = 100 mL ✓

---

## Exercice 3 : NaCl 0,9% en gouttes/min (macrogouttes)

**Situation clinique :**
M. Leroy, 45 ans, hospitalisé pour déshydratation. Pas de pompe disponible → perfusion par gravité avec tubulure macrogouttes (facteur 20 gtt/mL).

**Prescription :** NaCl 0,9% 500 mL à passer en 4h

**Question :** Quel débit régler en gouttes/min ?

> [!success]- Correction
> **Données :**
> - Volume : 500 mL
> - Durée : 4h = 240 min
> - Facteur chute : 20 gtt/mL (macrogouttes)
>
> **Calcul :**
> Débit = (500 × 20) / 240 = 10 000 / 240 = **41,7 ≈ 42 gtt/min**
>
> **Vérification :** sens clinique correct pour une réhydratation adulte modérée.

---

## Exercice 4 : Furosémide IV lent

**Situation clinique :**
Mme Moreau, 80 ans, insuffisance cardiaque décompensée. Le médecin prescrit un diurétique IV.

**Prescription :** Furosémide (Lasilix®) 40 mg IV lent, à passer en 20 min. Disponible : ampoule 20 mg/2 mL. Diluer dans 50 mL de NaCl 0,9%.

**Questions :**
1. Combien d'ampoules prélever ?
2. Quel débit programmer en mL/h ?

> [!success]- Correction
> **Question 1 → Nombre d'ampoules :**
> - Dose prescrite : 40 mg
> - 1 ampoule = 20 mg → **2 ampoules** (soit 4 mL prélevés)
>
> **Question 2 → Débit :**
> - Volume total : 50 mL (NaCl) + 4 mL (médicament) = 54 mL
> - Durée : 20 min = 20/60 h = 0,333 h
>
> Débit = 54 / 0,333 = **162 mL/h**
>
> **Vérification :** passage rapide sur 20 min → débit élevé normal. Surveiller la tension artérielle.

---

## Exercice 5 : Calcul de la durée

**Situation clinique :**
En arrivant à votre poste, vous constatez qu'une poche de glucosé 5% de 250 mL est en cours. Le débit est réglé à 83 mL/h.

**Question :** Dans combien de temps cette perfusion sera-t-elle terminée ? (il reste 250 mL)

> [!success]- Correction
> **Données :**
> - Volume restant : 250 mL
> - Débit : 83 mL/h
>
> **Calcul :**
> Durée = Volume / Débit = 250 / 83 = **3,01 h ≈ 3h**
>
> **Vérification :** 83 mL/h × 3h = 249 mL ≈ 250 mL ✓ → La perfusion se terminera dans environ 3 heures.

---

## Exercice 6 : Volume restant à l'instant T

**Situation clinique :**
Une perfusion de Ringer Lactate 500 mL a débuté à 8h00 avec un débit de 100 mL/h.

**Question :** Combien de mL reste-t-il dans la poche à 10h30 ?

> [!success]- Correction
> **Données :**
> - Volume initial : 500 mL
> - Débit : 100 mL/h
> - Temps écoulé : de 8h00 à 10h30 = **2h30 = 2,5h**
>
> **Calcul :**
> Volume écoulé = 100 × 2,5 = 250 mL
> Volume restant = 500 − 250 = **250 mL**
>
> **Vérification :** la moitié de la poche est passée en 2h30. ✓

---

## Exercice 7 : Conversion mL/h → gtt/min (macrogouttes)

**Situation clinique :**
Le médecin prescrit une perfusion à 125 mL/h. Vous n'avez pas de pompe disponible et utilisez une tubulure macrogouttes (20 gtt/mL).

**Question :** À combien de gouttes par minute devez-vous régler la perfusion ?

> [!success]- Correction
> **Méthode :** convertir le débit de mL/h en gtt/min
>
> **Débit en mL/min** = 125 mL/h ÷ 60 = 2,083 mL/min
>
> **Débit en gtt/min** = 2,083 × 20 = **41,7 ≈ 42 gtt/min**
>
> **Raccourci :** Pour les macrogouttes, Débit (gtt/min) ≈ Débit (mL/h) / 3
> 125 / 3 = 41,7 ✓

---

## Exercice 8 : Microgouttes pédiatriques

**Situation clinique :**
Antoine, 4 ans, hospitalisé pour gastro-entérite. Le médecin prescrit une perfusion de réhydratation avec une tubulure microgouttes (60 gtt/mL).

**Prescription :** Glucosé 5% + NaCl 0,9% 100 mL à passer en 4h

**Question :** Quel débit en gouttes/min ?

> [!success]- Correction
> **Données :**
> - Volume : 100 mL
> - Durée : 4h = 240 min
> - Facteur chute : 60 gtt/mL (microgouttes)
>
> **Calcul :**
> Débit = (100 × 60) / 240 = 6 000 / 240 = **25 gtt/min**
>
> **Vérification :** débit faible cohérent pour un enfant de 4 ans. ✓
> Note : avec microgouttes, 1 gtt/min ≈ 1 mL/h, donc 25 gtt/min ≈ 25 mL/h.

---

## Exercice 9 : PIÈGE : durée en minutes à convertir

**Situation clinique :**
Prescription pour M. Garcia, 61 ans : vancomycine 1g IV dans 250 mL de NaCl 0,9%, à passer en 90 minutes.

**Question :** Quel débit programmer en mL/h ?

> [!warning] Point piège
> La durée est donnée en **minutes** → penser à convertir en heures !

> [!success]- Correction
> **Données :**
> - Volume : 250 mL
> - Durée : 90 min = **1,5 h** (= 90/60)
>
> **Calcul :**
> Débit = 250 / 1,5 = **166,7 mL/h ≈ 167 mL/h**
>
> **Vérification :** 167 mL/h × 1,5 h = 250,5 mL ≈ 250 mL ✓
> La vancomycine doit toujours passer lentement (min 60 min) pour éviter le "red man syndrome". ✓

---

## Exercice 10 : PIÈGE : unités différentes (g vs mg)

**Situation clinique :**
Prescription : Métronidazole (Flagyl®) 500 mg IV dans 100 mL, à passer en 20 min.
Le flacon indique : Métronidazole 0,5 g / 100 mL.

**Question :** La prescription et le flacon correspondent-ils ? Quel débit programmer ?

> [!warning] Point piège
> 0,5 g = 500 mg → vérifier les équivalences avant tout calcul !

> [!success]- Correction
> **Vérification de concordance :**
> Prescription : 500 mg = **0,5 g**
> Flacon : 0,5 g / 100 mL ✓ → **le flacon correspond**, administrer les 100 mL complets.
>
> **Débit :**
> - Volume : 100 mL
> - Durée : 20 min = 0,333 h
>
> Débit = 100 / 0,333 = **300 mL/h**
>
> **Vérification :** 300 × 0,333 = 100 mL ✓

---

## Exercice 11 : Débit avec changement de poche

**Situation clinique :**
Mme Petit, 67 ans, en postopératoire. Elle reçoit une perfusion de NaCl 0,9% 1 000 mL à 125 mL/h depuis 7h00.

**Question :** À quelle heure devrez-vous changer la poche ?

> [!success]- Correction
> **Données :**
> - Volume : 1 000 mL
> - Débit : 125 mL/h
> - Heure de début : 7h00
>
> **Calcul de la durée :**
> Durée = 1 000 / 125 = **8 heures**
>
> **Heure de fin :**
> 7h00 + 8h = **15h00**
>
> **Vérification :** 125 mL/h × 8h = 1 000 mL ✓ → Prévoir le changement à 15h00.

---

## Exercice 12 : Synthèse : calcul complet avec dilution et débit

**Situation clinique :**
M. Rousseau, 52 ans, sepsis à E. coli. Prescription : pipéracilline-tazobactam (Tazocilline®) 4g IV, à diluer dans 100 mL de NaCl 0,9%, à passer en 30 min. Vous avez un flacon de poudre de 4g à reconstituer.

**Questions :**
1. Avec quelle quantité de solvant reconstituer le flacon pour obtenir une concentration de 200 mg/mL ?
2. Quel débit programmer en mL/h pour la perfusion ?

> [!success]- Correction
> **Question 1 → Reconstitution :**
> - Dose : 4 g = 4 000 mg
> - Concentration souhaitée : 200 mg/mL
>
> Volume de solvant = 4 000 / 200 = **20 mL**
>
> (En pratique, le flacon de Tazocilline 4g est reconstitué avec 20 mL d'eau PPI selon la notice ✓)
>
> **Question 2 → Débit de perfusion :**
> - Volume total : 100 mL (NaCl) + 20 mL (médicament reconstitué) = 120 mL
> - Durée : 30 min = 0,5 h
>
> Débit = 120 / 0,5 = **240 mL/h**
>
> **Vérification :** 240 × 0,5 = 120 mL ✓

---