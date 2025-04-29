# Humanfootprint_KOR

**Spatial Heterogeneity Patterns Along the Human Footprint Gradient and Their Ecological Implications: A Case Study in South Korea**

## Introduction
This repository provides datasets related to the study of spatial heterogeneity along human footprint (HF) gradients in South Korea. The study quantifies how human activities influence landscape patterns and biodiversity, using a combination of spatial metrics and machine learning approaches.

This project supports the quantitative analysis of human impacts on ecosystems and proposes strategies for ecological conservation in human-modified landscapes.

The related research has been accepted for publication in *Ecological Indicators*:

> **Title:** Spatial Heterogeneity Patterns Along the Human Footprint Gradient and Their Ecological Implications: A Case Study in South Korea  
> **Authors:** Kyoung-Ho Kim, Minkyu Park, Taeho Park, Donghae Baek, Gyobeom Kim, Namjoo Heo, Dong Jun Chun

## Dataset
- **Human Footprint (HF) Map:** National-scale HF data of South Korea at 1 km² resolution.

### Spatial Heterogeneity Metrics
- GLCM metrics (contrast, entropy, dissimilarity, etc.)
- Local spatial association metrics (Local Moran’s I, Getis-Ord Gi*, ELSA)

### Ecological Indicators
- Forest patch number
- Mammal species richness
- Protected area coverage

The dataset was generated following globally standardized HF mapping methods (Venter et al., 2016) and adapted for South Korean environmental conditions.

## Files
- `HF_SK_1km_Resolution.csv`: Human Footprint & Spatial Heterogeneity Data (1 km resolution)
- `LICENSE`: GPL-3.0 License
- `.gitignore`: Git ignore settings

## Key Findings
- Three distinct landscape zones were identified:
  - **Urbanized zones** (low spatial heterogeneity)
  - **Transitional zones** (high spatial heterogeneity, biodiversity hotspots)
  - **Natural zones** (moderate spatial heterogeneity)

- Moderate levels of human activities can sustain higher biodiversity.
- Machine learning models with spatial heterogeneity inputs improved ecological prediction accuracy compared to HF intensity-only models.

## License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0).  
Please refer to the `LICENSE` file for more details.
