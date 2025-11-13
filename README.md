# 🎓 **Atelier Bubble (14h)**

**Projet fil rouge** : Application de benchmark des offres de formation informatique.

---

# ✅ **0. Préparation**

### ✅ Créer ton propre environnement Bubble

👉 [https://bubble.io](https://bubble.io)
Créer un projet “Benchmark Demo”.

### ✅ Vérifier le matériel

* Apprenants sur Chrome / Edge (éviter Safari)
* Connexion stable
* Casque micro si travail en distanciel

### ✅ Ressources à préparer

* Une fiche “exemple de formation”
* Une clé API Mistral IA (ou alternative)
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

#### ✅ **1) Créer un Type Formation (5 minutes)**


* Va dans l’onglet Data
* Onglet Data types
* Clique "Create a new type"
* Appelle-le Formation
* Ajoute au moins un champ (ex : “titre” en text)

---

#### ✅ **2) Création du Group principal (5 minutes)**

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

#### ✅ **3) Ajouter le titre de la formation (4 minutes)**

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

#### ✅ **4) Ajouter l’organisme (2 minutes)**

📌 **Ce que tu fais**

* Ajouter un élément Text sous le titre
* Écrire : “Organisme”
* Style plus discret (12–14px, gris)

🎤 Ce que tu dis :

> “On ajoute l’organisme qui propose la formation.
> Il doit être visible mais moins mis en avant que le titre.”

---

#### ✅ **5) Ajouter le prix (2 minutes)**

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

#### ✅ **6) Ajouter le bouton ‘Voir détails’ (3 minutes)**

📌 **Ce que tu fais**

1. Ajouter un **Button** en bas du Group
2. Texte : “Voir détails”
3. Style : Primary button
4. Action (pas encore, on le fera dans une prochaine séquence)

🎤 Ce que tu dis :

> “Ce bouton servira pour naviguer vers la page ‘Détails formation’.
> Pour l’instant, il n’a pas encore d’action, mais il doit être présent dans la carte.”

---

#### ✅ **7) Bien nommer les éléments (4 minutes)**


* Clique sur ton élément Text dans la page.
* Regarde la colonne de droite → c’est le Property Editor.
* En tout en haut, tu as une zone avec le nom de l’élément (souvent un truc moche genre Text A).
* Clique dessus et renomme-le comme tu veux, par exemple card_title ou formation_title.

---

#### ✅ **8) Explication des concepts clés (4 minutes)**

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

Bien sûr, je te fais ça version “terrain”, clair et actionnable, pour que tu puisses **vraiment faire la démo** devant les apprenants sans galérer.
Je reste simple et concret, comme si j’étais derrière toi pendant le cours.

---

#### ✅ A. **Changer la largeur minimale (min width)**

Objectif : éviter que les éléments se compressent ou explosent en mobile.

Voici comment le montrer :

1. Clique sur un élément (ex : ton Group principal, ta carte ou un texte).
2. Dans la colonne de droite, tu vas dans l’onglet **Layout**.
3. Tu cherches la ligne **Min width**.
4. Tu leur expliques :

   “Min width, c’est la largeur minimum que l’élément peut atteindre quand l’écran devient petit.”

Exemples que tu peux faire en live :

* mettre min width à **0** pour que la carte accepte de se réduire
* mettre min width à **200px** pour forcer un élément à rester lisible
* montrer la différence en passant en mode mobile (ça réagit instantanément)

⚡ Tip à dire :
“Min width à 0 permet un vrai responsive. Min width trop élevé casse tout en mobile.”

---

#### ✅ B. **Comment centrer un élément**

En Bubble New Editor, le centrage passe par le layout.

Voici la démo “parfaite” à faire :

##### A. Centrer un élément dans un group

1. Clique sur le **Group parent**
2. Dans **Layout**, vérifie que le mode est :
   **Row** (pour centrer horizontalement)
   ou
   **Column** (pour centrer verticalement)
3. Dans **Alignment**, choisis :
   **Center**

Boom, ton élément se place au centre direct.

##### B. Centrer un élément en pleine page

1. Clique sur la page (oui, toute la page est un container)
2. Mets **Layout = column**
3. Dans Alignment, choisis :
   **Center**

Maintenant tout ce que tu mets dedans est centré par défaut.

⚡ Phrase que tu peux dire :
“Bubble centre les choses via le container, pas via l’élément. L’élément n’est jamais responsable de son propre centrage.”

---

##### C. **Tester en mobile**

Démo indispensable et très simple.

Tu show :

1. Le bouton en haut **Responsive mode** (icône d’écran)

2. Une fois dedans, tu peux :

   * glisser la largeur avec la souris
   * cliquer sur les presets : **mobile, tablette, desktop**
   * voir les points de rupture (breakpoints)

3. Démo vite fait :

   * Reduis la largeur
   * Montre comment ta carte ou ton header se réorganise
   * Montre quand les éléments passent à la ligne

⚡ Tip à dire :
“Le responsive, c’est juste : comment ta page se comporte quand on serre la largeur.”

---

##### ✅ D. Bonus pour impressionner la promo (très utile et simple)

###### ✅ Ajuster la **max width** pour éviter une page trop large

Dans le Group ou la page :

* **Max width = 100%**
* Ou fixe-le à 1200px pour faire un contenant “moderne”

###### ✅ Activer “Make this element fixed-width” (à utiliser avec modération)

Démontre l’effet :

* Si coché → l’élément ne se réduit jamais
* Si décoché → il est responsive

---

###### ✅ Petit script que tu peux dire à voix haute (fluide et clair)

Tu peux sortir ça tel quel en cours :

> “Bubble gère le responsive avec trois outils.
>
> 1. La largeur minimale, qui dit jusqu’où un élément peut se réduire.
> 2. Le centrage, qui se fait au niveau du container, pas de l’élément.
> 3. Le mode responsive, qui permet de voir le résultat en mobile.
>    Si vous savez manipuler ces trois trucs, vous êtes capables de faire 90 pour cent du responsive sur Bubble.”

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

## 🎯 Objectifs

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

Voici comment faire **TP 5 – Formulaire d’ajout** découpé en actions très précises pour Bubble. Tu peux suivre pas à pas à l’écran.

### 🧩 Objectif

Créer un **formulaire** qui ajoute une **Formation** en base, avec validations simples, puis redirige vers la page **benchmark**.

---

#### a) Préparer les champs (Data)

> Si tu as déjà créé le type **Formation**, vérifie juste les champs.

1. Onglet **Data → Data types**
2. Type **Formation** avec champs :

   * `title` (text)
   * `provider` (text)
   * `price` (number)
   * `duration_hours` (number) *ou* `duration` (text/number, à toi de choisir)
   * `format` (text **ou** Option set, voir ci-dessous)
   * `link` (text)
   * `description` (text, “long text”)
   * `category` (text) *(servira plus tard avec l’API)*

💡 **Option Set (recommandé) pour `format`**
Onglet **Data → Option sets → New option set** : `TrainingFormat`
Options : `Presentiel`, `Distanciel`, `Hybride`
Dans **Formation.format**, choisis le type **TrainingFormat** (au lieu de text).

---

#### b) Poser les éléments du formulaire (Design)

Sur la page **ajouter_formation** :

1. Ajoute un **Group** conteneur (layout = Column, gap 12–16).
   Renomme : `grp_form_formation`.
2. Dans ce group, ajoute les inputs :

   * **Input** → placeholder “Titre de la formation” → id : `inp_title`
   * **Input** → placeholder “Organisme” → id : `inp_provider`
   * **Input** → placeholder “Prix (en €)” → **Content format = Integer** → id : `inp_price`
   * **Input** → placeholder “Durée (heures)” → **Content format = Integer** → id : `inp_duration`
   * **Dropdown** → id : `dd_format`

     * Si **Option set** : *Type of choices* = **TrainingFormat**, *Option caption* = **This Option’s Display**
     * Si **texte** : *Static choices* = “Présentiel, Distanciel, Hybride”
   * **Multiline Input** → placeholder “Description” → id : `ml_description`
   * **Input** → placeholder “Lien (https…)” → id : `inp_link`
3. Ajoute un **Button** “Créer formation” → id : `btn_create`.
4. (Optionnel) Ajoute un **Alert** (element) pour afficher un message de succès → id : `al_success`.

**Responsive rapide**

* Sur `grp_form_formation` : width max 600–720px, centré (Container alignment = center).
* Chaque input : **Fit width** activé, min width ~ 280px.

---

#### c) Petites validations UX (sans plugin)

Sélectionne chaque input et règle :

* `inp_title` / `inp_provider` : **This input should not be empty** ✓
* `inp_price` : **Content format = Integer**, ajoute **Min 0** (dans “Validate the input”).
* `inp_link` : **Content format = Text** (tu peux ajouter une condition plus tard).
* `dd_format` : coche **This input should not be empty**.

**Désactiver le bouton tant que ce n’est pas valide**

* Sur `btn_create` → onglet **Conditional** :

  * Condition : `When inp_title's value is empty or inp_provider's value is empty or inp_price's value is empty or dd_format's value is empty`
  * Propriétés : **This element is disabled** = true, **Opacity** = 0.6.

---

#### d) Workflow de création

1. Onglet **Workflow** → **+ Start/Edit workflow** en cliquant sur `btn_create`.
2. **Event** : *When Button btn_create is clicked*
   **Only when** *(à droite du déclencheur)* :
   `inp_title's value is not empty and inp_provider's value is not empty and inp_price's value is not empty and dd_format's value is not empty`
3. **Action 1 — Data (Things) → Create a new thing**

   * *Type* : **Formation**
   * Champs → valeurs :

     * `title` = `inp_title's value`
     * `provider` = `inp_provider's value`
     * `price` = `inp_price's value`
     * `duration_hours` = `inp_duration's value`
     * `format` =

       * si Option set : `dd_format's value`
       * si texte : `dd_format's value`
     * `description` = `ml_description's value`
     * `link` = `inp_link's value`
4. **Action 2 — Element actions → Show message** (si tu as mis un Alert)

   * `al_success` → message “Formation créée !”
5. **Action 3 — Reset relevant inputs** (Data → Reset relevant inputs)
   → vide le formulaire.
6. **Action 4 — Navigation → Go to page**

   * Page : **benchmark**
   * (Optionnel) **Send more parameters** :

     * `new` = `yes` (pratique pour afficher un toast sur benchmark)

> Variante : au lieu de l’Action 4, tu peux **envoyer la formation créée** vers une page de détails :
>
> * Dans Action 1, clique “Result of step 1”
> * **Navigation → Go to page details_formation** with **Data to send = Result of step 1**.

---

#### e) Bonus utiles (faciles)

* **Slug SEO** : après création, ajoute **Action → Make changes to a thing** sur *Result of step 1* → `slug = inp_title's value:slugify`.
* **Vérifier le lien** : condition “Only when `inp_link's value` contains ‘http’” sinon afficher un Alert d’erreur.
* **Réutilisable “FormFormation”** : transforme `grp_form_formation` en **Reusable element** pour avoir le même composant en “Créer” et “Éditer”.

  * Si le Reusable reçoit un **type de contenu = Formation**, alors :

    * Mode **Créer** : *Parent group’s Formation is empty* → bouton = “Créer”.
    * Mode **Éditer** : pré-remplis **Initial content** des inputs avec *Parent group’s Formation’s…* et workflow = **Make changes to a thing**.

---

#### f) Tests & debug

* **Preview** la page → remplis → clique.
* Si rien ne se passe, ouvre **Logs → Step-by-step** depuis le debugger et rejoue le clic pour voir si une condition bloque.
* Onglet **Issues** (barre du haut) pour corrections rapides.

---

#### g) Récap express (checklist)

* [ ] Inputs posés et nommés (`inp_*`, `dd_*`, `ml_*`)
* [ ] Validations “should not be empty” et min/max
* [ ] Bouton désactivé tant que non valide
* [ ] Workflow “Create a new Formation” + Reset + Go to page
* [ ] (Bonus) Slug, Alert succès, Reusable pour réutiliser le même formulaire

---

## ✅ **TP 6 – Afficher les formations (45 min)**

Créer un **Repeating Group** :

* Source = “Do a search for Formation”
* Cell content = la carte créée plus tôt

Super, on fait **TP 6 – Afficher les formations** pas-à-pas. Objectif : lister toutes les *Formation* déjà créées dans la base avec une jolie carte par élément.

---

### Étapes détaillées (≈45 min)

#### 0) Pré-requis rapides (2 min)

* Type de donnée **Formation** existe (titre, organisme, prix, etc.).
* Tu as déjà une **carte** (group “Group Formation”) dont le **Type of content = Formation** et dont les textes sont dynamiques/vides pour l’instant.
* Page cible : **benchmark** (ou la page liste).

---

#### 1) Placer un Repeating Group (RG) (5–7 min)

1. Ouvre la page **benchmark**.
2. **Design → Containers → Repeating Group** (ou “RepeatingGroup”).
3. Dessine le RG au centre de la page (prends large).
4. Propriété du RG :

   * **Type of content** : `Formation`
   * **Layout style** :

     * Débutants : **Full list** (affiche tout, simple)
     * Ou **Ext. vertical scrolling** (scroll infini)
   * **Cells** : commence avec **3 colonnes** × **2 lignes** (tu ajusteras).
   * **Min width cell** : ~280–320 px (selon ta carte).
5. **Data source** du RG :

   * Clique le champ *Data source* → **Do a search for… → Formation**
   * (Optionnel) **Sort by** : `title` ou `price` selon ce que tu veux.

> Résultat attendu : ton RG sait “qu’il doit afficher des Formation”.

---

#### 2) Mettre la carte dans la cellule (2 options) (10–12 min)

=> En glisser / déposer sur le premier élément

##### Option A — Tu utilises ta carte *comme un Group* (simple)

1. Clique **une cellule** du RG (double-clic dans la première).
2. **Add → Container → Group** (si ta carte n’était pas encore posée).
3. **Type of content** du Group : `Formation`.
4. **Data source** du Group : `Current cell's Formation`.
5. Place dedans tes éléments (Titre/Organisme/Prix/Bouton) **et remplace** les textes par des **données dynamiques** :

   * Title → `Parent group's Formation's title`
   * Organisme → `Parent group's Formation's organisme`
   * Prix → `Parent group's Formation's price:formatted as…`
6. Stylise (padding, alignement, radius, shadow).

##### Option B — Tu as fait une **carte réutilisable** (Reusable Element) (clean & DRY)

1. Dans la cellule du RG, **Add → Reusable elements → TaCarteFormation**.
2. Sélectionne le composant → dans **Data source / Element data** mets :

   * `Current cell's Formation`.
3. À l’intérieur du Reusable (déjà créé), tous les champs doivent pointer vers **`Parent's thing`** (i.e. la Formation reçue).

> Résultat attendu : une cellule montre la carte avec des données; les autres se rempliront automatiquement.

---

#### 3) Bouton “Voir détails” (workflow) (5–8 min)

1. Sélectionne le **bouton** dans la carte (celui dans la cellule).
2. **Workflow → Start/Edit workflow**.
3. **Action → Navigation → Go to page…** : choisis **details_formation**.
4. **Send data to page** : **Current cell’s Formation** (ou `Parent group's Formation` selon Option A/B).
5. Sur la page **details_formation**, règle **Type of content = Formation** et lie tes champs à **Current page's Formation**. 

---

#### 4) État “liste vide” (2–3 min)

* Clique le RG → **No data source / Empty state** (ou ajoute un **Text** conditionnel) :

  * “Aucune formation pour le moment.”
  * Condition : *When RepeatingGroup Formation’s list of Formation:count is 0 → this text is visible*.

---

#### 5) Pagination (si tu as choisi “Fixed number of cells”) (5 min)

* Ajoute deux boutons sous le RG : **Précédent** / **Suivant**.
* Crée un **Custom state** sur la page : `page (number)` par ex., valeur par défaut = 1.
* **Data source** du RG → `Do a search for Formation :items from ((page-1)*X+1) :items until (page*X)`
  (X = nb d’éléments par page, ex. 6).
* Workflow “Suivant” : **Set state page = page+1** (ajoute condition si fin de liste).
* Workflow “Précédent” : **Set state page = max(1, page-1)**.

*(Si tu as mis “Ext. vertical scrolling”, inutile : Bubble charge au scroll.)*

---

#### 6) Responsive propre (5–7 min)

* Sélectionne le RG → **Layout** :

  * **Row gap / Column gap** pour l’espacement.
  * Coche **Wrap to previous line** si tu veux que les cartes passent à la ligne quand l’écran rétrécit.
* Ouvre **Responsive** (icône mobile en haut) :

  * Teste 320–1440px.
  * Ajuste **min width** de la cellule et **min width** des éléments de la carte pour éviter les chevauchements.
  * Aligne **center** dans la cellule si besoin.

---

#### 7) Tests (3–5 min)

* Va sur la page **ajouter_formation**, crée 3–5 entrées (ou passe par **Data → App data → Add entry**).
* **Preview** la page **benchmark**.
* Vérifie :

  * Les cartes se répètent.
  * Les textes affichent bien les bonnes valeurs.
  * Le bouton **Voir détails** envoie vers la bonne page avec la bonne *Formation*.
  * Le responsive est OK.

---

#### Dépannage rapide

* **Rien ne s’affiche ?**

  * Vérifie **Type of content** du RG = *Formation*.
  * Vérifie **Data source** = *Do a search for Formation*.
  * Regarde **Privacy rules** (Data → Privacy) : autorisent-elles la lecture ?
* **Les champs restent “static” ?**

  * Remplace le texte fixe par **Insert dynamic data** vers `Parent group/Current cell's Formation`.
* **Le bouton n’emmène pas la bonne fiche ?**

  * Dans le workflow **Go to page**, assure-toi d’envoyer **Current cell’s Formation** (pas la page entière).

---

#### Bonus (si temps)

* **Tri** : ajoute un dropdown “Trier par” (prix, durée, titre) et change le **:sorted by** de la recherche.
* **Compteur** : Text = `RepeatingGroup Formation's List of Formation:count & " résultats"`.

Si tu bloques sur un point précis (libellé exact de Bubble FR/EN, options manquantes), dis-moi ce que tu vois dans l’IHM et je t’indique le clic exact à faire.


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

Excellent, tu arrives à la partie la plus “magique” de Bubble 💪
Le **TP7 – Moteur de recherche complet** permet de filtrer dynamiquement les formations selon plusieurs critères (texte, organisme, budget, format).
Voici **toutes les étapes détaillées** pour que tu puisses le faire sans galérer 👇

---

### 🎯 Objectif du TP

Créer une page (souvent `benchmark`) qui contient :

* des champs de recherche (Input / Dropdown / Slider)
* un **Repeating Group (RG)** qui affiche les formations
* un filtrage dynamique selon les valeurs saisies par l’utilisateur

---

### ⚙️ 1️⃣ Préparer la page

Va dans ta page **benchmark** (celle où tu affiches déjà les formations avec un Repeating Group).

Tu dois déjà avoir un RG qui affiche les formations :

> Repeating Group → Type of content : Formation
> Data source : “Do a search for Formation”

Si tu ne l’as pas encore, crée-le :

1. **Add element → Repeating Group**
2. Type of content → `Formation`
3. Data source → `Do a search for Formation`
4. Dans chaque cellule, insère le **Group Formation** (ou ta carte formation)

---

### ⚙️ 2️⃣ Ajouter les filtres au-dessus du Repeating Group

Ajoute les éléments suivants au-dessus du RG :

| Élément    | Type Bubble | Nom recommandé       | Description                          |
| ---------- | ----------- | -------------------- | ------------------------------------ |
| Recherche  | Input       | `input_search`       | pour taper un mot-clé dans le titre  |
| Organisme  | Dropdown    | `dropdown_organisme` | pour filtrer par organisme           |
| Budget max | Slider      | `slider_budget`      | pour limiter le prix max             |
| Format     | Dropdown    | `dropdown_format`    | pour filtrer par format de formation |

#### ➕ Paramétrage de chacun :

##### 🟩 Input “Recherche”

* Placeholder : “Rechercher une formation…”
* Type : texte normal

##### 🟩 Dropdown “Organisme”

* Type of choices : “Dynamic choices”
* Type of content : `Formation`
* Choices source : `Do a search for Formation`
* Option caption : `Organisme`
* (tu peux aussi utiliser une “static list” si tu veux les taper à la main)

##### 🟩 Slider “Budget max”

* Valeur min : 0
* Valeur max : 5000 (ou selon ton jeu de données)
* Valeur initiale : 2000
* Nom : `slider_budget`

##### 🟩 Dropdown “Format”

* Type of choices : “Static choices”
* Choices : Présentiel, Distanciel, Hybride (par ex.)
* Nom : `dropdown_format`

---

### ⚙️ 3️⃣ Relier les filtres au Repeating Group

Maintenant, on va dire au Repeating Group :

> “Montre-moi toutes les formations qui correspondent aux filtres.”

#### Étape :

1. Clique sur ton **Repeating Group**
2. Dans **Data source**, clique sur “Insert dynamic data”
3. Choisis **“Do a search for Formation”**
4. Clique sur **More** pour ouvrir les “constraints”

---

### ⚙️ 4️⃣ Ajouter les constraints dynamiques

Tu vas ajouter plusieurs conditions (constraints) selon les filtres :

| Champ     | Constraint                               | Exemple                                |
| --------- | ---------------------------------------- | -------------------------------------- |
| Titre     | `titre contains input_search's value`    | filtre par mot-clé                     |
| Organisme | `organisme = dropdown_organisme's value` | filtre si un organisme est sélectionné |
| Prix      | `prix ≤ slider_budget's value`           | filtre selon le budget                 |
| Format    | `format = dropdown_format's value`       | filtre par format                      |

⚠️ **Important** : ces constraints doivent être dynamiques, mais si un filtre est vide (ex : aucun organisme sélectionné), Bubble risque d’exclure toutes les données.
👉 Pour éviter ça, on utilise **“:filtered” + “Advanced filter”** ou bien des “constraints conditionnels”.

---

### ⚙️ 5️⃣ Méthode simple : utiliser `:filtered` avec “Advanced filter”

1. Repeating Group → Data source =

   ```bubble
   Do a search for Formation:filtered
   ```
2. Clique sur “Advanced” dans la fenêtre de filtres.
3. Ajoute les conditions suivantes :

```bubble
(this Formation's titre:lowercase contains input_search's value:lowercase)
and (dropdown_organisme's value is empty or this Formation's organisme = dropdown_organisme's value)
and (dropdown_format's value is empty or this Formation's format = dropdown_format's value)
and (slider_budget's value is empty or this Formation's prix ≤ slider_budget's value)
```

✅ Ce code “logique” veut dire :

> “Montre-moi la formation si elle correspond aux filtres,
> ou si le filtre est vide, je l’ignore.”

---

### ⚙️ 6️⃣ Tester le moteur de recherche

1. Clique sur **Preview**.
2. Tape un mot dans “Recherche” → le RG doit se mettre à jour.
3. Change le Dropdown “Organisme” → le RG doit filtrer.
4. Déplace le slider “Budget” → le RG se met à jour selon le prix.
5. Change le “Format” → idem.

Si ça ne se met pas à jour automatiquement :

* coche “This input should cause a search to run automatically”
* ou ajoute un bouton “Rechercher” qui **“Display list in Repeating Group”** avec la même data source.

---

### 💡 Astuces formateur

✅ “Is empty” → permet d’ignorer un filtre vide.
✅ “:filtered” → s’exécute côté client, donc plus flexible.
✅ Pour les performances : si ta base devient grosse, déplace un maximum de conditions dans le “Do a search for …” (côté serveur).

---

Souhaites-tu que je te montre aussi **la version “performante”** (filtrage côté serveur avec conditions dynamiques propres) ?
Elle est un peu plus technique, mais utile si tu veux aller plus loin.


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

Parfait 👌 tu veux refaire le **TP8 – Catégorisation automatique via API**, mais **en utilisant Mistral AI à la place d’OpenAI**.
Très bon réflexe, c’est 100 % faisable — voici **le tutoriel complet pas à pas pour l’intégrer dans Bubble** 👇

---

### 🎯 Objectif

Quand l’utilisateur clique sur **“Analyser catégorie”**,
→ Bubble envoie le **titre de la formation** à **Mistral AI**,
→ Mistral répond avec une **catégorie texte**,
→ cette catégorie est enregistrée dans le champ `catégorie` de la base `Formation`.

---

### 🧩 Étape 1 — Récupérer ta clé API Mistral

1. Va sur : [https://console.mistral.ai](https://console.mistral.ai)
2. Crée un compte (ou connecte-toi)
3. Va dans **API Keys → Create new key**
4. Copie ta clé (ex : `mistral-xxxxx...`)

---

### ⚙️ Étape 2 — Installer et configurer l’API Connector

1. Dans Bubble, ouvre l’onglet **Plugins**
2. Clique **Add plugins**
3. Recherche **API Connector**
4. Clique **Install**

Ensuite :

1. Ouvre **API Connector**
2. Clique sur **Add another API**
3. Nomme-la par ex. `Mistral Categorization`

---

### ⚙️ Étape 3 — Créer l’appel API Mistral

Clique sur **Add another call** et configure comme suit 👇

| Champ         | Valeur                                       |
| ------------- | -------------------------------------------- |
| **Name**      | `Categorize Formation`                       |
| **Use as**    | Action                                       |
| **Data type** | JSON                                         |
| **Method**    | POST                                         |
| **URL**       | `https://api.mistral.ai/v1/chat/completions` |

#### Headers :

| Key             | Value                 |
| --------------- | --------------------- |
| `Authorization` | `Bearer YOUR_API_KEY` |
| `Content-Type`  | `application/json`    |

(⚠️ remplace `YOUR_API_KEY` par ta vraie clé)

---

#### Body (JSON) :

```json
{
  "model": "mistral-small-latest",
  "messages": [
    {
      "role": "system",
      "content": "Tu es un assistant qui classe les formations dans une catégorie simple : Développement, Réseau, Cybersécurité, Data, IA, Bureautique, etc."
    },
    {
      "role": "user",
      "content": "Catégorise cette formation : <titre>"
    }
  ],
  "temperature": 0.3,
  "max_tokens": 20
}
```

✅ Clique sur **Initialize call**
💡 Quand Bubble te demande un exemple de valeur pour `<titre>`, tu peux taper “Formation Administrateur Réseau”.

Une fois que c’est validé, tu verras une réponse comme :

```json
{
  "choices": [
    {
      "message": {
        "content": "Réseau"
      }
    }
  ]
}
```

---

### ⚙️ Étape 4 — Créer le bouton “Analyser catégorie”

Sur ta page (ex : `ajouter_formation` ou `details_formation`) :

1. Ajoute un **Button** nommé “Analyser catégorie”
2. Donne-lui un ID logique : `btn_analyser_categorie`

---

### ⚙️ Étape 5 — Créer le workflow

1. Sélectionne ton bouton → **Start/Edit workflow**
2. Clique **Add an action**
3. Va dans **Plugins → Mistral Categorization → Categorize Formation**
4. Dans le champ `titre`, insère la donnée dynamique :
   `Current Formation's titre`

🧠 (Bubble enverra automatiquement le texte du titre de la formation à l’API.)

---

### ⚙️ Étape 6 — Utiliser le résultat

Juste après, ajoute une autre action :

1. **Data → Make changes to a thing**
2. Thing to change → `Current Formation`
3. Nouveau champ :

   * `Catégorie = Result of step 1 (Categorize Formation)'s choices:first item's message:content`

💡 Cela enregistre le texte renvoyé par Mistral (ex. “Cybersécurité”) dans la base.

---

### ✅ Étape 7 — Tester le tout

1. Lance le **Preview**
2. Va sur une formation
3. Clique “Analyser catégorie”
4. Attends 1–2 secondes → la catégorie se remplit dans ta base

---

### 💡 Astuce bonus

Tu peux aussi :

* afficher un **Alert “Catégorie mise à jour !”** à la fin du workflow
* ou bien **mettre un loader (popup)** pendant l’appel API (via condition `When API call is loading`)

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

Parfait 👏 tu arrives au **dernier TP de ton atelier Bubble : la mise en production !**
C’est une étape super importante, car elle te fait passer d’une **application “en développement”** à une **application publique**, que n’importe qui peut utiliser depuis un lien web.

Voici le déroulé **étape par étape, sans rien oublier** 👇

---

## 🎯 Objectif du TP 9

À la fin de cette séquence, tu sauras :

* tester ton app dans différents modes (preview, debug)
* sécuriser tes données avec des “Privacy rules”
* publier ton application Bubble
* vérifier que ton lien public fonctionne correctement

---

### 🧩 **1️⃣ Preview – Tester ton app en mode apprenant**

#### ▶️ Comment faire

Dans l’éditeur Bubble :

* En haut à droite, clique sur le bouton **Preview**
* Ou appuie sur **Ctrl + P (Windows)** ou **Cmd + P (Mac)**

Cela ouvre ton app dans une nouvelle fenêtre avec une URL du type :

```
https://tonapp.bubbleapps.io/version-test/benchmark
```

#### 💡 À faire :

* Vérifie que tout s’affiche correctement
* Teste tes formulaires, workflows, filtres
* Ajoute et supprime une formation pour t’assurer que tout marche

---

### 🔍 **2️⃣ Debug Mode – Voir ce qui se passe “sous le capot”**

Bubble dispose d’un outil de **debug visuel** super utile.

#### ▶️ Comment l’activer

* Dans l’URL de ton app, ajoute `?debug_mode=true` à la fin, par exemple :

  ```
  https://tonapp.bubbleapps.io/version-test/benchmark?debug_mode=true
  ```

#### 🧠 Ce que ça permet :

* Voir **toutes les actions** qui se déclenchent en temps réel (workflows)
* Inspecter les **données dynamiques** (ex. ce que contient un champ)
* Mettre le **mode “Step by step”** pour exécuter ton workflow lentement

#### 💡 À tester :

1. Clique sur un bouton (ex. “Créer formation”)
2. Ouvre la barre du bas → clique sur **Step by step**
3. Tu verras chaque étape s’exécuter et les valeurs associées

C’est parfait pour comprendre **pourquoi un workflow ne marche pas** ou pourquoi une donnée est vide.

---

### 🔒 **3️⃣ Privacy Rules – Sécuriser ta base de données**

Par défaut, **toutes les données Bubble sont publiques** 😱 (si ton app est publiée).
Il faut donc définir des **règles de confidentialité**.

#### ▶️ Comment faire

1. Va dans **Data → Privacy**
2. Sélectionne le type de données **Formation**
3. Clique sur **Add a new rule**

#### Exemple de règles :

| Condition       | Autorisation                                                          |
| --------------- | --------------------------------------------------------------------- |
| *Tout le monde* | Peut voir seulement les champs “titre”, “organisme”, “prix”, “format” |
| *Créateur*      | Peut modifier et supprimer                                            |

#### Pour faire ça :

1. Coche **Everyone else** → autorise uniquement “View all fields”
2. Décoche “Modify” et “Delete”
3. Ajoute une autre règle :

   * Condition : `This Formation's Creator is Current User`
   * Coche “View”, “Modify”, “Delete”

💡 **Astuce** : si tu veux être prudent, commence par interdire tout, puis ajoute les permissions nécessaires.

---

### 🌍 **4️⃣ Publish – Mettre ton app en ligne**

C’est le moment de vérité 😄

#### ▶️ Étapes :

1. Clique sur le bouton **Deploy** en haut à droite (icône fusée 🚀)
2. Dans la fenêtre qui s’ouvre :

   * Vérifie que tu déploies **de version-test → live**
   * Clique sur **Deploy current version to live**
3. Bubble va publier ton app en ligne sur une URL du type :

   ```
   https://tonapp.bubbleapps.io
   ```

💡 Si tu veux ton **propre nom de domaine** :

* Va dans **Settings → Domain / email**
* Clique sur “Set up your domain”
* Suis les instructions pour relier ton nom de domaine (ex. `monapp.fr`)

---

### 🔗 **5️⃣ Tester le lien public**

Va sur :

```
https://tonapp.bubbleapps.io
```

Teste ton application comme un vrai utilisateur :

* Ouvre le lien dans un autre navigateur (ou une session privée)
* Vérifie que la navigation fonctionne
* Vérifie qu’on ne peut pas modifier/supprimer des formations sans autorisation
* Si tu utilises une API (comme Mistral), teste qu’elle fonctionne aussi en version live

---

### ✅ **Check-list finale du TP 9**

| Étape            | Action                             | OK |
| ---------------- | ---------------------------------- | -- |
| 🔍 Preview       | L’app fonctionne en mode test      | ☐  |
| 🪄 Debug         | Tu as vérifié les workflows        | ☐  |
| 🔒 Privacy rules | Les données sont sécurisées        | ☐  |
| 🚀 Publish       | L’app est déployée en version live | ☐  |
| 🌐 Test public   | Le lien public fonctionne bien     | ☐  |

---

### 🧠 Bonus : astuces de formateur

* Avant de publier, demande aux apprenants :

  > “Est-ce que vous seriez prêts à partager votre lien public ?”
* Encourage-les à tester depuis leur téléphone (responsive !)
* Rappelle qu’ils peuvent revenir en “version-test” pour faire des modifs sans casser la prod

---

## ✅ **Fin de Partie III — Livrables attendus**

* Application entièrement fonctionnelle
* API intégrée
* Filtres avancés
* App publiée

---

## ✅ **Conclusion formateur**

À la fin de ce module, les apprenants auront réalisé :

✅ Une vraie base de données

✅ Une app web complète

✅ Un moteur de recherche multifacteurs

✅ Une intégration API

✅ Un site web publié en production

Excellent cours 👏 — ton parcours Bubble sur deux jours est hyper complet et bien structuré.
Voici **3 TP bonus** que tu peux proposer aux apprenants les plus rapides : chacun exploite une dimension différente de Bubble (UX, base de données avancée, intégrations).
Ils sont conçus pour **30 à 45 minutes chacun**, selon le niveau du groupe.

---

## 💎 **TP Bonus 1 – Ajouter un système de “favoris” (base de données + UX)**

### 🎯 Objectif

Permettre à l’utilisateur de **“liker” ou “ajouter en favoris”** une formation pour la retrouver plus tard.

### 🧩 Étapes

1. **Créer un nouveau type de données** :
   *Nom* : `Favori`
   *Champs* :

   * `formation` (Type = Formation)
   * `utilisateur` (Type = User)

2. Sur la carte **Formation** :
   ➜ Ajouter un **icône “❤️” ou “⭐”** (FontAwesome ou Material).
   ➜ Créer un workflow :

   > *Quand l’icône est cliquée → Create a new Favori → formation = Current cell’s Formation, utilisateur = Current User*

3. (Optionnel) Gérer le toggle :

   * Si le favori existe déjà, le supprimer plutôt que le recréer.
   * Modifier la couleur de l’icône selon l’état (rempli / vide).

4. **Nouvelle page “Mes favoris”** :

   * Crée une page `favoris`
   * Repeating Group → `Do a search for Favori`

     * Constraint : `utilisateur = Current User`
   * Affiche `Favori’s formation’s titre`, `organisme`, `prix`.

👉 **Livrable attendu** : un système fonctionnel où chaque utilisateur peut marquer ses formations préférées et les revoir sur une page dédiée.

---

## 🔍 **TP Bonus 2 – Ajouter un score moyen et des avis (Note & calcul dynamique)**

### 🎯 Objectif

Permettre aux utilisateurs de **noter les formations** et afficher une **moyenne des scores**.

### 🧩 Étapes

1. Vérifie que tu as déjà un type `Note` :

   * `score` (Number)
   * `commentaire` (Text)
   * `formation` (Formation)
   * `utilisateur` (User)

2. Sur la page **details_formation** :

   * Ajoute un **Slider (0–5)** pour la note
   * Ajoute un **Multiline Input** pour le commentaire
   * Ajoute un bouton **“Laisser un avis”**

3. Workflow du bouton :

   * Action : *Create a new Note*
     → score = slider’s value
     → commentaire = input’s value
     → formation = Current page’s Formation
     → utilisateur = Current User

4. Sous la description, affiche :

   * Moyenne des notes :

     > `Search for Note's score:average` avec contrainte `formation = Current page’s Formation`
   * Liste des commentaires :

     > Repeating Group “Do a search for Note (formation = Current page’s Formation)”

👉 **Livrable attendu** :
Page “Détails” qui montre la moyenne des avis et les commentaires postés.

---

## 🌐 **TP Bonus 3 – Créer un tableau de bord admin (DataViz + gestion)**

### 🎯 Objectif

Créer une page **admin** avec des statistiques sur les formations.

### 🧩 Étapes

1. **Créer une page “admin”**
   (réservée au formateur, ou tout utilisateur admin)

2. Ajouter un **Repeating Group** :

   * Source : `Do a search for Formation`
   * Colonnes : titre, prix, format, catégorie

3. Ajouter des **textes dynamiques statistiques** :

   * `Nombre total de formations : Search for Formation:count`
   * `Prix moyen : Search for Formation's price:average`
   * `Catégorie la plus fréquente : Search for Formation's catégorie:grouped by catégorie:first item's catégorie`

4. (Bonus visuel)
   ➜ Installe le plugin **Chart.js** (ou “Simple Charts”).
   ➜ Crée un **graphique à barres** :

   * X = catégorie
   * Y = nombre de formations par catégorie (`grouped by catégorie:count`)

5. (Optionnel)
   Ajoute un bouton “Exporter en CSV” :

   * Action → *Download data as CSV* sur la liste des formations.

👉 **Livrable attendu** : une page “admin” claire avec quelques KPI et un graphique interactif.

---

## 🎁 Résumé rapide

| TP Bonus                 | Thème                            | Durée estimée | Compétences mobilisées                 |
| ------------------------ | -------------------------------- | ------------- | -------------------------------------- |
| 1. Favoris               | Base de données + UI dynamique   | 30–40 min     | Requêtes liées & états conditionnels   |
| 2. Avis & moyenne        | Calculs & relations entre tables | 45 min        | Recherche, agrégats, workflows         |
| 3. Tableau de bord admin | DataViz & statistiques           | 45 min        | Grouped by, chart, gestion des données |

