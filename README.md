# Hybrid-Hierarchical Fashion Graph Attention Network for Compatibility-Oriented and Personalized Outfit Recommendation

**Authors:** Sajjad Saed, Babak Teimourpour*

**Affiliation:** Department of Information Technology Engineering, Faculty of Industrial and Systems Engineering, Tarbiat Modares University (TMU), Tehran, Iran  

<p align="center">
  <img src="Hybrid-Hierarchical Fashion Graph Attention Network.png" alt="Scheme of the Proposed FGAT Model" width="600"/>
</p>

This repository contains the implementation of **FGAT**, a Hybrid Hierarchical Fashion GAT model for Compatibility-Oriented and Personalized Outfit Recommendation proposed in our paper:
> Saed, S., & Teimourpour, B. (2025). Hybrid-Hierarchical Fashion Graph Attention Network for Compatibility-Oriented and Personalized Outfit Recommendation (No. arXiv:2508.11105). arXiv. https://doi.org/10.48550/arXiv.2508.11105
---

## 📌 Abstract
The rapid expansion of the fashion industry and the growing variety of products have made it increasingly challenging for users to identify compatible items on e-commerce platforms. Effective fashion recommendation systems are therefore crucial for filtering irrelevant options and suggesting suitable ones. However, simultaneously addressing outfit compatibility and personalized recommendations remains a significant challenge, as these aspects are typically treated independently in existing studies, thereby overlooking the complex interactions between items and user preferences. This research introduces a new framework named FGAT, which leverages a hierarchical graph representation together with attention mechanisms to address this problem. The framework constructs a three-tier graph of users, outfits, and items, integrating visual and textual features to jointly model outfit compatibility and user preferences. By dynamically weighting node importance during representation propagation, the graph attention mechanism captures key interactions and produces precise embeddings for both user preferences and outfit compatibility. Evaluated on the POG dataset, FGAT outperforms strong baselines such as HFGN, achieving notable improvements in accuracy, precision, hit ratio (HR), recall, and NDCG. These results demonstrate that combining multimodal visual–textual features with a hierarchical graph structure and attention mechanisms significantly enhances the effectiveness and efficiency of personalized fashion recommendation systems.  

> **✨ Key Contribution:
>  
> **Proposing a novel hybrid-hierarchical graph attention framework**
>  
> **Effectively fusing multimodal features (images, descriptions, and interaction structures) to enhance representation learning in recommendation**
>  
> **Category co-occurrence guides dynamic weighting across item relationships**
>  
> ** Our model achieved **HR@10=0.4286** ,**Recall@10=0.1580** ,**Precision@10=0.4424** ,**NDCG@10=0.1340** ,**accuracy=89.56%** on the POG dataset, surpassing existing benchmarks.

---

## 👩‍💻 Authors  
**Sajjad Saed**  
<p align="left">
  <a href="https://www.linkedin.com/in/sajjad-saed-845908125/" target="_blank">
    <img src="https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=linkedin">
  </a>  
  <a href='https://scholar.google.com/citations?user=4xT5JlQAAAAJ&hl=en' target="_blank">
    <img alt='GoogleScholar' src='https://img.shields.io/badge/Scholar-100000?style=flat&logo=GoogleScholar&logoColor=white&color=0181FF'>
  </a>
  <a href="https://www.researchgate.net/profile/Sajjad-Saed" target="_blank">
    <img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=ResearchGate&logoColor=white">
  </a>
    <a href="mailto:ssaed.89@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white">
  </a>
</p>

**Dr.Babak Teimourpour**
<p align="left">
  <a href="https://www.linkedin.com/in/babak-teimourpour-7877482b/" target="_blank">
    <img src="https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=linkedin">
  </a>  
  <a href='https://scholar.google.com/citations?user=Hb0DMrUAAAAJ&hl=en' target="_blank">
    <img alt='GoogleScholar' src='https://img.shields.io/badge/Scholar-100000?style=flat&logo=GoogleScholar&logoColor=white&color=0181FF'>
  </a>
  <a href="https://www.researchgate.net/profile/Babak-Teimourpour" target="_blank">
    <img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=ResearchGate&logoColor=white">
  </a>
</p>
---

## 📊 Performance

| **Model**       |  **NDCG@10** | **Precision@10** | **Recall@10** |   **HR@10**  |
| :-------------- | :----------: | :--------------: | :-----------: | :----------: |
| FPITF           |    0.0420    |      0.1121      |     0.0183    |    0.1006    |
| FHN             |    0.0490    |      0.1192      |     0.0208    |    0.1109    |
| MF              |    0.0872    |      0.2391      |     0.0434    |    0.2121    |
| VBPR            |    0.0949    |      0.2481      |     0.0449    |    0.2201    |
| NGCF            |    0.1143    |      0.3104      |     0.0554    |    0.2619    |
| HFGN            |    0.1241    |      0.3390      |     0.1265    |    0.3328    |
| DTNM            |    0.1813    |      0.1654      |     0.0625    |       —      |
| Try-On-CM       |       —      |         —        |       —       |    0.2900    |
| RankBPR         |       —      |         —        |  ***0.1921*** |       —      |
| BCDSVD++        |    0.1666    |      0.1483      |     0.0569    |       —      |
| BPR             |    0.2633    |      0.2410      |     0.0559    |       —      |
| LightGCN        |    0.2882    |      0.2632      |     0.1015    |       —      |
| Hg-PDC          | ***0.3532*** |      0.3080      |     0.1402    |       —      |
| **FGAT (Ours)** |    0.1340    |   ***0.4424***   |     0.1580    | ***0.4286*** |


| **Model**       |    **AUC**   | **Accuracy** |
| :-------------- | :----------: | :----------: |
| SiameseNet      |    0.7087    |    0.5039    |
| Style2Vec       |   0.7321  |    0.6113    |
| Bi-LSTM         |    0.7840    |    0.6384    |
| FOM             |    0.8609    |    0.6879    |
| FHN             |    0.8942    |    0.7422    |
| FaTrans-Multi   |   0.7852  |    0.7760    |
| NGNN            |    0.8381    |    0.8422    |
| HFGN            |    0.8750    |    0.8797    |
| **FGAT (Ours)** | ***0.8974*** | ***0.8956*** |

| **Metric**   | **HFGN (Baseline)** | **FGAT (Ours)** | **Improvement (%)** |
| :----------- | :-----------------: | :-------------: | :-----------------: |
| HR@10        |        0.3328       |      0.4286     |    **28.8 %**    |
| Recall@10    |        0.1265       |      0.1580     |    **25.0 %**    |
| Precision@10 |        0.3390       |      0.4424     |    **30.5 %**    |
| NDCG@10      |        0.1241       |      0.1340     |    **8.0 %**    |
| Accuracy     |        0.8797       |      0.8956     |    **1.81 %**    |

---

## 🚀Features
- Three-level user/outfit/item hierarchical graph
- Multimodal item embeddings (ResNet-152 visual + BERT textual)
- Category co-occurrence priors + attention-based propagation
- Joint training for compatibility and personalized outfit recommendation
---

## 📂 Datasets

The datasets of the paper POG:
https://drive.google.com/drive/folders/1xFdx5xuNXHGsUVG2VIohFTXf9S7G5veq

This project uses the **Fashion-MNIST** dataset, a widely-used benchmark dataset for clothing image classification.  

- **Description:** Fashion-MNIST consists of **70,000 grayscale images** of fashion items across **10 categories**, with **28x28 pixel** resolution.  
- **Train/Test Split:** 60,000 training images and 10,000 test images.  
- **Source:** Directly available via **Keras datasets**, automatically downloaded when using:

```python
from tensorflow.keras.datasets import fashion_mnist
(x_train, y_train), (x_test, y_test) = fashion_mnist.load_data()
```

---

## 📚Citation
If you use the datasets or findings from our paper, please cite [our paper](https://ieeexplore.ieee.org/abstract/document/10533341) in your work:

```bibtex
@INPROCEEDINGS{10533341,
  author={Saed, Sajjad and Teimourpour, Babak and Kalashi, Kamand and Soltanshahi, Mohammad Ali},
  booktitle={2024 10th International Conference on Web Research (ICWR)}, 
  title={An Efficient Multiple Convolutional Neural Network Model (MCNN-14) for Fashion Image Classification}, 
  year={2024},
  volume={},
  number={},
  pages={13-21},
  keywords={Computational modeling;Clothing;Computer architecture;Search engines;Benchmark testing;Feature extraction;Computational efficiency;Deep Learning;Image Classification;Multiple Convolutional Neural Networks;Fashion-MNIST},
  doi={10.1109/ICWR61162.2024.10533341}}
```

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

If you use this repository, please mention the original GitHub repository by linking to [MCNN-14-Fashion-Image-Classification](https://github.com/Kalashi-Saed-Collaborations/MCNN-14-Fashion-Image-Classification). This helps support the project and acknowledges the contributors.

