<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=58a6ff&background=FFFFFF00&center=true&vCenter=true&width=700&lines=Ali+Sayed+Ahmad;Deep+Learning+%26+Computer+Vision;Machine+Learning+%26+Data+Science;Neuromorphic+Vision+%26+Edge+AI;Time+Series+%26+Signal+Processing;ENSTA+%E2%80%93+Institut+Polytechnique+de+Paris)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ali--sayedahmad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ali-sayedahmad)
[![Email](https://img.shields.io/badge/ali.sayed%40ensta.fr-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ali.sayed@ensta.fr)
[![GitHub](https://img.shields.io/badge/GitHub-alisayedahmad-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alisayedahmad)
![Profile Views](https://komarev.com/ghpvc/?username=alisayedahmad&style=for-the-badge&color=58a6ff&label=PROFILE+VIEWS)

</div>

---

## 🧠 À propos

```python
class AliSayedAhmad:
    def __init__(self):
        self.school     = "ENSTA Bretagne – Institut Polytechnique de Paris"
        self.degree     = "Ingénieur IA & Systèmes d'Observation"
        self.current    = "PFE @ Schneider Electric Hive R&D — Vision Neuromorphique"
        self.focus      = ["Deep Learning", "Computer Vision", "Edge AI", "Neuromorphic Sensing"]
        self.languages  = {"French": "C1", "English": "C1", "Arabic": "native", "German": "A2"}

    def now(self):
        return "Développement de pipelines vision événementielle pour la maintenance prédictive industrielle"
```

Ingénieur formé à l'**ENSTA Bretagne – IP Paris**, je construis des systèmes de vision intelligents à l'intersection de la recherche et du produit : caméras événementielles, vision temps réel, déploiement embarqué. Du prototype à la production.

---

## 💼 Expérience

**`03/2026 → 09/2026`** &nbsp;|&nbsp; 🏭 **Schneider Electric Hive R&D** — *Ingénieur R&D, Vision Neuromorphique (PFE)*
> Pipeline caméra événementielle Prophesee · Estimation de vitesse de rotation moteurs · Détection de défauts mécaniques · Analyse de signatures dynamiques événementielles

**`05/2025 → 08/2025`** &nbsp;|&nbsp; 🎧 **OSO-AI, Brest** — *Ingénieur ML, Traitement Audio*
> Clustering audio non supervisé (MobileNet V3 + spectrogrammes mel) · **−40% de temps d'annotation** · Reconnaissance d'émotions zero-shot (CLAP) · Déploiement Streamlit en production

**`06/2024 → 08/2024`** &nbsp;|&nbsp; ⚡ **Candia, Beyrouth** — *Ingénieur ML, Optimisation Énergétique*
> Prévision sur 17 000+ capteurs IoT · Production solaire & demande électrique · **−11% de consommation carburant** diesel · Dashboard temps réel

---

## 🚀 Projets

<table>
<tr>
<td width="50%" valign="top">

### 🎯 SIAMOIS — Reconnaissance SAR
**ENSTA Bretagne / Lab-STICC · Défense**

Réseaux siamois contrastifs & triplets sur MSTAR (10 classes véhicules militaires, imagerie radar).

- 📈 `95.18%` → **`99.02%`** de précision
- 🔬 57 expériences · 6 axes hyperparamétriques · 3 seeds
- 🏆 Batch All mining surpasse Batch Hard de **+1.39%** en few-shot

`PyTorch` `Meta-learning` `Transfer Learning` `SAR`

</td>
<td width="50%" valign="top">

### 🐋 Classification Vocalisations Baleines
**bioDCASE · 1 292h d'enregistrements antarctiques**

7 classes de vocalisations (baleines bleues & rorquals) à partir de spectrogrammes STFT.

- 📈 XGBoost : **88% accuracy**, F1 ≥ 0.90
- 🎵 6 007 fichiers WAV · 2005–2017
- ⚙️ Pipeline SVM / RF / XGBoost / NN + clustering

`scikit-learn` `XGBoost` `librosa` `Streamlit`

[![Repo](https://img.shields.io/badge/GitHub-antarctic--whale-181717?style=flat-square&logo=github)](https://github.com/alisayedahmad/antarctic-whale-vocalization-classification)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛰️ Segmentation Satellite (SpaceNet 2/3)
**Bâtiments & routes · Imagerie géospatiale**

Pipeline end-to-end de segmentation sémantique sur imagerie satellite.

- 🏗️ U-Net (ResNet34/50) · DeepLabV3+ (ResNet101)
- 📐 Tiling 512×512 · blending · export GeoTIFF/GeoJSON
- 🎯 mIoU ≥ 0.75 (bâtiments) · APLS (routes)

`PyTorch Lightning` `rasterio` `geopandas` `Docker`

[![Repo](https://img.shields.io/badge/GitHub-sat--segmentation-181717?style=flat-square&logo=github)](https://github.com/alisayedahmad/SIS)

</td>
<td width="50%" valign="top">

### ⚽ Analyse Football Temps Réel
**Tracking multi-objets · Broadcast AI**

Détection et suivi de joueurs et ballon en temps réel depuis flux vidéo.

- ⚡ **45–60 FPS** · mAP50 : **0.85+**
- 📊 Vitesse, possession, heatmaps
- 🚀 Déploiement ONNX / TensorRT embarqué

`YOLOv8` `DeepSORT` `TensorRT` `ONNX`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 Assistant RAG Algorithmique
**LLM Local · Aide à la résolution de problèmes**

Pipeline RAG pour l'analyse de problèmes algorithmiques et la génération de hints progressifs.

- 🧠 CodeBERT + ChromaDB + **Mistral-7B** (local)
- 🎯 Précision top-3 : **78%**
- 🔐 Exécution sandbox automatisée

`RAG` `LangChain` `ChromaDB` `Mistral` `CodeBERT`

</td>
<td width="50%" valign="top">

### 🏭 Vision Neuromorphique Industrielle
**Schneider Electric · En cours (2026)**

Détection de défauts sur moteurs électriques par caméra événementielle Prophesee.

- 👁️ Event Frame · Voxel Grid · Time Surface
- 🔧 Balourd · désalignement · usure roulements
- ⚡ Traitement de flux asynchrones temps réel

`Event Camera` `PyTorch` `Prophesee SDK` `Edge AI`

</td>
</tr>
</table>

---

## 🛠️ Stack Technique

**Deep Learning & Vision**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Lightning](https://img.shields.io/badge/Lightning-792EE5?style=flat-square&logo=lightning&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Neuromorphique & Edge**

![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

**ML & Data**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AC7?style=flat-square&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**MLOps & Déploiement**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Langages**

![Python](https://img.shields.io/badge/Python%20(expert)-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=alisayedahmad&theme=github_dark" height="160"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=alisayedahmad&theme=github_dark" height="160"/>

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=alisayedahmad&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D)](https://git.io/streak-stats)

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=alisayedahmad&theme=react-dark&hide_border=true&area=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🎓 Formation & Certifications

| Diplôme | École | Période |
|---------|-------|---------|
| Ingénieur IA & Systèmes d'Observation | **ENSTA Bretagne – Institut Polytechnique de Paris** | 2024 – 2026 |
| Ingénieur Électrique & Télécoms (Double diplôme) | Université Libanaise | 2020 – 2026 |

**Certifications** : Machine Learning & Deep Learning Specializations *(DeepLearning.AI · Andrew Ng)* · PyTorch Professional Certificate · Generative AI with LangChain & HuggingFace · MLOps Bootcamp

---

<div align="center">

**Disponible pour un CDI en Deep Learning / Computer Vision · Paris & remote**

[![LinkedIn](https://img.shields.io/badge/Me+contacter-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ali-sayedahmad)
[![Email](https://img.shields.io/badge/ali.sayed%40ensta.fr-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ali.sayed@ensta.fr)

*"Build systems that see, think, and act — at the edge of what's possible."*

</div>
