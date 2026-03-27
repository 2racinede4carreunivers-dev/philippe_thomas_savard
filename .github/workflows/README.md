# Dépôt *philippe_thomas_savard*

Ce dépôt contient le document LaTeX principal de Philippe Thomas Savard ainsi que l’infrastructure nécessaire pour assurer une compilation reproductible, légère et vérifiable.

##  Objectif du dépôt
- Centraliser le document LaTeX principal
- Générer automatiquement un PDF propre et stable
- Produire une attestation cryptographique SHA‑256 garantissant l’intégrité du fichier
- Maintenir un historique clair des mises à jour via `CHANGELOG.md`

##  Fonctionnement du workflow
Un workflow GitHub Actions compile automatiquement le fichier `.tex` à chaque mise à jour du dépôt :

1. Installation d’une version minimale de TeX Live  
2. Compilation du document en PDF  
3. Génération d’une attestation SHA‑256  
4. Mise à jour automatique du `CHANGELOG.md`  
5. Commit et push des fichiers générés

Ce mécanisme assure une chaîne de production transparente, reproductible et vérifiable.

##  Fichiers importants
- `main.tex` — Document LaTeX principal  
- `main.pdf` — PDF généré automatiquement  
- `ATTESTATION_SHA256.txt` — Empreinte cryptographique du PDF  
- `CHANGELOG.md` — Historique des mises à jour  
- `.github/workflows/latex-build.yml` — Workflow de compilation automatisée

---

Si tu veux, je peux aussi te préparer :

- une version plus longue et détaillée du README  
- un badge GitHub “PDF généré automatiquement”  
- une section “Comment contribuer”  
- une section “Structure du projet”  

Tu me dis ce que tu préfères et je te le prépare.