# Hybrid-Hierarchical Fashion Graph Attention Network for Compatibility-Oriented and Personalized Outfit Recommendation

**Authors:** Sajjad Saed, Babak Teimourpour*

**Affiliation:** Department of Information Technology Engineering, Faculty of Industrial and Systems Engineering, Tarbiat Modares University (TMU), Tehran, Iran  

<p align="center">
  <img src="Hybrid-Hierarchical Fashion Graph Attention Network.png" alt="Scheme of the Proposed FGAT Model" width="600"/>
</p>

This repository contains the implementation of **FGAT**, a Hybrid Hierarchical Fashion GAT model for Compatibility-Oriented and Personalized Outfit Recommendation proposed in our paper:
> Saed, S., & Teimourpour, B. (2025). Hybrid-Hierarchical Fashion Graph Attention Network for Compatibility-Oriented and Personalized Outfit Recommendation (No. arXiv:2508.11105). arXiv. https://doi.org/10.48550/arXiv.2508.11105
> 
> (Saed & Teimourpour, 2025) [*“Hybrid-Hierarchical Fashion Graph Attention Network for Compatibility-Oriented and Personalized Outfit Recommendation.”*]([https://ieeexplore.ieee.org/abstract/document/10533341](https://doi.org/10.48550/arXiv.2508.1110)).
> 
> Saed et al. [*“An Efficient Multiple Convolutional Neural Network Model (MCNN-14) for Fashion Image Classification.”*](https://ieeexplore.ieee.org/abstract/document/10533341). ICWR2024

---

## 📌 Abstract
The transformation of fashion through online platforms has spurred a need for high-quality clothing search engines, facilitating seamless product discovery for global consumers. However, this transition has brought forth challenges in categorization and description standards among retailers and search engines, stemming from the inherent complexity and variability of fashion items. To address these challenges, deep learning techniques like Multiple Convolutional Neural Networks (MCNNs) have gained prominence in the fashion industry. We propose **MCNN-14**, a novel multiple-CNN architecture that balances superior classification accuracy with computational efficiency.  

> **✨ Key Contribution:** Our model achieved **93.08% accuracy** on the Fashion-MNIST dataset, surpassing existing benchmarks.

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

**Kamand Kalashi**  
 <p align="left">
  <a href="https://www.linkedin.com/in/kamand-kalashi-0696b1199/" target="_blank">
    <img src="https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=linkedin">
  </a>  
  <a href='https://scholar.google.com/citations?user=Rjiq7qUAAAAJ&hl=en' target="_blank">
    <img alt='GoogleScholar' src='https://img.shields.io/badge/Scholar-100000?style=flat&logo=GoogleScholar&logoColor=white&color=0181FF'>
  </a>
  <a href="https://www.researchgate.net/profile/Kamand-Kalashi" target="_blank">
    <img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=ResearchGate&logoColor=white">
  </a>
    <a href="mailto:kalashi.kamand@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white">
  </a>
</p>

**Dr.Mohamad Ali Soltanshahi**  
 <p align="left">
  <a href="https://www.linkedin.com/in/ali-soltanshahi-61091472/" target="_blank">
    <img src="https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=linkedin">
  </a>  
  <a href='https://scholar.google.com/citations?user=WEYVvrYAAAAJ&hl=en' target="_blank">
    <img alt='GoogleScholar' src='https://img.shields.io/badge/Scholar-100000?style=flat&logo=GoogleScholar&logoColor=white&color=0181FF'>
  </a>
  <a href="https://www.researchgate.net/profile/Mohammad-Soltanshahi" target="_blank">
    <img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=ResearchGate&logoColor=white">
  </a>
</p>

---

## 📊 Performance

<div align="left">

| Model            | Accuracy (%) |
|:-----------------|:------------:|
| **CNNs [32]**    | 92.87        |
| **LSTM [33]**    | 89.00        |
| **LeNet [34]**   | 90.16        |
| **LSTMs [35]**   | 88.26        |
| **VGG [36]**     | 92.30        |
| **CNN LeNet-5 [37]** | 90.64    |
| **SVM+HOG [38]** | 88.53        |
| **ViT [39]**     | 90.98        |
| **MCNN-14 (Ours)** | **_93.08_**<br>_(SOTA)_ |

</div>

---

## 🚀Features
- Multiple CNN (MCNN-14) architecture
- Optimized for **Fashion-MNIST**
- Achieved **93.08% classification accuracy**
- Balances accuracy with computational efficiency
- Built with **TensorFlow / Keras**

---

## 📂 Datasets

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

