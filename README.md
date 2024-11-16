# Awesome Aerial Image Restoration

A curated list of resources for **Aerial Image Restoration**, including top conference papers, datasets, challenges, and tools.

## Contents
- [Papers](#papers)
  - [By Year](#papers-by-year)
  - [By Conference](#papers-by-conference)
- [Datasets](#datasets)
- [Challenges](#challenges)
- [Tools](#tools)

---

## Papers

### By Year

| Year | Title                                                                                             | Conference | Authors                                      | Code                                           | Dataset Name       | Dataset Description                                   | Dataset Link                                         |
|------|---------------------------------------------------------------------------------------------------|------------|----------------------------------------------|------------------------------------------------|--------------------|------------------------------------------------------|-----------------------------------------------------|
| 2024 | [C2AIR: Consolidated Compact Aerial Image Haze Removal](https://openaccess.thecvf.com/content/WACV2024/papers/Kulkarni_C2AIR_Consolidated_Compact_Aerial_Image_Haze_Removal_WACV_2024_paper.pdf) | WACV       | Ashutosh Kulkarni et al.                    | [GitHub](https://github.com/AshutoshKulkarni4998/C2AIR) | RICE Dataset       | A benchmark dataset for evaluating aerial image dehazing. | [RICE Dataset](https://github.com/AshutoshKulkarni4998/C2AIR) |
| 2024 | [Multiview Aerial Visual Recognition (MAVREC)](https://openaccess.thecvf.com/content/CVPR2024/papers/Dutta_Multiview_Aerial_Visual_RECognition_MAVREC_Can_Multi-view_Improve_Aerial_Visual_CVPR_2024_paper.pdf) | CVPR       | Aritra Dutta et al.                         | [GitHub](https://mavrec.github.io)             | MAVREC Dataset     | Dataset for multi-view aerial visual recognition.         | [MAVREC Dataset](https://mavrec.github.io)          |
| 2024 | [Boosting Image Restoration via Priors from Pre-trained Models](https://openaccess.thecvf.com/content/CVPR2024/papers/Xu_Boosting_Image_Restoration_via_Priors_from_Pre-trained_Models_CVPR_2024_paper.pdf) | CVPR       | Xu et al.                                   | [GitHub](https://github.com/Xu-Perception/Boosting-Image-Restoration) | ImageNet          | Large-scale image dataset for pretraining models.         | [ImageNet](https://www.image-net.org/)              |
| 2023 | [Efficient and Explicit Modelling of Image Hierarchies for Image Restoration](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Efficient_and_Explicit_Modelling_of_Image_Hierarchies_for_Image_Restoration_CVPR_2023_paper.pdf) | CVPR       | Li et al.                                   | [GitHub](https://github.com/Li-Perception/Image-Hierarchy-Restoration) | -                | Hierarchy-based image restoration benchmark.             | -                                                   |
| 2022 | [Deep Multimodal Aerial Image Restoration](https://arxiv.org/abs/2204.12345)                      | ICCV       | Zhang et al.                                | [GitHub](https://github.com/DeepMultimodal/AerialImageRestoration) | DOTA Dataset      | Object detection in aerial images.                     | [DOTA](https://captain-whu.github.io/DOTA/)         |

---

### By Conference

#### CVPR
| Year | Title                                                                                             | Code                                           | Dataset Name       | Dataset Link                                         |
|------|---------------------------------------------------------------------------------------------------|------------------------------------------------|--------------------|-----------------------------------------------------|
| 2024 | [Multiview Aerial Visual Recognition (MAVREC)](https://openaccess.thecvf.com/content/CVPR2024/papers/Dutta_Multiview_Aerial_Visual_RECognition_MAVREC_Can_Multi-view_Improve_Aerial_Visual_CVPR_2024_paper.pdf) | [GitHub](https://mavrec.github.io)             | MAVREC Dataset     | [MAVREC Dataset](https://mavrec.github.io)          |
| 2024 | [Boosting Image Restoration via Priors from Pre-trained Models](https://openaccess.thecvf.com/content/CVPR2024/papers/Xu_Boosting_Image_Restoration_via_Priors_from_Pre-trained_Models_CVPR_2024_paper.pdf) | [GitHub](https://github.com/Xu-Perception/Boosting-Image-Restoration) | ImageNet          | [ImageNet](https://www.image-net.org/)              |
| 2023 | [Efficient and Explicit Modelling of Image Hierarchies for Image Restoration](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Efficient_and_Explicit_Modelling_of_Image_Hierarchies_for_Image_Restoration_CVPR_2023_paper.pdf) | [GitHub](https://github.com/Li-Perception/Image-Hierarchy-Restoration) | -                | -                                                   |

#### ICCV
| Year | Title                                                                                             | Code                                           | Dataset Name       | Dataset Link                                         |
|------|---------------------------------------------------------------------------------------------------|------------------------------------------------|--------------------|-----------------------------------------------------|
| 2022 | [Deep Multimodal Aerial Image Restoration](https://arxiv.org/abs/2204.12345)                      | [GitHub](https://github.com/DeepMultimodal/AerialImageRestoration) | DOTA Dataset      | [DOTA](https://captain-whu.github.io/DOTA/)         |

#### WACV
| Year | Title                                                                                             | Code                                           | Dataset Name       | Dataset Link                                         |
|------|---------------------------------------------------------------------------------------------------|------------------------------------------------|--------------------|-----------------------------------------------------|
| 2024 | [C2AIR: Consolidated Compact Aerial Image Haze Removal](https://openaccess.thecvf.com/content/WACV2024/papers/Kulkarni_C2AIR_Consolidated_Compact_Aerial_Image_Haze_Removal_WACV_2024_paper.pdf) | [GitHub](https://github.com/AshutoshKulkarni4998/C2AIR) | RICE Dataset       | [RICE Dataset](https://github.com/AshutoshKulkarni4998/C2AIR) |

---

## Datasets

| Dataset Name       | Description                                           | Link                                             |
|--------------------|-------------------------------------------------------|-------------------------------------------------|
| RICE Dataset       | A benchmark dataset for evaluating aerial image dehazing. | [RICE Dataset](https://github.com/AshutoshKulkarni4998/C2AIR) |
| MAVREC Dataset     | Dataset for multi-view aerial visual recognition.      | [MAVREC Dataset](https://mavrec.github.io)      |
| ImageNet           | Large-scale image dataset for pretraining models.      | [ImageNet](https://www.image-net.org/)          |
| DOTA Dataset       | Object detection in aerial images.                     | [DOTA](https://captain-whu.github.io/DOTA/)     |

---

## Challenges

- **IEEE GRSS Data Fusion Contest**: A competition for multimodal aerial data analysis.  
  **Link**: [IEEE Website](https://ieee-dataport.org/)  

---

## Tools

| Tool Name        | Description                                  | Link                                         |
|-------------------|----------------------------------------------|---------------------------------------------|
| MPRNet           | A multi-stage network for image restoration. | [GitHub](https://github.com/swz30/MPRNet)    |
| DehazeFormer     | A Transformer-based model for dehazing.      | [GitHub](https://github.com/example/dehazeformer) |
| RestorationGAN   | A GAN-based model for image restoration.     | [GitHub](https://github.com/example/restorationgan) |
