
[stars-img]: https://img.shields.io/github/stars/zzhangsm/Awesome-Spatial-Transcriptomics-Analysis?color=yellow
[stars-url]: https://github.com/zzhangsm/Awesome-Spatial-Transcriptomics-Analysis/stargazers
[fork-img]: https://img.shields.io/github/forks/zzhangsm/Awesome-Spatial-Transcriptomics-Analysis?color=lightblue&label=fork
[fork-url]: https://github.com/zzhangsm/Awesome-Spatial-Transcriptomics-Analysis/network/members
[ASTA-url]: https://github.com/zzhangsm/Awesome-Spatial-Transcriptomics-Analysis

# Awesome-Spatial-Transcriptomics-Analysis
Awesome-Spatial-Transcriptomics-Analysis is a comprehensive collection of spatial transcriptomics analysis works, including papers, codes, tools, and datasets🔥. We focus on cutting-edge research in spatial transcriptomics — a revolutionary technology that measures gene expression while preserving spatial information within tissues. This repository covers computational methods for spatial gene expression analysis, spatial clustering, trajectory inference, cell-cell communication, and integration with other omics data.

Any problems, please contact the zzhangsm615@gmail.com. Any other interesting papers or codes are welcome. If you find this repository useful to your research or work, it is really appreciated to star this repository.

[![GitHub stars][stars-img]][stars-url]
[![GitHub forks][fork-img]][fork-url]


## 📋 Table of Contents

- [🛠️ Tools & Software](#️-tools--software)
- [📚 Papers](#-papers)
  - [🧬 Spatial Clustering & Cell Type Identification](#-spatial-clustering--cell-type-identification)
  - [🔍 Spatial Deconvolution & Mapping](#-spatial-deconvolution--mapping)
  - [🔬 Spatial Variable Genes](#-spatial-variable-genes)
  - [🔄 Multi-slice Alignment](#-multi-slice-alignment)
  - [🛣️ Spatial Trajectory & Development](#️-spatial-trajectory--development)
  - [💬 Cell-Cell Communication](#-cell-cell-communication)
  - [📊 Benchmarking & Evaluation](#-benchmarking--evaluation)
  - [🔧 Others (Anomaly Detection, Quality Control, Data Simulation, etc.)](#-others-anomaly-detection-quality-control-data-simulation-etc)
  - [🏥 H&E To Spatial Transcriptomics](#-he-to-spatial-transcriptomics)
- [🗃️ Datasets](#️-datasets)
- [🤝 Contributing](#-contributing)
- [📧 Contact](#-contact)
- [🙏 Acknowledgments](#-acknowledgments)


## 🛠️ Tools & Software

| Tool | Language | Description | Link |
| ---- | -------- | ----------- | ---- |
| **Scanpy** | Python | Single-cell and spatial analysis | [link](https://scanpy.readthedocs.io/) |
| **Seurat** | R | Integrated spatial analysis | [link](https://satijalab.org/seurat/) |
| **Squidpy** | Python | Spatial omics analysis | [link](https://squidpy.readthedocs.io/) |
| **stLearn** | Python | Spatial transcriptomics analysis | [link](https://github.com/BiomedicalMachineLearning/stLearn) |
| **SpaSEG** | Python | Spatial transcriptomics analysis | [link](https://github.com/y-bai/SpaSEG) |

## 📚 Papers

<details>
<summary>🧬 Spatial Clustering & Cell Type Identification</summary>

| Year | Title | Venue | Method | Paper | Code |
| ---- | ----- | ----- | ------ | ----- | ---- |
| 2025 | **MAEST: accurately spatial domain detection in spatial transcriptomics with graph masked autoencoder** | Brief. Bioinform. | MAEST | [link](https://dx.doi.org/10.1093/bib/bbaf086) | TBD |
| 2025 | **Unveiling fine-scale spatial structures and amplifying gene expression signals in ultra-large ST slices with HERGAST** | Nat. Commun. | HERGAST | [link](https://www.nature.com/articles/s41467-025-59139-w) | TBD |
| 2025 | **Exploring the Latent Information in Spatial Transcriptomics Data via Multi-View Graph Convolutional Network Based on Implicit Contrastive Learning** | Adv. Sci. | STMIGCL | [link](https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/advs.202413545) | TBD |
| 2025 | **STAIG: Spatial transcriptomics analysis via image-aided graph contrastive learning for domain exploration and alignment-free integration** | Nat. Commun. | STAIG | [link](https://www.nature.com/articles/s41467-025-56276-0) | TBD |
| 2024 | **Accurate Spatial Heterogeneity Dissection and Gene Regulation Interpretation for Spatial Transcriptomics using Dual Graph Contrastive Learning** | Adv. Sci. | stDCL | [link](https://onlinelibrary.wiley.com/doi/abs/10.1002/advs.202410081) | TBD |
| 2024 | **Unsupervised spatially embedded deep representation of spatial transcriptomics** | Genome Med. | SEDR | [link](https://doi.org/10.1186/s13073-024-01283-x) | [link](https://github.com/JinmiaoChenLab/SEDR/) |
| 2024 | **A multi-view graph contrastive learning framework for deciphering spatially resolved transcriptomics data** | Brief. Bioinform. | MuCoST | [link](https://doi.org/10.1093/bib/bbae255) | TBD |
| 2024 | **Multiscale topology classifies cells in subcellular spatial transcriptomics** | Nature | TopACT | [link](https://www.nature.com/articles/s41586-024-07563-1) | [link](https://gitlab.com/kfbenjamin/topact) |
| 2023 | **Spatially informed clustering, integration, and deconvolution of spatial transcriptomics with GraphST** | Nat. Commun. | GraphST | [link](https://www.nature.com/articles/s41467-023-36796-3) | TBD |

</details>

<details>
<summary>🔍 Spatial Deconvolution & Mapping</summary>

| Year | Title | Venue | Method | Paper | Code |
| ---- | ----- | ----- | ------ | ----- | ---- |
| 2025 | **SURF: A Self-Supervised Deep Learning Method for Reference-Free Deconvolution in Spatial Transcriptomics** | Adv. Sci.  | SURF | [link](https://doi.org/10.1002/advs.202505456) | [link](https://github.com/lllsssyyyy/SURF) |
| 2025 | **Mapping cells through time and space with moscot** | Nature | Moscot | [link](https://www.nature.com/articles/s41586-024-08453-2) | [link](https://moscot-tools.org/) |
| 2025 | **High-resolution mapping of single cells in spatial context** | Nat. Commun. | CMAP |[link](https://doi.org/10.1038/s41467-025-61667-4) | [link](https://github.com/SuoLab-GZLab/CMAP) |
| 2024 | **SpaTopic: A statistical learning framework for exploring tumor spatial architecture from spatially resolved transcriptomic data** | Sci. Adv. | SpaTopic | [link](https://www.science.org/doi/10.1126/sciadv.adp4942) |  [link](https://github.com/compbioNJU/SpaTopic) |
| 2024 | **SpatialcoGCN: deconvolution and spatial information–aware simulation of spatial transcriptomics data via deep graph co-embedding** | Brief. Bioinform. | SpatialcoGCN | [link](https://doi.org/10.1093/bib/bbae130) | TBD |
| 2024 | **Dissecting tumor microenvironment from spatially resolved transcriptomics data by heterogeneous graph learning** | Nat. Commun. | stKeep | [link](https://www.nature.com/articles/s41467-024-49171-7) | TBD |
| 2024 | **Search and match across spatial omics samples at single-cell resolution** | Nat. Methods | CAST | [link](https://www.nature.com/articles/s41592-024-02410-7) | TBD |
| 2024 | **Dependency-aware deep generative models for multitasking analysis of spatial omics data** | Nat. Methods | spaVAE | [link](https://www.nature.com/articles/s41592-024-02257-y) | TBD |
| 2023 | **SPACEL: deep learning-based characterization of spatial transcriptome architectures** | Nat. Commun. | SPACEL | [link](https://www.nature.com/articles/s41467-023-43220-3) | TBD |
| 2025 | **DECIPHER for learning disentangled cellular embeddings in large-scale heterogeneous spatial omics data** | Nat. Commun. | DECIPHER | [link](https://www.nature.com/articles/s41467-025-63140-8) | TBD |
| 2025 | **CellMemory: hierarchical interpretation of out-of-distribution cells using bottlenecked transformer** | Genome Biol. | CellMemory | [link](https://doi.org/10.1186/s13059-025-03638-y) | TBD |
| 2023 | **Integrating spatial and single-cell transcriptomics data using deep generative models with SpatialScope** | Nat. Commun. | SpatialScope | [link](https://www.nature.com/articles/s41467-023-43629-w) | TBD |
| 2022 | **Spatial-ID: a cell typing method for spatially resolved transcriptomics via transfer learning and spatial embedding** | Nat. Commun. | Spatial-ID | [link](https://www.nature.com/articles/s41467-022-35288-0) | TBD |

</details>

<details>
<summary>🔬 Spatial Variable Genes</summary>

| Year | Title | Venue | Method | Paper | Code |
| ---- | ----- | ----- | ------ | ----- | ---- |
| 2025 | **Prioritizing perturbation-responsive gene patterns using interpretable deep learning** | Nat. Commun. | River | [link](https://www.nature.com/articles/s41467-025-61476-9) | [link](https://github.com/C0nc/River) |
| 2024 | **PROST: quantitative identification of spatially variable genes and domain detection in spatial transcriptomics** | Nat. Commun. | PROST | [link](https://www.nature.com/articles/s41467-024-44835-w) | TBD |
| 2024 | **SpotGF: Denoising spatially resolved transcriptomics data using an optimal transport-based gene filtering algorithm** | Cell Syst. | SpotGF | [link](https://www.cell.com/cell-systems/abstract/S2405-4712(24)00269-2) | TBD |
| 2023 | **STAMarker: determining spatial domain-specific variable genes with saliency maps in deep learning** | Nucleic Acids Res. | STAMarker | [link](https://dx.doi.org/10.1093/nar/gkad801) | TBD |

</details>

<details>
<summary>🔄 Multi-slice Alignment</summary>

| Year | Title | Venue | Method | Paper | Code |
| ---- | ----- | ----- | ------ | ----- | ---- |
| 2025 | **stClinic dissects clinically relevant niches by integrating spatial multi-slice multi-omics data in dynamic graphs** | Nat. Commun. | stClinic | [link](https://www.nature.com/articles/s41467-025-60575-x) | [link](https://github.com/cmzuo11/stClinic) |
| 2024 | **MENDER: fast and scalable tissue structure identification in spatial omics data** | Nat. Commun. | MENDER | [link](https://www.nature.com/articles/s41467-023-44367-9) | TBD |
| 2024 | **Accurate and efficient integrative reference-informed spatial domain detection for spatial transcriptomics** | Nat. Methods | IRIS |[link](https://www.nature.com/articles/s41592-024-02284-9) | [link](https://github.com/YingMa0107/IRIS) |
| 2024 | **Interpretable spatially aware dimension reduction of spatial transcriptomics with STAMP** |  Nat. Methods | STAMP | [link](https://www.nature.com/articles/s41592-024-02463-8) | [link](https://github.com/JinmiaoChenLab/scTM) |
| 2024 | **Spatiotemporal modeling of molecular holograms** | Cell | Spateo | [link](https://www.cell.com/cell/abstract/S0092-8674(24)01159-0) | [link](https://github.com/aristoteleo/spateo-release) |
| 2023 | **STAligner: Integrating spatial transcriptomics data across different conditions, technologies, and developmental stages** | Nat. Comput. Sci. | STAligner | [link](https://doi.org/10.1038/s43588-023-00528-w) | [link](https://github.com/zhanglabtools/STAligner) |
| 2023 | **Construction of a 3D whole organism spatial atlas by joint modelling of multiple slices with deep neural networks** | Nat. Mach. Intell. | STitch3D | [link](https://doi.org/10.1038/s42256-023-00734-1) | [link](https://github.com/YangLabHKUST/STitch3D) |

</details>

<details>
<summary>🛣️ Spatial Trajectory & Development</summary>

| Year | Title | Venue | Method | Paper | Code |
| ---- | ----- | ----- | ------ | ----- | ---- |
| 2025 | **spVelo: RNA velocity inference for multi-batch spatial transcriptomics data** | Genome Biol. | spVelo | [link](https://doi.org/10.1186/s13059-025-03701-8) | TBD |

</details>

<details>
<summary>💬 Cell-Cell Communication</summary>

| Year | Title | Venue | Method | Paper | Code |
| ---- | ----- | ----- | ------ | ----- | ---- |
| 2025 | **Finding spatially variable ligand-receptor interactions with functional support from downstream genes** | Nat. Commun. | SPIDER | [link](https://www.nature.com/articles/s41467-025-62988-0) | TBD |
| 2025 | **CellNEST reveals cell–cell relay networks using attention mechanisms on spatial transcriptomics** | Nat. Methods | CellNEST | [link](https://www.nature.com/articles/s41592-025-02721-3) | [link](https://github.com/schwartzlab-methods/CellNEST) |
| 2025 | **Dissecting multilayer cell–cell communications with signaling feedback loops from spatial transcriptomics data** | Genome Res. | stMLnet | [link](http://genome.cshlp.org/content/35/6/1400) | TBD |
| 2025 | **Interpretable niche-based cell‒cell communication inference using multi-view graph neural networks** | Nat. Comput. Sci. | STCase | [link](https://www.nature.com/articles/s43588-025-00809-6) | TBD |
| 2025 | **VGAE-CCI: variational graph autoencoder-based construction of 3D spatial cell–cell communication network** | Brief. Bioinform. | VGAE-CCI | [link](https://doi.org/10.1093/bib/bbae619) | TBD |
| 2024 | **Mapping cellular interactions from spatially resolved transcriptomics data** | Nat. Methods | Spacia | [link](https://www.nature.com/articles/s41592-024-02408-1) | TBD |
| 2024 | **Inferring pattern-driving intercellular flows from single-cell and spatial transcriptomics** | Nat. Methods | FlowSig | [link](https://www.nature.com/articles/s41592-024-02380-w) | TBD |
| 2023 | **Screening cell–cell communication in spatial transcriptomics via collective optimal transport** | Nat. Methods | COMMOT | [link](https://www.nature.com/articles/s41592-022-01728-4) | TBD |
| 2021 | **Inference and analysis of cell-cell communication using CellChat** | Nat. Commun. | CellChat | [link](https://www.nature.com/articles/s41467-021-21246-9) | TBD |

</details>

<details>
<summary>📊 Benchmarking & Evaluation</summary>

| Year | Title | Venue | Method | Paper | Code |
| ---- | ----- | ----- | ------ | ----- | ---- |
| 2025 | **Reusability report: Exploring the transferability of self-supervised learning models from single-cell to spatial transcriptomics** | Nat. Mach. Intell. | SSL Transfer | [link](https://www.nature.com/articles/s42256-025-01097-5) | TBD |
| 2024 |  **Benchmarking spatial clustering methods with spatially resolved transcriptomics data** | Nat. Mach. Intell. | Spatial clustering | [link](https://doi.org/10.1038/s41592-024-02215-8) | [link](https://github.com/zhaofangyuan98/SDMBench) |

</details>

<details>
<summary>🔧 Others (Anomaly Detection, Quality Control, Data Simulation, etc.)</summary>

| Year | Title | Venue | Method | Paper | Code |
| ---- | ----- | ----- | ------ | ----- | ---- |
| 2025 | **SpotSweeper: spatially aware quality control for spatial transcriptomics** | Nat. Methods | SpotSweeper | [link](https://www.nature.com/articles/s41592-025-02713-3) | TBD |
| 2024 | **GRouNdGAN: GRN-guided simulation of single-cell RNA-seq data using causal generative adversarial networks** | Nat. Commun. | GRouNdGAN | [link](https://www.nature.com/articles/s41467-024-48516-6) | TBD |
| 2024 | **Detecting anomalous anatomic regions in spatial transcriptomics with STANDS** | Nat. Commun. | STANDS | [link](https://www.nature.com/articles/s41467-024-52445-9) | TBD |

</details>

<details>
<summary>🏥 H&E To Spatial Transcriptomics</summary>

| Year | Title                                                        |  Venue  |        Method        |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :-------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2025 | **A visual–omics foundation model to bridge histopathology with spatial transcriptomics** | Nat. Methods | OmiCLIP | [link](https://www.nature.com/articles/s41592-025-02707-1)    | [link](https://github.com/GuangyuWangLab2021/Loki)  
| 2025 | **Predicting Spatial Transcriptomics from H&E Image by Pretrained Contrastive Alignment Learning** | bioRxiv | CarHE | [link](https://www.biorxiv.org/content/10.1101/2025.06.15.659438v1.abstract)    | [link](https://github.com/Jwzouchenlab/CarHE) |
| 2025 | **Gene-DML: Dual-Pathway Multi-Level Discrimination for Gene Expression Prediction from Histopathology Images** | arXiv | Gene-DML | [link](https://arxiv.org/abs/2507.14670)    | [link](https://github.com/hrlblab/Img2ST-Net) |
| 2025 | **Img2ST-Net: Efficient High-Resolution Spatial Omics Prediction from Whole Slide Histology Images via Fully Convolutional Image-to-Image Learning** | arXiv | Img2ST-Net | [link](https://arxiv.org/abs/2508.14393)    | [link](https://github.com/hrlblab/Img2ST-Net) |
| 2025 | **MV-Hybrid: Improving Spatial Transcriptomics Prediction with Hybrid State Space-Vision Transformer Backbone in Pathology Vision Foundation Models** | MICCAI Workshop | MV-Hybrid | [link](https://arxiv.org/abs/2508.00383)    | [link](https://github.com/deepnoid-ai/MVHybrid) |
| 2025 | **Diffusion Generative Modeling for Spatially Resolved Gene Expression Inference from Histology Images** | ICLR | Stem | [link](https://arxiv.org/abs/2501.15598)    | [link](https://github.com/SichenZhu/Stem)                   |
| 2025 | **Spatially resolved gene expression prediction from histology images via bi-modal contrastive learning** | NeurIPS | BLEEP | [link](https://arxiv.org/pdf/2306.01859)    | [link](https://github.com/bowang-lab/BLEEP)                   |
| 2025 | **M2ORT: Many-To-One Regression Transformer for Spatial Transcriptomics Prediction from Histopathology Images** | AAAI | M2ORT | [link](https://ojs.aaai.org/index.php/AAAI/article/view/32830/34985)    | [link](https://github.com/Dootmaan/M2ORT/) |
| 2024| **HEMIT: H&E to Multiplex-immunohistochemistry Image Translation with Dual-Branch Pix2pix Generator** | arXiv | HEMIT | [link](https://arxiv.org/abs/2403.18501)    | [link](https://github.com/BianChang/HEMIT-DATASET) |
| 2024 | **Accurate spatial gene expression prediction by integrating multi-resolution features** | CVPR | TRIPLEX | [link](https://openaccess.thecvf.com/content/CVPR2024/html/Chung_Accurate_Spatial_Gene_Expression_Prediction_by_Integrating_Multi-Resolution_Features_CVPR_2024_paper.html)    |   [link](https://github.com/NEXGEM/TRIPLEX)                   |
| 2023 | **Exemplar guided deep neural network for spatial transcriptomics analysis of gene expression prediction** | CVPR | EGN                  | [link](https://arxiv.org/abs/2210.16721)    | [link](https://github.com/Yan98/EGN)                   |
| 2022 | **Spatial transcriptomics prediction from histology jointly through transformer and graph neural networks** | BIB | Hist2ST                  | [link](https://doi.org/10.1093/bib/bbac297)    | [link](https://github.com/biomed-AI/Hist2ST)                   |
| 2021 | **Leveraging information in spatial transcriptomics to predict super-resolution gene expression from histology images in tumors** | bioRxiv | HisToGene                  | [link](https://www.biorxiv.org/content/10.1101/2021.11.28.470212v1)    | [link](https://github.com/maxpmx/HisToGene)                   |
| 2020 | **Integrating spatial gene expression and breast tumour morphology via deep learning** | Nature biomedical engineering | ST-Net                  | [link](https://www.nature.com/articles/s41551-020-0578-x)    | [link](https://github.com/bryanhe/ST-Net)                   |

</details>

## 🗃️ Datasets

| Dataset | Technology | Tissue Type | Species | Download Link | Description |
| ------- | ---------- | ----------- | ------- | ------------- | ----------- |
| **10x Visium** | Visium | Various | Human/Mouse | [link](https://www.10xgenomics.com/resources/datasets) | Official datasets from 10x Genomics |

## 🤝 Contributing

We welcome all forms of contributions! If you want to add new papers, codes, or resources, please:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

If you have any questions or suggestions, please contact us through:
- Email: zzhangsm615@gmail.com
- GitHub Issues: [Create Issue](https://github.com/zzhangsm/Awesome-Spatial-Transcriptomics-Analysis/issues)

## 🙏 Acknowledgments

Thanks to all researchers and developers who have contributed to the field of spatial transcriptomics analysis.

---

⭐ If you find this project useful, please give us a star!
