# Fei Su, PhD

**Computational Pathology & Spatial Biology | MRI & Neuroimaging Analysis**

Medical- and pathology-trained researcher with a PhD in Biomedical Imaging from the **University of Technology Sydney (UTS)**. My research combines quantitative biomedical imaging, machine learning, and rigorous evaluation to study tissue structure, molecular heterogeneity, and brain imaging. My work is organized into **two complementary research directions**.

---

## 01 · Computational Pathology

**Whole-slide imaging · Pathology foundation models · Tissue context · Spatial biology · Evidence-grounded AI**

I develop and evaluate methods that link histopathological morphology, image representations, and molecular or spatial information, with particular attention to resolution, tissue context, and reproducibility.

### Publications & manuscripts

**Published**

**[PathScaleBench: A Multidimensional Benchmark of Cross-Scale Representation Behavior and Magnification-Shift Robustness in Pathology Foundation Models](https://doi.org/10.1007/s10278-026-02354-8)**  
*Journal of Imaging Informatics in Medicine* · Published online **October 2026** · [DOI](https://doi.org/10.1007/s10278-026-02354-8) · [Code](https://github.com/Great-sophie/PathScaleBench)

**Under review**

**Resolution and Tissue Context Across Eight Pathology Foundation Models: A Controlled Field-of-View Study**  
*Computers in Biology and Medicine* · **Under Review**

### Research projects

| Repository | Focus |
| --- | --- |
| **[PathScaleBench](https://github.com/Great-sophie/PathScaleBench)** | Cross-scale representation behavior and robustness to histological magnification shift. |
| **[PathBioAgent](https://github.com/Great-sophie/PathBioAgent)** | Research prototype for evidence-driven morphology–molecular reasoning and analysis. |
| **[Spatial Omics–Histology Transfer](https://github.com/Great-sophie/spatial-omics-histology-transfer)** | Histology features, spatial transcriptomics, and graph-based modeling. |
| **[Histology Nuclei Segmentation](https://github.com/Great-sophie/histology-nuclei-segmentation)** | H&E nuclei segmentation with case-level splitting and held-out evaluation. |
| **[Clinical AI Validation](https://github.com/Great-sophie/clinical-ai-validation)** | Model discrimination, calibration, external validation, and decision-curve evaluation. |
| **[Multimodal Clinical AI](https://github.com/Great-sophie/multimodal-clinical-ai)** | Image and clinical-metadata fusion approaches. |

**Related experimental and molecular imaging:** [Organelle Thermal Signatures](https://github.com/Great-sophie/Organelle-Thermal-Signatures) · [Spatiotemporal Organelle Interactions](https://github.com/Great-sophie/Spatiotemporal-Organelle-Interactions) · [Single-Cell RNA-seq with Scanpy](https://github.com/Great-sophie/scanpy-single-cell-pbmc).

**Methods and tools:** digital pathology, WSI, quantitative microscopy, PyTorch, Vision Transformers, pathology foundation models, spatial transcriptomics, Scanpy, Squidpy, graph neural networks, and molecular imaging.

---

## 02 · MRI & Neuroimaging Analysis

**Longitudinal 3D MRI · Self-supervised learning · Brain development · Connectomics · Quantitative analysis**

I investigate temporal representations in 3D MRI and longitudinal changes in structural–functional brain network organization. Both repositories are research studies rather than clinically validated diagnostic models.

### Manuscript

**Temporally Structured Self-Distillation for Longitudinal 3D Brain MRI**  
**ICASSP 2027 · Submitted** 

### Research projects

#### [TempoDINO — Longitudinal 3D Brain MRI](https://github.com/Great-sophie/TempoDINO-Longitudinal-Brain-MRI)

Self-supervised developmental representation learning from **longitudinal non-human-primate T1-weighted 3D MRI**.

- **Dataset:** 114 MRI scans from 23 subjects; five subject-disjoint evaluation folds.
- **Approach:** 3D ResNet-18 student/EMA teacher, DINO self-distillation, temporal-ordering and relative-spacing objectives.
- **Reported locked out-of-fold results:** within-subject ordering accuracy **95.58%**, cross-subject ordering accuracy **89.79%**; downstream age-probe MAE **3.235 months**.
- **Limitations:** full independent training reproducibility and external generalization have not been established. Age prediction is a downstream probe, not the primary optimization target.

#### [TumorConnectome — Brain Tumor Connectomics](https://github.com/Great-sophie/TumorConnectome)

Exploratory analysis of **preoperative and postoperative structural–functional connectome coupling** and cognitive change using public BTC brain tumor datasets.

- **Dataset:** 63 audited SC–FC session records (36 preoperative, 27 postoperative).
- **Approach:** 68-region Desikan–Killiany SC–FC coupling, subject-level longitudinal changes, permutation and bootstrap inference.
- **Exploratory finding:** among 16 patients with matched cognitive data, change in coupling correlated with sustained-attention change (Spearman **ρ ≈ −0.585**, unadjusted **p ≈ 0.019**).
- **Limitations:** small sample, multiple-testing concerns, noncausal association; tumor-to-DK68 regional burden was not validated and is excluded from quantitative conclusions.

**Methods and tools:** NIfTI imaging, 3D MRI preprocessing, image orientation/resampling, registration QC, brain connectivity matrices, Python, PyTorch, self-supervised representation learning, and subject-level statistical evaluation.

---

## Academic Background

- **PhD in Biomedical Imaging** — University of Technology Sydney, Australia (2022–2026)
- **Master of Medicine in Clinical Pathology** — Sichuan University / West China Hospital, China (2015–2018)
- **Bachelor of Medicine** — Xinjiang Medical University, China (2009–2014)

## Connect

- **GitHub:** [Great-sophie](https://github.com/Great-sophie)
- **Research interests:** computational pathology, biomedical imaging, MRI analysis, and spatial biology.

*Publication and submission statuses are current as reported in October 2026. Project results are exploratory unless otherwise stated; no claim of clinical deployment or regulatory approval is made.*
