# OpenSkillsmd : Redéfinir l'Évolution des Agents IA

[English](./README.md) | [简体中文](./README.zh.md) | [日本語](./README.ja.md) | [Français](./README.fr.md)

OpenSkillsmd est une infrastructure open-source pour les compétences des Agents IA. Nous sommes à la fois un centre de **distribution (Docker Hub)** et une **encyclopédie mondiale (Wikipedia)** de l'intelligence des Agents.

---

## 🌟 Notre Vision

### 📦 Distribution Efficace (Le Docker Hub)
Grâce au protocole standardisé `skill.md`, nous permettons le `pull` et le `push` des compétences. Les développeurs peuvent télécharger instantanément des compétences certifiées pour étendre les capacités de leurs Agents.

### 📖 Connaissance Collaborative (La Wikipedia)
Chaque `skill.md` est une distillation d'intelligence. Nous encourageons la communauté à itérer et affiner les documents, rendant les instructions et les définitions d'outils structurées et transparentes.

### 📊 Évaluation Objective (Le Juge)
Piloté par l'IA, notre système d'évaluation automatique note les compétences selon plusieurs dimensions (qualité, stabilité, adaptabilité). Seules les meilleures compétences reçoivent la "Certification Officielle".

### 🚀 Slogan
> "Téléchargez des compétences de qualité, éditez le futur des Agents."

---

## 📂 Architecture des Dépôts

| Dépôt | Rôle | Description | Vision |
| :--- | :--- | :--- | :--- |
| **`skillsmd`** | **CLI** | Outil binaire supportant `pull`, `push` et `run`. | Productivité |
| **`skillsmd-hub`** | **Registry** | Backend pour le versionnage, l'API et les métadonnées. | Distribution |
| **`skillsmd-wiki`** | **Contenu** | Bibliothèque de `skill.md` classée par catégories. | Connaissance |
| **`skillsmd-judge`** | **Évaluateur** | Moteur de notation et de certification basé sur l'IA. | Qualité |
