# 📊 Compte Rendu Technique
# Analyse de Rentabilité sur Produit

<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║          ENCG SETTAT  •  Université Hassan 1er                   ║
║        Module : Contrôle de Gestion & Analyse Financière         ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

---

| Champ | Détail |
|:---|:---|
| 📄 **Document** | Compte Rendu — Analyse de Rentabilité sur Produit |
| ✍️ **Rédigé par** | **Islam HACHEM** |
| 🏛️ **Établissement** | ENCG Settat — Université Hassan 1er |
| 📅 **Date** | 31 mars 2026 |
| 🎓 **Matière** | Contrôle de Gestion / Analyse Financière |
| 🔖 **Version** | 1.0 — Document initial |
| ✅ **Statut** | Finalisé |

---

## 📋 Table des Matières

- [1. Introduction](#1-introduction)
  - [1.1 Définition et Enjeux](#11-définition-et-enjeux)
  - [1.2 Objectifs de l'Analyse](#12-objectifs-de-lanalyse)
  - [1.3 Périmètre et Hypothèses](#13-périmètre-et-hypothèses)
- [2. Fondements Théoriques](#2-fondements-théoriques)
  - [2.1 Notion de Rentabilité](#21-notion-de-rentabilité)
  - [2.2 Structure des Coûts](#22-structure-des-coûts)
  - [2.3 Méthodes d'Analyse](#23-méthodes-danalyse)
- [3. Indicateurs Clés de Rentabilité](#3-indicateurs-clés-de-rentabilité)
  - [3.1 Marge sur Coût Variable (MCV)](#31-marge-sur-coût-variable-mcv)
  - [3.2 Seuil de Rentabilité](#32-seuil-de-rentabilité)
  - [3.3 Point Mort](#33-point-mort)
  - [3.4 Indice de Sécurité et Levier Opérationnel](#34-indice-de-sécurité-et-levier-opérationnel)
  - [3.5 Marge Nette et ROI Produit](#35-marge-nette-et-roi-produit)
- [4. Méthodes d'Imputation des Coûts](#4-méthodes-dimputation-des-coûts)
  - [4.1 Méthode des Coûts Complets](#41-méthode-des-coûts-complets)
  - [4.2 Méthode des Coûts Variables (Direct Costing)](#42-méthode-des-coûts-variables-direct-costing)
  - [4.3 Méthode ABC (Activity-Based Costing)](#43-méthode-abc-activity-based-costing)
  - [4.4 Comparaison des Méthodes](#44-comparaison-des-méthodes)
- [5. Application Pratique — Cas Chiffré](#5-application-pratique--cas-chiffré)
  - [5.1 Données du Cas](#51-données-du-cas)
  - [5.2 Calcul des Marges](#52-calcul-des-marges)
  - [5.3 Détermination du Seuil de Rentabilité](#53-détermination-du-seuil-de-rentabilité)
  - [5.4 Tableau de Bord de Rentabilité](#54-tableau-de-bord-de-rentabilité)
- [6. Analyse Multi-Produits](#6-analyse-multi-produits)
  - [6.1 Problématique de l'Affectation des Charges Fixes](#61-problématique-de-laffectation-des-charges-fixes)
  - [6.2 Hiérarchisation des Produits](#62-hiérarchisation-des-produits)
  - [6.3 Décisions Stratégiques](#63-décisions-stratégiques)
- [7. Limites et Précautions](#7-limites-et-précautions)
- [8. Synthèse et Recommandations](#8-synthèse-et-recommandations)

---

## 1. Introduction

### 1.1 Définition et Enjeux

L'**analyse de rentabilité sur produit** est une démarche fondamentale du contrôle de gestion. Elle consiste à mesurer la capacité d'un produit (ou d'une ligne de produits) à générer un **bénéfice suffisant** pour couvrir l'ensemble des charges qui lui sont imputées, et à contribuer positivement au résultat global de l'entreprise.

> 💡 **En une phrase :** La rentabilité d'un produit mesure ce qu'il rapporte réellement à l'entreprise, une fois tous ses coûts déduits — directs et indirects.

Cette analyse est au cœur des **décisions stratégiques** de l'entreprise :

- Faut-il **maintenir, développer ou abandonner** un produit ?
- Quel **prix de vente** fixer pour atteindre la rentabilité cible ?
- Quelle **quantité minimale** doit-on vendre pour ne pas perdre d'argent ?
- Comment **répartir les ressources** entre plusieurs produits ?

---

### 1.2 Objectifs de l'Analyse

| # | Objectif | Question à laquelle on répond |
|:---:|:---|:---|
| 1 | Évaluer la profitabilité unitaire | *Ce produit génère-t-il une marge positive ?* |
| 2 | Identifier le seuil de rentabilité | *À partir de combien d'unités vendues sommes-nous rentables ?* |
| 3 | Mesurer la contribution au résultat global | *Ce produit couvre-t-il sa quote-part de charges fixes ?* |
| 4 | Comparer la rentabilité entre produits | *Quel est notre produit le plus rentable ?* |
| 5 | Orienter les décisions de mix produit | *Sur quel produit doit-on concentrer nos efforts commerciaux ?* |
| 6 | Simuler des scénarios | *Que se passe-t-il si le prix de vente baisse de 10 % ?* |

---

### 1.3 Périmètre et Hypothèses

Pour mener une analyse rigoureuse, plusieurs **hypothèses simplificatrices** sont posées :

- Les coûts variables sont **proportionnels** au volume de production/vente
- Les coûts fixes sont **constants** sur la période d'analyse (pas de saut de charges)
- Le prix de vente est **stable** sur la période considérée
- La production est **totalement écoulée** (pas de variation de stock significative)
- Les coûts indirects sont **répartis** selon une clé d'allocation cohérente et stable

> ⚠️ **Attention :** Ces hypothèses ne sont valables que dans une **fourchette de volume** donnée. Au-delà, des sauts de charges fixes ou des effets de seuil peuvent modifier radicalement les conclusions.

---

## 2. Fondements Théoriques

### 2.1 Notion de Rentabilité

La **rentabilité** est le rapport entre un résultat obtenu et les moyens mis en œuvre pour l'obtenir. Dans le cadre de l'analyse produit, on distingue plusieurs niveaux :

```
CHIFFRE D'AFFAIRES (CA)
       │
       ▼
  – Coûts variables de production
       │
       ▼
  MARGE SUR COÛT VARIABLE (MCV)
       │
       ▼
  – Coûts fixes directs du produit
       │
       ▼
  MARGE SUR COÛT SPÉCIFIQUE
       │
       ▼
  – Quote-part de charges fixes communes
       │
       ▼
  RÉSULTAT NET DU PRODUIT
```

Chaque niveau correspond à une **décision différente** :
- La **MCV** guide les décisions à court terme (production, vente)
- La **Marge sur coût spécifique** guide les décisions à moyen terme (abandon de produit)
- Le **Résultat net** reflète la rentabilité globale réelle du produit

---

### 2.2 Structure des Coûts

#### Coûts Variables (CV)

Les coûts variables **fluctuent proportionnellement** au volume d'activité :

| Catégorie | Exemples |
|:---|:---|
| Matières premières | Matières incorporées dans le produit |
| Main-d'œuvre directe | Heures de production directement affectées |
| Énergie de production | Électricité, gaz consommés par unité |
| Emballages | Coûts d'emballage par unité produite |
| Commissions commerciales | Pourcentage sur CA vendeur |
| Transport | Coût de livraison par unité |

#### Coûts Fixes (CF)

Les coûts fixes **restent constants** indépendamment du volume, dans une plage d'activité donnée :

| Catégorie | Exemples |
|:---|:---|
| Amortissements | Machines, équipements, brevets |
| Loyers | Ateliers, entrepôts, bureaux |
| Salaires fixes | Encadrement, administration |
| Assurances | Primes d'assurance annuelles |
| Frais de publicité | Campagnes nationales ou institutionnelles |
| R&D | Frais de développement du produit |

#### Distinction Coûts Directs / Indirects

```
┌─────────────────────────────────────────────────────────────────┐
│                    CLASSIFICATION DES COÛTS                      │
├──────────────────────────┬──────────────────────────────────────┤
│     COÛTS DIRECTS        │          COÛTS INDIRECTS             │
│ Affectés sans ambiguïté  │  Nécessitent une clé de répartition  │
│ au produit concerné      │  (par ex. m², h-machine, CA…)        │
├──────────────────────────┼──────────────────────────────────────┤
│ • Matières premières     │ • Loyer de l'usine                   │
│ • MOD spécifique         │ • Direction générale                 │
│ • Amortissement machine  │ • Service comptabilité               │
│   dédiée au produit      │ • Frais informatiques                │
└──────────────────────────┴──────────────────────────────────────┘
```

---

### 2.3 Méthodes d'Analyse

Trois grandes méthodes structurent l'analyse de rentabilité sur produit :

| Méthode | Logique | Usage privilégié |
|:---|:---|:---|
| **Coûts complets** | Imputer **tous** les coûts (variables + fixes) au produit | Calcul du prix de revient complet, pricing |
| **Direct costing** | N'imputer que les **coûts variables** ; les CF sont traités globalement | Décisions à court terme, seuil de rentabilité |
| **ABC** | Imputer les coûts via les **activités** consommées | Analyse fine de la profitabilité par segment |

---

## 3. Indicateurs Clés de Rentabilité

### 3.1 Marge sur Coût Variable (MCV)

La MCV est l'indicateur central de l'analyse en **coûts variables**. Elle mesure ce que chaque unité vendue contribue à couvrir les charges fixes.

```
┌─────────────────────────────────────────────────────────────────┐
│                  FORMULES — MARGE SUR COÛT VARIABLE             │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  MCV unitaire  =  Prix de vente unitaire  –  Coût variable unit.│
│                                                                  │
│  MCV totale    =  Chiffre d'affaires  –  Coûts variables totaux  │
│                                                                  │
│  Taux de MCV   =  (MCV unitaire / Prix de vente unitaire) × 100 │
│                =  (MCV totale / CA) × 100                        │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

**Interprétation du Taux de MCV :**

| Taux de MCV | Interprétation |
|:---:|:---|
| > 60 % | Excellent — produit à forte valeur ajoutée |
| 40 – 60 % | Bon — structure de coûts équilibrée |
| 20 – 40 % | Correct — surveiller l'évolution des coûts variables |
| < 20 % | Faible — rentabilité très sensible aux variations de prix ou de volume |

---

### 3.2 Seuil de Rentabilité

Le **seuil de rentabilité** (ou point mort) est le niveau de chiffre d'affaires (ou de volume) à partir duquel l'entreprise couvre la totalité de ses charges et commence à dégager un bénéfice.

```
┌─────────────────────────────────────────────────────────────────┐
│                 FORMULES — SEUIL DE RENTABILITÉ                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  SR (en valeur)  =  Charges Fixes  /  Taux de MCV               │
│                                                                  │
│  SR (en volume)  =  Charges Fixes  /  MCV unitaire              │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

**Représentation graphique :**

```
Résultat (MAD)
     │
     │                        ╱ Chiffre d'Affaires
     │                      ╱
     │                    ╱      ← ZONE BÉNÉFICE
     │                  ╱
─────┼────────────────●────────────────── Volume
     │              ╱ │
     │            ╱   │
     │          ╱     │
     │        ╱ ← Coût Total
     │   ZONE │
     │  PERTE │
              SR
```

---

### 3.3 Point Mort

Le **point mort** exprime le seuil de rentabilité en **nombre de jours d'activité** nécessaires pour couvrir les charges fixes.

```
┌─────────────────────────────────────────────────────────────────┐
│                    FORMULE — POINT MORT                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Point mort  =  (SR / CA annuel)  ×  360 jours                  │
│                                                                  │
│  Exemple : SR = 800 000 MAD, CA = 2 000 000 MAD                  │
│  Point mort = (800 000 / 2 000 000) × 360 = 144 jours           │
│  → L'entreprise est rentable à partir du 144ème jour de l'année  │
│    soit approximativement le 24 mai                              │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

### 3.4 Indice de Sécurité et Levier Opérationnel

#### Marge de Sécurité (MS)

La marge de sécurité mesure de combien le CA réel peut **baisser** avant d'atteindre le seuil de rentabilité.

```
MS (en valeur)   =  CA réel  –  Seuil de rentabilité
MS (en %)        =  MS / CA réel  ×  100
Indice de sécu.  =  CA réel / Seuil de rentabilité
```

#### Levier Opérationnel (LO)

Le levier opérationnel mesure la **sensibilité du résultat** aux variations du CA.

```
┌─────────────────────────────────────────────────────────────────┐
│                  FORMULE — LEVIER OPÉRATIONNEL                   │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  LO  =  MCV totale / Résultat net                               │
│                                                                  │
│  Interprétation : Si LO = 4, alors une hausse de 10 % du CA     │
│  entraîne une hausse de 40 % du résultat net                    │
│  (et inversement en cas de baisse)                              │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

> ⚠️ Un **levier élevé** signifie une forte sensibilité aux variations d'activité — risque d'exploitation important, mais fort potentiel de croissance du résultat.

---

### 3.5 Marge Nette et ROI Produit

| Indicateur | Formule | Interprétation |
|:---|:---|:---|
| **Marge brute** | CA – Coût de production | Rentabilité industrielle du produit |
| **Marge commerciale** | CA – Coût d'achat des marchandises | Pour les activités de négoce |
| **Marge nette** | Résultat net / CA × 100 | Rentabilité globale après tous les coûts |
| **ROI Produit** | Résultat net / Investissement × 100 | Retour sur l'investissement produit |
| **Délai de récupération** | Investissement / Cash-flow annuel | Temps pour récupérer l'investissement |

---

## 4. Méthodes d'Imputation des Coûts

### 4.1 Méthode des Coûts Complets

#### Principe

Tous les coûts — **variables et fixes, directs et indirects** — sont imputés au produit. Les coûts indirects sont ventilés via un **tableau de répartition** par centres d'analyse (centres de coûts).

#### Structure du Tableau de Répartition

```
┌──────────────────┬──────────────┬──────────────┬──────────────┬──────────────┐
│  CHARGES         │ Centre Admin │ Centre Appro │ Centre Prod  │ Centre Distri│
├──────────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│ Charges primaires│    Xxxxx     │    Xxxxx     │    Xxxxx     │    Xxxxx     │
│ (directes)       │              │              │              │              │
├──────────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│ Prestations      │              │              │              │              │
│ réciproques      │   (Xxxxx)    │   + Xxxxx    │   + Xxxxx    │   + Xxxxx    │
├──────────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│ TOTAUX           │      0       │    Xxxxx     │    Xxxxx     │    Xxxxx     │
├──────────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│ Unités d'œuvre   │      —       │  Kg achetés  │  H-machine   │  CA livré    │
├──────────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│ Coût UO          │      —       │   X MAD/kg   │  X MAD/h-m   │  X % du CA   │
└──────────────────┴──────────────┴──────────────┴──────────────┴──────────────┘
```

#### Calcul du Coût de Revient Complet

```
Coût de revient complet
= Coût matières premières
+ Coût MOD
+ Charges de l'atelier de production (via UO)
+ Charges du centre Approvisionnement (via UO)
+ Charges du centre Distribution (via UO)
─────────────────────────────────────────────
= Coût de revient unitaire complet
```

---

### 4.2 Méthode des Coûts Variables (Direct Costing)

#### Principe

Seuls les **coûts variables** sont affectés aux produits. Les **charges fixes** sont traitées globalement et déduites de la somme des marges sur coûts variables.

#### Compte de Résultat Différentiel

```
┌──────────────────────────────────────────────────────────────────┐
│              COMPTE DE RÉSULTAT EN DIRECT COSTING                │
├──────────────────────────────────────────────────────────────────┤
│  Chiffre d'Affaires                              CA              │
│  – Coûts Variables                              (CV)             │
│                                          ─────────────           │
│  = MARGE SUR COÛT VARIABLE                      MCV              │
│  – Charges Fixes (totales)                       (CF)            │
│                                          ─────────────           │
│  = RÉSULTAT NET                                   R              │
└──────────────────────────────────────────────────────────────────┘
```

#### Avantages du Direct Costing

- ✅ Simplifie la prise de décision à court terme
- ✅ Élimine les biais liés à l'affectation arbitraire des charges fixes
- ✅ Met en évidence la contribution de chaque produit
- ✅ Facilite le calcul du seuil de rentabilité

---

### 4.3 Méthode ABC (Activity-Based Costing)

#### Principe

La méthode ABC (Comptabilité par Activités) affecte les coûts indirects aux produits via les **activités** qu'ils consomment, plutôt que par des clés de répartition forfaitaires.

```
Ressources (charges indirectes)
        │
        ▼ (inducteurs de ressources)
   ACTIVITÉS
   ┌──────────────┬──────────────┬──────────────┐
   │ Planification│  Contrôle    │  Livraison   │
   │ production   │  qualité     │  client      │
   └──────┬───────┴──────┬───────┴──────┬───────┘
          │               │              │
          ▼               ▼              ▼
     (inducteurs d'activité : nb OF, nb contrôles, nb livraisons)
          │               │              │
          └───────────────┴──────────────┘
                          │
                          ▼
                    PRODUITS / CLIENTS
```

#### Comparaison avec les méthodes traditionnelles

| Aspect | Coûts Complets | Direct Costing | ABC |
|:---|:---:|:---:|:---:|
| Précision d'imputation | Moyenne | Faible (CF globales) | Élevée |
| Complexité de mise en œuvre | Moyenne | Faible | Élevée |
| Pertinence pour le pricing | Bonne | Partielle | Excellente |
| Décisions court terme | Correcte | Excellente | Bonne |
| Identification des activités non rentables | Non | Non | **Oui** |

---

### 4.4 Comparaison des Méthodes

| Critère | Coûts Complets | Direct Costing | ABC |
|:---|:---|:---|:---|
| **Objectif** | Prix de revient total | Contribution, seuil SR | Coût réel par activité |
| **Charges fixes** | Réparties par clé | Traitées globalement | Via inducteurs d'activité |
| **Avantage principal** | Vision complète | Simplicité | Précision maximale |
| **Inconvénient principal** | Subjectivité de la clé | Ignore les CF produit | Coûteux à implémenter |
| **Contexte d'usage** | Pricing long terme | Décisions court terme | Optimisation des processus |

---

## 5. Application Pratique — Cas Chiffré

### 5.1 Données du Cas

> **Contexte :** Une entreprise commercialise trois produits : **Alpha**, **Bêta** et **Gamma**. Les données de l'exercice N sont les suivantes.

#### Données de Production et de Vente

| Élément | Produit Alpha | Produit Bêta | Produit Gamma |
|:---|:---:|:---:|:---:|
| Volume vendu (unités) | 5 000 | 3 000 | 8 000 |
| Prix de vente unitaire | 200 MAD | 350 MAD | 120 MAD |
| **CA total** | **1 000 000 MAD** | **1 050 000 MAD** | **960 000 MAD** |

#### Structure des Coûts Variables Unitaires

| Élément | Alpha | Bêta | Gamma |
|:---|:---:|:---:|:---:|
| Matières premières | 60 MAD | 110 MAD | 40 MAD |
| Main-d'œuvre directe | 40 MAD | 70 MAD | 25 MAD |
| Frais variables de fabrication | 20 MAD | 30 MAD | 15 MAD |
| Frais variables de distribution | 10 MAD | 15 MAD | 8 MAD |
| **Total CV unitaire** | **130 MAD** | **225 MAD** | **88 MAD** |

#### Charges Fixes (globales)

| Nature | Montant |
|:---|:---:|
| Amortissements | 180 000 MAD |
| Loyers et charges locatives | 120 000 MAD |
| Salaires fixes (encadrement) | 250 000 MAD |
| Frais généraux fixes | 90 000 MAD |
| **Total Charges Fixes** | **640 000 MAD** |

---

### 5.2 Calcul des Marges

#### Marge sur Coût Variable

| Indicateur | Alpha | Bêta | Gamma |
|:---|:---:|:---:|:---:|
| Prix de vente unitaire | 200 MAD | 350 MAD | 120 MAD |
| Coût variable unitaire | 130 MAD | 225 MAD | 88 MAD |
| **MCV unitaire** | **70 MAD** | **125 MAD** | **32 MAD** |
| Volume vendu | 5 000 u. | 3 000 u. | 8 000 u. |
| **MCV totale** | **350 000 MAD** | **375 000 MAD** | **256 000 MAD** |
| **Taux de MCV** | **35 %** | **35,7 %** | **26,7 %** |

#### Résultat Global

```
MCV totale consolidée  =  350 000 + 375 000 + 256 000  =  981 000 MAD
Charges fixes totales  =                                   640 000 MAD
                                                       ─────────────
RÉSULTAT NET           =                                   341 000 MAD
```

---

### 5.3 Détermination du Seuil de Rentabilité

**Taux de MCV global pondéré :**

```
CA total  =  1 000 000 + 1 050 000 + 960 000  =  3 010 000 MAD
Taux MCV  =  981 000 / 3 010 000              =  32,59 %
```

**Seuil de Rentabilité global :**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                  │
│  SR (en valeur)  =  640 000 / 0,3259  =  1 963 792 MAD         │
│                                                                  │
│  Point mort      =  (1 963 792 / 3 010 000) × 360              │
│                  =  234,7 jours                                  │
│                  ≈  23 août de l'exercice                        │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

### 5.4 Tableau de Bord de Rentabilité

| Indicateur | Alpha | Bêta | Gamma | **Global** |
|:---|:---:|:---:|:---:|:---:|
| CA | 1 000 000 | 1 050 000 | 960 000 | **3 010 000** |
| CV totaux | 650 000 | 675 000 | 704 000 | **2 029 000** |
| MCV | 350 000 | 375 000 | 256 000 | **981 000** |
| Taux de MCV | 35,0 % | 35,7 % | 26,7 % | **32,6 %** |
| Quote-part CF* | 212 624 | 222 990 | 204 386 | **640 000** |
| Résultat produit | 137 376 | 152 010 | 51 614 | **341 000** |
| Marge nette | 13,7 % | 14,5 % | 5,4 % | **11,3 %** |

*Quote-part CF répartie proportionnellement au CA*

> 🏆 **Classement de rentabilité :** Bêta (14,5 %) > Alpha (13,7 %) > Gamma (5,4 %)

---

## 6. Analyse Multi-Produits

### 6.1 Problématique de l'Affectation des Charges Fixes

Dans un contexte multi-produits, la répartition des charges fixes est **la principale source de biais** dans l'analyse de rentabilité. Plusieurs clés d'allocation sont possibles :

| Clé d'allocation | Avantage | Inconvénient |
|:---|:---|:---|
| Proportionnelle au CA | Simple, intuitive | Avantage les produits à fort CA |
| Proportionnelle au volume | Simple | Ignore la valeur unitaire |
| Proportionnelle aux heures-machines | Reflète la consommation productive | Nécessite un suivi précis |
| Proportionnelle aux coûts directs | Cohérente avec les coûts réels | Peut pénaliser les produits intensifs |
| Méthode ABC | La plus précise | La plus complexe |

> ⚠️ **Règle d'or :** Une charge fixe **commune** à plusieurs produits ne doit **jamais** conduire à l'abandon d'un produit ayant une **MCV positive**, car sa disparition reporterait ses charges fixes sur les autres produits.

---

### 6.2 Hiérarchisation des Produits

La hiérarchisation des produits doit combiner **plusieurs critères** pour être pertinente :

```
┌──────────────────────────────────────────────────────────────────┐
│              MATRICE DE DÉCISION PRODUIT                          │
├──────────────────────────┬───────────────────────────────────────┤
│  CRITÈRE                 │  Alpha    │  Bêta     │  Gamma        │
├──────────────────────────┼───────────┼───────────┼───────────────┤
│  Taux de MCV             │  35,0 %   │  35,7 %   │  26,7 %       │
│  MCV totale              │  350 000  │  375 000  │  256 000      │
│  Marge nette             │  13,7 %   │  14,5 %   │   5,4 %       │
│  Volume (potentiel croiss│  Moyen    │  Faible   │  Élevé        │
│  Positionnement marché   │  Mature   │  Premium  │  Entrée gamme │
├──────────────────────────┼───────────┼───────────┼───────────────┤
│  DÉCISION                │ Maintenir │ Développer│ Optimiser     │
└──────────────────────────┴───────────┴───────────┴───────────────┘
```

---

### 6.3 Décisions Stratégiques

#### Cas 1 — Abandon d'un produit

> Un produit ne doit être abandonné que si sa **MCV est négative**, c'est-à-dire s'il génère moins de recettes que ses coûts variables. Si sa MCV est positive mais insuffisante, la priorité est de l'**optimiser**, pas de l'abandonner.

#### Cas 2 — Produit contraignant (goulot d'étranglement)

En cas de ressource limitante (heures-machines, matières premières rares), la décision de production doit être basée sur la **MCV par unité de ressource contrainte** :

```
Critère de priorité  =  MCV unitaire / Consommation de la ressource contrainte
```

Le produit ayant la MCV par unité de ressource la **plus élevée** est produit en priorité.

#### Cas 3 — Réduction de prix

L'impact d'une réduction de prix sur le résultat se calcule ainsi :

```
Variation du résultat
= (Nouveau prix – Ancien prix) × Volume initial
+ (Nouveau volume – Ancien volume) × MCV unitaire nouveau
```

---

## 7. Limites et Précautions

| Limite | Description | Précaution à prendre |
|:---|:---|:---|
| **Hypothèse de linéarité** | CV proportionnels au volume — rarement vrai à grande échelle | Vérifier la validité dans la plage d'activité concernée |
| **Charges fixes « fixes »** | Les CF peuvent sauter par paliers (ex: nouvel équipement) | Identifier les seuils de capacité et les sauts de charges |
| **Clés de répartition arbitraires** | L'affectation des coûts indirects influence les résultats | Utiliser des clés économiquement justifiées, recourir à l'ABC si possible |
| **Horizon temporel** | Le direct costing est inadapté aux décisions long terme | Compléter par une analyse en coûts complets pour le pricing |
| **Évolution des prix** | Le prix de vente est supposé constant | Réaliser des analyses de sensibilité pour différents scénarios de prix |
| **Corrélation entre produits** | Les produits d'une gamme s'influencent mutuellement (cannibalisme, effet d'image) | Prendre en compte les effets croisés dans la décision de mix produit |

---

## 8. Synthèse et Recommandations

### Ce qu'il faut retenir

```
┌─────────────────────────────────────────────────────────────────┐
│                    SYNTHÈSE CONCEPTUELLE                         │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ① MCV > 0   → Le produit contribue à couvrir les CF           │
│    MCV < 0   → Abandon immédiat ou restructuration profonde      │
│                                                                  │
│  ② SR        → Niveau de CA minimum pour être rentable          │
│    PM        → Date à partir de laquelle l'entreprise gagne      │
│                                                                  │
│  ③ MS > 0    → Marge de manœuvre avant la zone de perte         │
│    LO élevé  → Sensibilité forte aux variations d'activité       │
│                                                                  │
│  ④ Méthode à choisir selon l'objectif :                         │
│    Court terme  → Direct Costing                                 │
│    Long terme   → Coûts Complets                                 │
│    Précision    → ABC                                            │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

### Recommandations Pratiques

| Priorité | Recommandation |
|:---:|:---|
| 🔴 **1** | Calculer systématiquement la MCV avant toute décision d'abandon de produit |
| 🔴 **2** | Ne jamais confondre produit peu rentable et produit à MCV négative |
| 🟠 **3** | Vérifier la robustesse du SR avec des analyses de sensibilité (±10 % prix, ±15 % volume) |
| 🟠 **4** | Réviser les clés de répartition des CF au moins une fois par exercice |
| 🟡 **5** | Implémenter l'ABC pour les produits représentant plus de 20 % du CA |
| 🟡 **6** | Compléter l'analyse de rentabilité par une analyse du cycle de vie produit (CVP) |
| 🟢 **7** | Mettre en place un tableau de bord mensuel de suivi des MCV par produit |

---

<div align="right">

---

*Rédigé par **Islam HACHEM***
*ENCG Settat — Université Hassan 1er*
*31 mars 2026*

</div>
