# 🎓 **GUIDE FORMATEUR – Atelier Bubble (14h)**

**Projet fil rouge** : Application de benchmark des offres de formation informatique.

---

# ✅ **0. Préparation formateur (avant le cours)**

### ✅ Créer ton propre environnement Bubble

👉 [https://bubble.io](https://bubble.io)
Créer un projet “Benchmark Demo”.

### ✅ Vérifier le matériel

* Apprenants sur Chrome / Edge (éviter Safari)
* Connexion stable
* Casque micro si travail en distanciel

### ✅ Ressources à préparer

* Une fiche “exemple de formation” (pour tester le formulaire)
* Une clé API OpenAI (ou alternative)
* Un fichier Excel avec des fomations (pour tests filtres)

---

# ✅ **1. Objectifs pédagogiques globaux**

À la fin des 14h, l’apprenant doit savoir :

✅ concevoir une base de données

✅ créer des pages & UI professionnelles

✅ créer des workflows

✅ intégrer une API

✅ filtrer et trier des données

✅ publier une application Bubble

✅ réaliser un benchmark de formations

---

# ✅ **PARTIE I — Découverte & UI (4h)**

---

# **🟦 Séquence 1 – Introduction Low-Code (1h)**

### 🎯 Objectifs

* Comprendre l’intérêt du no-code/low-code

Le no-code / low-code sert à :
➜ Construire plus vite
➜ Moins cher
➜ En impliquant plus de monde
➜ Tout en gardant la possibilité d’évoluer ensuite

Par contre
❌ Dépendance à la plateforme

❌ Liberté technique limitée

❌ Ralentissements / limitations avec la complexité

❌ Coût qui peut augmenter avec les utilisateurs

❌ Intégrations parfois difficiles

❌ Maintenance visuelle complexe

❌ Demande tout de même des compétences


* Découvrir Bubble

Je recommande fortement : BUBBLE
Car :
- c’est plus complet que Airtable
- plus simple qu’OutSystems
- entièrement web (contrairement à certaines fonctionnalités PowerApps)
- parfait pour construire une vraie application avec front + logique + API

### 🎤 À dire (exemple)

> “Aujourd’hui, on va développer une application web complète, sans coder, mais en appliquant les concepts fondamentaux du développement logiciel.”

### 📽 Démo à faire

1. Montrer Bubble.io
2. Montrer le dashboard
3. Montrer un exemple d’app Bubble existante (Bubble Showcase)

### ✅ Activité : “Définir un benchmark”

Demander :

> “Quels critères utilisez-vous pour comparer des formations ?”

Noter les idées au tableau pour structurer la base de données ensuite.

**Sortie attendue :** une liste de critères (titre, prix, durée, organisme…)

---

# **🟦 Séquence 2 – Première prise en main (3h)**

## 🎯 Objectifs

* Utiliser l’éditeur (Design, Workflow, Data)
* Créer les premières pages

Bien sûr ! Voici **exactement ce que tu dois faire, dire et faire faire** durant la **Séquence 2 – Première prise en main (3h)**.
Tu peux suivre ça minute par minute : c’est un plan **clé en main** pour ton animation pédagogique.

---

### ✅ **🟦 Séquence 2 – Première prise en main (3h)**

#### 🎯 Objectifs

* Comprendre comment fonctionne l’éditeur Bubble
* Découvrir Design, Workflow, Data
* Créer les 3 pages du projet fil rouge
* Mettre en place la navigation
* Créer la première UI (la carte formation)

---

#### ✅ ✅ ✅ **CE QUE TU DOIS FAIRE EXACTEMENT**

---

#### ✅ **1) Introduction (5 min)**

🎤 À dire :

> “Dans cette séquence, on va découvrir comment fonctionne Bubble et créer les premières pages de notre application.”

Ensuite, ouvre Bubble et montre en live.

---

#### ✅ **2) Présenter l’interface Bubble (20 min)**

🎤 Tu expliques en montrant ton écran :

#### 🔹 À montrer :

✅ `Design` → interface de création visuelle
✅ `Workflow` → automatisations
✅ `Data` → base de données
✅ `Styles` → apparence globale
✅ `Plugins` → API Connector, etc.
✅ `Settings` → versions, SEO, domaine

#### 🎤 Phrase simple :

> “Bubble fonctionne comme un LEGO : Design = visuel, Workflow = actions, Data = stockage.”

---

#### ✅ **3) Démonstration guidée : créer une nouvelle page (10 min)**

Tu leur montres comment faire pour *une* page :

* cliquer *New page*
* choisir un nom simple : `home`

Puis tu leur demandes de répéter pour les 3 pages suivantes.

---

#### ✅ **4) TP Formateur : Création des pages du projet (20 min)**

Tu leur demandes de créer les pages suivantes :

✅ Page 1 : **home**
✅ Page 2 : **ajouter_formation**
✅ Page 3 : **benchmark**
✅ Page 4 : **details_formation** (option pour plus tard)

Une fois les pages créées, tu fais le tour pour vérifier.

---

#### ✅ **5) Créer un en-tête (header) réutilisable (20 min)**

🎤 À dire :

> “On va créer un menu commun à toutes les pages grâce aux éléments réutilisables.”

##### Étapes :

1. Bubble → *New reusable element*
2. Nom : `header`
3. Ajouter :

   * logo ou texte “Benchmark Formations”
   * 3 boutons : *Home*, *Ajouter*, *Benchmark*
4. Ajouter une barre horizontale / petit background

✅ **Très important** : leur montrer comment **insérer ce header dans chaque page**.

---

# ✅ **6) TP : Mise en place de la navigation (20 min)**

📌 Consigne :

* Cliquer sur le bouton *Home* → Workflow → “Navigate to page home”
* Faire pareil pour les boutons Ajouter & Benchmark

✅ Tu dois vérifier que :

* chaque bouton renvoie vers la bonne page
* les workflows sont créés
* les pages affichent le header

---

# ✅ **7) Pause ou micro-exercice (5 min)**

---

# ✅ **8) Démo : Créer une carte “Formation” (20 min)**

🎤 À dire :

> “Nous allons créer la carte visuelle d’une formation, que nous réutiliserons plus tard dans le listing.”

### Sur ta page `benchmark` :

Tu crées :

* un **Group** rectangulaire
* un **titre** (Text)
* un **organisme** (Text)
* un **prix** (Text)
* un **bouton** “Voir détails”

Tu expliques :
✅ utilisation des groupes
✅ nombre minimal d’éléments
✅ importance de l’alignement
✅ aspect reusable de la carte

---

# ✅ **9) TP : Chaque apprenant crée sa carte (25 min)**

📌 Consignes précises :

* Placer un group
* Ajouter 3 champs (text)
* Styliser légèrement
* Ajouter un bouton
* Aligner les éléments
* Centrer le group dans la page

✅ **À vérifier** :

* ne pas utiliser "Group Floating"
* ne pas bloquer le responsive
* nommer les éléments (card_title, card_price, etc.)

---

# ✅ **10) Initiation rapide au responsive (10 min)**

🎤 À dire :

> “Bubble a un moteur responsive : on va apprendre juste les bases.”

Tu montres :

* Comment changer la largeur minimale
* Comment centrer
* Comment tester en mobile

---

# ✅ **11) Mise en commun + questions (15 min)**

Tu réponds aux questions suivantes (les plus fréquentes) :

* “Comment centrer un élément ?”
* “Comment mettre des marges ?”
* “Pourquoi mon bouton se déforme ?”
* “Pourquoi mon groupe cache les textes ?”

---

# ✅ **À la fin des 3h, les apprenants doivent avoir :**

✅ 4 pages : home / ajouter_formation / benchmark / details
✅ Le header réutilisable en place
✅ La navigation fonctionnelle
✅ Une carte formation propre
✅ Les bases de Design, Workflow, Data, Styles

---

# ✅ **Résumé ultra simple pour toi : Ce que tu dois faire dans cette séquence**

| Étape                  | Ce que TU fais (formateur)       |
| ---------------------- | -------------------------------- |
| Présentation interface | 20 min, tu montres chaque onglet |
| Création pages         | Tu fais → ils répètent           |
| Création du header     | Tu montres → ils refont          |
| Navigation             | Tu fais → ils testent            |
| Carte formation        | Démo puis TP                     |
| Responsive             | Mini démo                        |
| Questions              | 10–15 min                        |

---

Si tu veux, je peux aussi te livrer :
✅ un **script mot-à-mot** de ce que tu dois dire
✅ une **checklist de validation par apprenant**
✅ une **fiche formateur** PDF prête à imprimer

Tu veux l’un d’eux ?


---

## ✅ **TP 1 – Créer la structure de l’application (45 min)**

### 📌 Consignes

Créer :

* Page d’accueil
* Menu (header réutilisable)
* Trois pages :

  * Home
  * Ajouter formation
  * Benchmark

### ✅ Astuce formateur

Les apprenants oublient souvent :

* de nommer leurs éléments
* d’utiliser des groupes
* de tester en mode Preview

✅ Passer vérifier que chaque apprenant a un header réutilisable (reusable element).

---

## ✅ **TP 2 – Créer une carte “formation” (45 min)**

### 🎤 À dire

> “Tout commence avec une carte qui représentera visuellement une formation.”

### Élément à créer :

* un **Group**
* avec : titre, organisme, prix, bouton “Voir détails”

### 💡Astuce

Insister sur :
✅ l’alignement
✅ le responsive simple
✅ l’utilisation des styles pour garder un thème cohérent

---

## ✅ **TP 3 – Navigation & responsive (30 min)**

Objectifs :

* relier les pages
* tester l’appli
* ajuster l’affichage pour mobile

---

# ✅ **Fin de Partie I — Livrables attendus**

* Pages principales créées
* Header fonctionnel
* Carte formation prête
* Navigation OK

---

# ✅ **PARTIE II – Base de données & logique métier (4h)**

---

# **🟦 Séquence 3 – Base de données (2h)**

### 🎯 Objectifs

* Définir les types de données
* Comprendre la relation Formation → Notes

---

## ✅ **TP 4 – Créer les types de données (30 min)**

Créer “Formation” :

* titre
* organisme
* prix
* durée
* format
* lien
* description
* catégorie (vide pour l'instant, utilisé avec API)

Créer “Note” :

* score
* commentaire
* formation (linked to Formation)

### ✅ Erreurs courantes

❗ Oublier d’appeler les champs en anglais (Bubble préfère)
❗ Mettre “text” plutôt que “number” pour prix/durée

---

## ✅ **TP 5 – Formulaire d’ajout (45 min)**

### 🎤 À dire

> “Un formulaire n’est rien sans un workflow.”

Créer :
✅ Input texte
✅ Input nombre
✅ Dropdown format
✅ Multi-line description
✅ Bouton “Créer formation”

Workflow :
→ Create new Formation
→ Go to page “benchmark”

---

## ✅ **TP 6 – Afficher les formations (45 min)**

Créer un **Repeating Group** :

* Source = “Do a search for Formation”
* Cell content = la carte créée plus tôt

---

# ✅ **Fin de Partie II — Livrables attendus**

* Base de données complète
* Formulaire opérationnel
* Listing des formations
* Page détail accessible

---

# ✅ **PARTIE III – API, filtres, test, déploiement (6h)**

---

# **🟦 Séquence 5 – Filtres avancés (2h)**

### 🎯 Objectifs

* Créer un moteur de recherche multi-critères

---

## ✅ **TP 7 – Moteur de recherche complet**

Ajouter :
✅ Input “Recherche”
✅ Dropdown “Organisme”
✅ Slider “Budget max”
✅ Dropdown “Format”

Repeating group →
Search for Formation →
constraints dynamiques (prix ≤ slider’s value, titre contains input’s value…)

### 💡Astuce formateur

Insister sur :

* “Is empty” pour gérer les filtres optionnels
* La différence entre :filtered et constraints

---

# **🟦 Séquence 6 – Intégration API (2h)**

### 🎯 Objectifs

* Utiliser API Connector
* Enrichir automatiquement une formation

---

## ✅ **TP 8 – Catégorisation automatique via API**

Préparation :
→ Clé API OpenAI (ou autre API simple)

### Workflow :

“Quand on clique sur ‘Analyser catégorie’”

1. Appel API avec le champ “titre”
2. Réponse text = catégorie prédite
3. Update current Formation → catégorie = API output

✅ Option de secours : API gratuite (Catégorisation texte)

---

# **🟦 Séquence 7 – Tests, debug & déploiement (2h)**

### 🎯 Objectifs

* Vérifier l’application
* Corriger les erreurs
* Publier l’application

---

## ✅ **TP 9 – Mise en production**

Actions :
✅ Preview
✅ Debug mode
✅ Privacy rules
✅ Publish
✅ Tester le lien public

---

# ✅ **Fin de Partie III — Livrables attendus**

* Application entièrement fonctionnelle
* API intégrée
* Filtres avancés
* App publiée

---

# ✅ **Conclusion formateur**

À la fin de ce module, les apprenants auront réalisé :

✅ Une vraie base de données
✅ Une app web complète
✅ Un moteur de recherche multifacteurs
✅ Une intégration API
✅ Un site web publié en production

---

# ✅ **Souhaites-tu maintenant ?**

✅ **La version diaporama (Slides)**
✅ **Un document PDF “pas-à-pas apprenant”**
✅ **La version TP MSPR (évaluation finale + barème)**
✅ **Le maquettage visuel complet (wireframes)**

Dis-moi ce que tu veux que je génère !
