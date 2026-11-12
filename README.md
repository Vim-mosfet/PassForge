# PassForge

# 🔐 PassForge - Générateur Pédagogique de Mots de Passe (Atelier Cybersécurité)

Application web interactive et visuelle conçue pour montrer étape par étape comment transformer une simple phrase facile à retenir en un mot de passe incassable lors d'ateliers de sensibilisation au collège et au lycée.

## 🌐 Accès direct à l'outil en ligne

Le site est hébergé sur GitHub Pages et accessible directement ici :  
👉 **[https://Vim-mosfet.github.io/passforge/](https://Vim-mosfet.github.io/passforge/)**

---

## 🎯 Principe de la démonstration

1. **Choix de la méthode dès l'accueil** : L'intervenant sélectionne la technique qu'il souhaite illustrer au tableau.
2. **Saisie en direct** : Une phrase est tapée au clavier (réplique, parole de chanson, proposition d'un élève).
3. **Progression pas à pas (Touche `Entrée`)** : Chaque étape de transformation s'anime lentement à l'écran pour permettre aux élèves d'observer la construction du mot de passe et d'en comprendre la logique.

---

## 🛠️ Les 2 Méthodes intégrées

### 1. Technique ANSSI (Initiales & Ponctuation)
- Conservation de la première lettre de chaque mot ainsi que des chiffres et ponctuations d'origine.
- *Exemple* : `"J'ai mangé 2 pizzas chez Luigi !"` $\rightarrow$ **`Jm2pcL!`**

### 2. Technique Mnémotechnique (Substitution Visuelle / Leet Speak)
- Extraction des initiales, alternance majuscules/minuscules et remplacement visuel de certaines lettres par des chiffres ou symboles proches graphiquement (`s` $\rightarrow$ `5`, `i` $\rightarrow$ `!`, `e` $\rightarrow$ `3`, `a` $\rightarrow$ `@`, `o` $\rightarrow$ `0`).
- *Exemple* : `"Une souris verte qui courait dans l'herbe"` $\rightarrow$ **`U5v!Qcdlh3?`**

---

## 💻 Stack technique

- **HTML5 / JavaScript ES6** (Application autonome en un seul fichier)
- **Tailwind CSS** (Thème sombre haute visibilité optimisé pour vidéoprojecteur)
