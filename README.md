# ⟐ZORANCORE⟐ – Flat Repo

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE.md)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

---

## 📖 Description
Référentiel **plat** pour l'orchestration ZORANCORE :  
**spécifications, pipelines et code directement à la racine** pour les hubs d'IA et les agents automatisés.

Ce dépôt est pensé pour être léger et lisible par les IA, sans sous-dossiers complexes.

---

## 📑 Contenu
- **Spécifications** → `SAFETY_RULES.yaml`, `POLICY_GUARD.yaml`, `NUMERIC_VALIDATION.yaml`, `GEO_PHARE.yaml`  
- **Pipelines** → `policy_guard_pipeline.yaml`, `streaming_pipeline.yaml`, `triple_check_pipeline.yaml`  
- **Code principal** → `orchestrator.py`, `verifier.py`, `numeric_guard.py`, `world_model_stub.py`  
- **Utilitaires** → `sbom_tools.py`, `cosign_stub.py`  
- **Tests** → `test_policy_guard.py`, `test_numeric_validation.py`, `test_geophare.py`  
- **Documents** → `whitepaper.md`, `zenodo.md`  

---
python orchestrator.pycat SAFETY_RULES.yaml
## ⚖️ Licences
⟐ZORANCORE⟐ est distribué sous un **modèle de licence double** :  

- **MIT** → par défaut, pour les injecteurs et l'adoption générale par la communauté.  
- **Apache 2.0** → pour les déploiements en entreprise/serveur nécessitant une gouvernance renforcée.  

Les deux licences coexistent. Le choix dépend du contexte d’usage.  

---

## 🔗 DOI / Zenodo
Ce référentiel sera connecté à **Zenodo** pour l’archivage et la citation permanents.  
👉 Remplacez `XXXXXXX` dans le badge DOI ci-dessus une fois que Zenodo aura généré le DOI.  

---

## 🚀 Utilisation
Cloner le dépôt :  
```bash
git clone https://github.com/Zoran-IA-Mimetique/ZORANCORE-flat.git
cd ZORANCORE-flatcat SAFETY_RULES.yaml
