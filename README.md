# 🌿 Ficus Seedbank (Dépôt de Contributions)

Bienvenue dans l'espace collaboratif et la pépinière de **ficus-quiz** ! 🚀

Ce dépôt permet aux collaborateurs de créer, relire et valider les questions et les quiz avant leur intégration officielle dans l'application. Initialement conçu pour le développement web, le projet est totalement évolutif et s'étend à tous les domaines (développement mobile, médecine, etc.). 

C'est ici que le contenu germe et se peaufine !

---

## 📂 Structure du Répertoire

*   `/propositions/` : Pour soumettre des questions isolées (les "graines"). 1 fichier `.md` par question.
*   `/quizzes/` : Pour assembler des séries de questions validées en quiz complets.
*   `/templates/` : Les modèles de base à copier-coller pour vos propositions.

---

## ✍️ Comment contribuer ?

1. Allez dans le dossier `/propositions/`.
2. Créez un fichier Markdown en suivant strictement cette convention de nommage : `domaine-categorie-motcle.md`
   *(Exemples : `devweb-accessibility-wcag.md`, `mobile-android-compose.md`, `medecine-anatomie-coeur.md`)*.
3. Copiez-collez le contenu de `/templates/template-question.md` et remplissez les sections.

### 📊 Les Niveaux de Difficulté
Lors de la création, attribuez l'un de ces trois mots-clés :
*   `debutant` : Concepts de base, fondamentaux, syntaxe simple.
*   `intermediaire` : Pratique courante, logique plus poussée, cas concrets.
*   `avance` : Cas d'usage complexes, expertise, normes pointues, optimisation.

### 🔄 Le Cycle de vie d'une question (`status`)
Dans les métadonnées de votre fichier, mettez à jour le statut selon l'avancement :
*   `draft` (Brouillon) : Vous travaillez encore sur la question.
*   `review` (En relecture) : La question est prête, vous attendez les retours et corrections des autres collaborateurs.
*   `approved` (Validé) : La question est validée par l'équipe et prête à être intégrée dans l'application finale.

---

## 🛠️ Règles d'or du contenu

Pour garantir la haute qualité pédagogique de **ficus-quiz**, chaque proposition doit obligatoirement respecter ces deux critères :
1. **Une explication claire :** Ne donnez pas juste la réponse. Écrivez une brève explication pour que l'utilisateur comprenne *pourquoi* c'est la bonne réponse et *pourquoi* les autres sont fausses.
2. **Un lien vers la documentation :** Ajoutez systématiquement un lien vers une documentation officielle ou une source fiable pour permettre d'approfondir le sujet.

---

## 🌿 Gestion des Branches et Workflow Git

Pour maintenir la branche principale propre et organiser sereinement les relectures, **nous n'écrivons jamais directement sur la branche `main`**. Chaque contribution doit suivre ce workflow :

### 1. Règle de nommage des branches
Nommez votre branche de travail en respectant la convention suivante : 
`nom-du-contributeur/domaine-sujet`

*   *Exemple :* `alex/devweb-flexbox`
*   *Exemple :* `sarah/medecine-cardiologie`

### 2. Le Workflow pas-à-pas

1. **Synchronisez votre dépôt local** avec le projet pour partir sur une base propre :
```bash
   git checkout main
   git pull origin main

```

2. **Créez et basculez** sur votre nouvelle branche :

```bash
   git checkout -b pseudo/domaine-sujet

```

3. **Rédigez votre question** dans le dossier `/propositions/` en suivant le template, puis sauvegardez vos modifications :

```bash
   git add propositions/votre-fichier.md
   git commit -m "feat: proposition question sur le sujet X"

```

4. **Publiez votre branche** sur le dépôt distant :

```bash
   git push origin pseudo/domaine-sujet

```

5. **Ouvrez une Pull Request (PR)** sur GitHub/GitLab vers la branche `main`.
* Passez le statut du fichier à `status: review` pour inviter l'équipe à relire.
* Une fois la relecture terminée et le statut passé à `status: approved`, un administrateur fusionnera la branche.
