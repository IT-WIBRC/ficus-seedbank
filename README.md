# 🌿 Ficus Seedbank (Dépôt de Contributions)

Bienvenue dans l'espace collaboratif de **ficus-quiz** ! 🚀

Ce dépôt permet aux collaborateurs de créer, relire et valider les questions et quiz avant leur intégration officielle dans l'application. Initialement conçu pour le développement web, le projet s'étend désormais à de nombreux domaines (développement mobile, médecine, etc.).

## 📂 Structure du Répertoire

*   `/propositions/` : Pour soumettre des questions isolées (1 fichier `.md` par question).
*   `/quizzes/` : Pour assembler des séries de questions validées en quiz complets.
*   `/templates/` : Les modèles à copier-coller pour vos propositions.

---

## ✍️ Comment contribuer ?

1. Allez dans le dossier `/propositions/`.
2. Créez un fichier Markdown en suivant cette convention : `domaine-categorie-motcle.md`
   *(Exemples : `devweb-accessibility-wcag.md`, `mobile-android-compose.md`, `medecine-anatomie-coeur.md`)*.
3. Copiez-collez le contenu de `/templates/template-question.md` et remplissez-le.

### 📊 Les Niveaux de Difficulté
Lors de la création, vous devez attribuer un niveau de difficulté :
*   `debutant` : Concepts de base, fondamentaux.
*   `intermediaire` : Pratique courante, logique plus poussée.
*   `avance` : Cas d'usage complexes, expertise, normes pointues.

### 🔄 Le Cycle de vie (`status`)
*   `draft` (Brouillon) : Travail en cours.
*   `review` (En relecture) : Prêt pour les retours des collaborateurs.
*   `approved` (Validé) : Prêt à être intégré dans l'application `ficus-quiz`.

---

## 🛠️ Règles d'or pour une bonne question
*   **Explication obligatoire :** Une brève explication doit toujours accompagner la réponse pour permettre à l'utilisateur de comprendre son erreur et d'apprendre.
*   **Lien de documentation :** Fournissez toujours un lien vers une documentation officielle ou une source fiable pour permettre un approfondissement.
