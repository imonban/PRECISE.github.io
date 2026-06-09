# FUSE-PDAC — NIH R01CA289249

**Multimodal AI Fusion Model for Early Detection of Pancreatic Cancer**

[![NIH](https://img.shields.io/badge/NIH-R01CA289249-blue?style=flat-square)](https://prevention.cancer.gov/funding-and-grants/funded-grants/R01CA289249)
[![Mayo Clinic](https://img.shields.io/badge/Institution-Mayo%20Clinic-red?style=flat-square)](https://www.mayo.edu)
[![ASU](https://img.shields.io/badge/Institution-Arizona%20State%20University-gold?style=flat-square)](https://scai.engineering.asu.edu)

---

## Overview

This repository hosts the GitHub Pages site for **FUSE-PDAC**, an NCI-funded research project developing the **PRECISE** model (**P**anc**RE**as **C**ancer mult**I**modal ri**S**k pr**E**diction).

PDAC (pancreatic ductal adenocarcinoma) accounts for 90% of pancreatic cancers and carries a ~12% 5-year survival rate — largely because over 85% of cases are diagnosed at late, unresectable stages. FUSE-PDAC addresses this by fusing pre-cancerous CT imaging biomarkers with longitudinal EMR data via a graph neural network to enable opportunistic, equitable early-detection screening.

**Grant:** R01CA289249 · National Cancer Institute  
**Period:** September 2024 – August 2029  
**PI:** Imon Banerjee, PhD · Mayo Clinic & Arizona State University

---

## Project Site

🌐 **[https://imonban.github.io/PRECISE](https://imonban.github.io/PRECISE)**

---

## Specific Aims

| Aim | Focus |
|-----|-------|
| **Aim 1** | Extract and validate pre-cancerous CT imaging biomarkers (pancreas texture, ductal morphology, vascular geometry) |
| **Aim 2** | Develop PRECISE: a fair, graph-based multimodal risk model fusing CT + EMR via GNN with adversarial debiasing |
| **Aim 3** | Prospective multi-site validation and deployment via Epic FHIR/CDS Hooks |

---

## Team

- **Imon Banerjee, PhD** — PI, Mayo Clinic & ASU


---

## Repository Structure

```
fuse-pdac/
├── index.html          # Main GitHub Pages site
├── _config.yml         # Jekyll/GitHub Pages config
├── README.md           # This file
└── .nojekyll           # Disables Jekyll processing (pure HTML)
```

---

## Contact

**Imon Banerjee, PhD**  
Department of Radiology & AI and Informatics  
Mayo Clinic, Scottsdale, AZ 85259  
📧 Banerjee.Imon@mayo.edu

---

## Acknowledgment

*This project is supported by the National Cancer Institute of the National Institutes of Health under Award Number R01CA289249. The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIH.*
