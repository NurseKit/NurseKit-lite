---
{"dg-publish":true,"permalink":"/Calculs Doses/Formules Référence/","tags":["calculs-doses","ue-4-4","formules"],"dg-note-properties":{"nom":"Calculs de doses - Formules de référence","type":"Aide-mémoire","tags":["calculs-doses","ue-4-4","formules"],"revision":"2026-06-14"}}
---


> [!tip] Conseil d'utilisation
> Mémorise ces formules AVANT de faire les exercices. Reviens ici si tu bloques. L'objectif est de les appliquer sans réfléchir à l'examen.

---

## 1. Débit de perfusion

### En mL/h (pompe à perfusion / PSE)

**Débit (mL/h) = Volume (mL) / Durée (h)**

> [!example] Exemple rapide
> 500 mL en 4h → 500 / 4 = **125 mL/h**

---

### En gouttes/min (perfusion par gravité)

**Débit (gtt/min) = (Volume (mL) × Facteur chute) / Durée (min)**

| Type de tubulure | Facteur chute |
|---|---|
| Macrogouttes (adulte) | **20 gtt/mL** |
| Microgouttes (pédiatrie) | **60 gtt/mL** |

> [!example] Exemple rapide
> 250 mL en 2h (120 min), macrogouttes → (250 × 20) / 120 = 5000 / 120 = **41,7 ≈ 42 gtt/min**

---

### Durée d'une perfusion

**Durée (h) = Volume (mL) / Débit (mL/h)**

---

### Volume restant à un instant T

**Volume restant (mL) = Volume total − (Débit × Temps écoulé)**

---

## 2. Dose à administrer : Volume à prélever

**Volume à prélever (mL) = Dose prescrite (mg) / Concentration du flacon (mg/mL)**

> [!example] Exemple rapide
> Prescription : 250 mg. Flacon : 500 mg/5 mL → concentration = 100 mg/mL
> Volume = 250 / 100 = **2,5 mL**

---

## 3. Dilution : Formule C1V1 = C2V2

**C1 × V1 = C2 × V2**

| Variable | Signification |
|---|---|
| C1 | Concentration initiale (mg/mL) |
| V1 | Volume à prélever (mL) |
| C2 | Concentration finale souhaitée (mg/mL) |
| V2 | Volume final de la solution (mL) |

> [!example] Exemple rapide
> Préparer 50 mL à 2 mg/mL depuis un flacon à 10 mg/mL
> V1 = (C2 × V2) / C1 = (2 × 50) / 10 = **10 mL** à prélever + 40 mL de solvant

---

## 4. Dose pédiatrique

**Dose totale (mg) = Dose (mg/kg) × Poids (kg)**

**Dose journalière = Dose (mg/kg/j) × Poids (kg)**

**Dose par prise = Dose journalière / Nombre de prises**

### Estimation du poids si non connu (enfant 1-12 ans)

**Poids estimé (kg) = (2 × Âge en années) + 8**

> [!warning] Attention
> Cette formule est une estimation. Toujours peser l'enfant si possible.

### Doses pédiatriques usuelles à connaître

| Médicament | Dose |
|---|---|
| Paracétamol | 15 mg/kg/prise → max 60 mg/kg/j → toutes les 6h |
| Ibuprofène | 10 mg/kg/prise → max 30 mg/kg/j → toutes les 8h |
| Amoxicilline | 50 mg/kg/j en 3 prises (soit ~16,7 mg/kg/prise) |

---

## 5. Seringue électrique (SE / PSE)

### Concentration dans la seringue

**Concentration (mg/mL) = Quantité de médicament (mg) / Volume total de la seringue (mL)**

### Débit de la seringue électrique

**Débit SE (mL/h) = Dose prescrite (mg/h) / Concentration (mg/mL)**

### Dose en mcg/kg/min → mL/h (catécholamines)

**Débit (mL/h) = [Dose (mcg/kg/min) × Poids (kg) × 60] / Concentration (mcg/mL)**

> [!example] Exemple rapide
> Dobutamine 5 mcg/kg/min, patient 70 kg, SE préparée à 2 mg/mL (= 2000 mcg/mL)
> Débit = (5 × 70 × 60) / 2000 = 21 000 / 2000 = **10,5 mL/h**

---

## 6. Reconstitution de poudre

**Volume de solvant à ajouter (mL) = Quantité de poudre (mg) / Concentration souhaitée (mg/mL)**

> [!warning] Tenir compte du volume résiduel de la poudre
> Certains flacons précisent un volume de reconstitution spécifique dans la notice → toujours vérifier.

---

## 7. Règle des 3 vérifications (obligatoire)

> [!important] À appliquer SYSTÉMATIQUEMENT
> 1. **Avant de préparer** : vérifier la prescription (médicament, dose, voie, patient)
> 2. **En préparant** : vérifier étiquette + calcul + péremption
> 3. **Avant d'administrer** : vérifier identité patient (bracelet) + voie d'administration

---

## 8. Conversions à connaître

| Équivalence | Valeur |
|---|---|
| 1 g | = 1 000 mg |
| 1 mg | = 1 000 mcg (µg) |
| 1 L | = 1 000 mL |
| 1 h | = 60 min |
| 1 UI (insuline) | ≠ mg (unité propre) |

---

## 9. Points de sécurité à ne jamais oublier

> [!danger] Médicaments à risque
> - **KCl (Chlorure de potassium)** : JAMAIS en IV direct → toujours dilué dans une perfusion (risque d'arrêt cardiaque)
> - **Insuline** : toujours vérifier le type (rapide, lente) et l'unité (UI ≠ mL)
> - **Morphine, noradrénaline, dobutamine** : médicaments à marge thérapeutique étroite → double vérification obligatoire
> - **Méthotrexate** : erreur de dosage fréquente (hebdomadaire ≠ quotidien)

---
