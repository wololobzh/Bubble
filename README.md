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

> Le no-code / low-code sert à :
> 
> ➜ Construire plus vite
> 
> ➜ Moins cher
> 
> ➜ En impliquant plus de monde
> 
> ➜ Tout en gardant la possibilité d’évoluer ensuite
> 
> Par contre
> 
> ❌ Dépendance à la plateforme
> 
> ❌ Liberté technique limitée
> 
> ❌ Ralentissements / limitations avec la complexité
> 
> ❌ Coût qui peut augmenter avec les utilisateurs
> 
> ❌ Intégrations parfois difficiles
> 
> ❌ Maintenance visuelle complexe
> 
> ❌ Demande tout de même des compétences

* Découvrir Bubble

> Je recommande fortement : BUBBLE
> 
> Car :
> 
> * c’est plus complet que Airtable
> * plus simple qu’OutSystems
> * entièrement web (contrairement à certaines fonctionnalités PowerApps)
> * parfait pour construire une vraie application avec front + logique + API
> 
### 🎤 À dire (exemple)

> “Aujourd’hui, on va développer une application web complète, sans coder, mais en appliquant les concepts fondamentaux du développement logiciel.”

### 📽 Démo à faire

1. Montrer Bubble.io
2. Montrer le dashboard
3. Montrer un exemple d’app Bubble existante (Bubble Showcase)

### ✅ Activité : “Définir un benchmark des formation en informatique en Bretagne”

Demander :

> “Quels critères utilisez-vous pour comparer des formations ?”

Noter les idées au tableau pour structurer la base de données ensuite.

**Sortie attendue :** une liste de critères (titre, prix, durée, organisme…)

---

# **🟦 Séquence 2 – Première prise en main (3h)**

## 🎯 Objectifs

* Comprendre comment fonctionne l’éditeur Bubble
* Découvrir Design, Workflow, Data
* Créer les 3 pages du projet fil rouge
* Mettre en place la navigation
* Créer la première UI (la carte formation)

---

## ✅ ✅ ✅ **CE QUE TU DOIS FAIRE EXACTEMENT**

---

### **1) Introduction (5 min)**

🎤 À dire :

> “Dans cette séquence, on va découvrir comment fonctionne Bubble et créer les premières pages de notre application.”

Ensuite, ouvre Bubble et montre en live.

---

### **2) Présenter l’interface Bubble (20 min)**

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

### **3) Démonstration guidée : créer une nouvelle page (10 min)**

Tu leur montres comment faire pour *une* page :

* cliquer *New page*
* choisir un nom simple : `home`

Puis tu leur demandes de répéter pour les 3 pages suivantes.

---

### **4) TP Formateur : Création des pages du projet (20 min)**

Tu leur demandes de créer les pages suivantes :

✅ Page 1 : **home**

✅ Page 2 : **ajouter_formation**

✅ Page 3 : **benchmark**

✅ Page 4 : **details_formation** (option pour plus tard)

Une fois les pages créées, tu fais le tour pour vérifier.

---

### **5) Créer un en-tête (header) réutilisable (20 min)**

🎤 À dire :

> “On va créer un menu commun à toutes les pages grâce aux éléments réutilisables.”

#### Étapes :

1. Bubble → *New reusable element*
2. Nom : `header`
3. Ajouter :

   * logo ou texte “Benchmark Formations”
   * 3 boutons : *Home*, *Ajouter*, *Benchmark*
4. Ajouter une barre horizontale / petit background

✅ **Très important** : leur montrer comment **insérer ce header dans chaque page**.

---

### **6) TP : Mise en place de la navigation (20 min)**

📌 Consigne :

* Cliquer sur le bouton *Home* → Workflow → “Navigate to page home”
* Faire pareil pour les boutons Ajouter & Benchmark

✅ Tu dois vérifier que :

* chaque bouton renvoie vers la bonne page
* les workflows sont créés
* les pages affichent le header

---

### **7) Pause**

---

Checker que c'est ok pour tout le monde.

---

### **8) Démo détaillée – Créer une carte “Formation” (20 min)**

*Objectif : créer une carte propre, réutilisable et adaptée au futur listing des formations.*

---

#### ✅ **🎤 Introduction (à dire – 15 secondes)**

> “Nous allons maintenant créer la carte visuelle d’une formation.
> Cette carte sera utilisée pour afficher les résultats dans le benchmark.
> On va y mettre les infos principales : le titre, l’organisme, le prix et un bouton ‘Voir détails’.”

---

#### ✅ **1) Création du Group principal (5 minutes)**

📌 **Ce que tu fais (à l’écran)**

1. Aller sur la page **benchmark**
2. Cliquer **Add container → Group**
3. Dessiner un rectangle (environ 300px de large × 180px de haut)
4. Dans les propriétés du Group :

   * **Type of content : Formation** (très important pour plus tard)
   * Background color : #FFFFFF
   * Border radius : 12
   * Shadow légère (optionnelle)
   * Layout : **column**
   * Alignement : **center**

🎤 **Ce que tu dis pendant que tu le fais :**

> “Un Group est le conteneur principal d’une carte.
> C’est comme la ‘boîte’ qui contient toutes les informations de la formation.
> On utilise un Group parce qu’une carte représente un objet : ici, une formation.”

✅ **Points pédagogiques à insister :**

* Le Group = 1 unité de donnée
* Toujours organiser la mise en page en colonnes ou lignes
* Ne pas laisser du ‘free layout’ partout

---

#### ✅ **2) Ajouter le titre de la formation (4 minutes)**

📌 **Ce que tu fais**

1. Dans le Group → Add element → **Text**
2. Taper un texte temporaire : **“Titre de la formation”**
3. Style : H3 ou Bold 18–20px
4. Alignement : center
5. Largeur : “Fit width” ou 80% du group

🎤 Ce que tu dis :

> “Le titre est l’élément le plus important. On le met en premier, en gros, centré.
> C’est cette structure que Bubble remplacera plus tard par les données réelles.”

✅ **Astuce :**
Ne mets pas de données dynamiques maintenant, car la base n’existe pas encore. On le fera plus tard.

---

#### ✅ **3) Ajouter l’organisme (2 minutes)**

📌 **Ce que tu fais**

* Ajouter un élément Text sous le titre
* Écrire : “Organisme”
* Style plus discret (12–14px, gris)

🎤 Ce que tu dis :

> “On ajoute l’organisme qui propose la formation.
> Il doit être visible mais moins mis en avant que le titre.”

---

#### ✅ **4) Ajouter le prix (2 minutes)**

📌 **Ce que tu fais**

* Ajouter un Text sous l’organisme
* Écrire : “Prix : 2100 €”
* Mettre en bold léger (15–16px)

🎤 Ce que tu dis :

> “On place le prix juste après.
> Plus tard, cette valeur sera dynamique, issue de la base de données.”

✅ **Astuce design**
Mettre une couleur légèrement différente pour attirer l'œil.

---

#### ✅ **5) Ajouter le bouton ‘Voir détails’ (3 minutes)**

📌 **Ce que tu fais**

1. Ajouter un **Button** en bas du Group
2. Texte : “Voir détails”
3. Style : Primary button
4. Action (pas encore, on le fera dans une prochaine séquence)

🎤 Ce que tu dis :

> “Ce bouton servira pour naviguer vers la page ‘Détails formation’.
> Pour l’instant, il n’a pas encore d’action, mais il doit être présent dans la carte.”

---

#### ✅ **6) Explication des concepts clés (4 minutes)**

🎤 **Tu expliques ceci pendant que tout le monde te regarde :**

##### ✅ 1) **Utilisation des groupes**

> “Chaque carte doit être un Group qui représente un objet ‘Formation’.
> Cela permet à Bubble de comprendre que tous les champs à l’intérieur sont liés à la même formation.”

##### ✅ 2) **Nombre minimal d’éléments**

> “Dans une carte, il faut aller à l’essentiel :
> un titre, un organisme, un prix, un bouton.
> Une carte trop chargée devient illisible.”

##### ✅ 3) **Importance de l’alignement**

> “On garde tout aligné verticalement :
> titre → organisme → prix → bouton.
> Cela améliore la lisibilité et permet un meilleur responsive.”

##### ✅ 4) **Notion de réutilisation**

> “Vous créez un template de carte.
> Plus tard, un Repeating Group va dupliquer automatiquement cette carte pour chaque formation enregistrée.”

🎤 Résumé :

> “Une carte = un conteneur + des textes + un bouton.
> Bubble réutilisera cette carte automatiquement dans la liste.”

---

### **9) TP : Chaque apprenant crée sa carte (25 min)**

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

### **10) Initiation rapide au responsive (10 min)**

🎤 À dire :

> “Bubble a un moteur responsive : on va apprendre juste les bases.”

Tu montres :

* Comment changer la largeur minimale
* Comment centrer
* Comment tester en mobile

---

### **11) Mise en commun + questions (15 min)**

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
