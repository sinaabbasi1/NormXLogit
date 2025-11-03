# <p align="center">NormXLogit</p>

<h3 align="center">
  <p> NormXLogit: The <u>Head-on-Top</u> Never Lies</p>
</h3>

<p align="center">
  <!-- [![arXiv](https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg)](https://arxiv.org/abs/2411.16252) -->
  <!-- <a href="https://arxiv.org/abs/2411.16252"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-1234.56789-b31b1b.svg"></a> -->
  <!-- <a href="https://aclanthology.org/2025.emnlp-main.1769/" style="line-height: 0;"><img src="http://img.shields.io/badge/ACL%20Anthology-paper-B31B1B.svg" style="display: block; margin: 0;"/></a> -->
  <a href="https://aclanthology.org/2025.emnlp-main.1769/"><img alt="Paper" src="https://img.shields.io/badge/EMNLP%202025-Paper-2C4F7C?logo=data:image/png;base64,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&style=flat"></a>
  <a href="./NormXLogit_2025_Slides.pdf"><img alt="Slides" src="https://img.shields.io/badge/​-Slides-FFBB00?logo=airplayvideo&logoColor=FFBB00&style=flat"></a>
  <a href="./NormXLogit_2025_Poster.pdf"><img alt="Poster" src="https://img.shields.io/badge/​-Poster-A493E7?logo=diagramsdotnet&logoColor=A493E7&style=flat"></a>

  ![EMNLP 2025](./EMNLP2025_main-logo.png)
</p>

## Abstract

> <div align="justify"> With new large language models (LLMs) emerging frequently, it is important to consider the potential value of model-agnostic approaches that can provide interpretability across a variety of architectures. While recent advances in LLM interpretability show promise, many rely on complex, model-specific methods with high computational costs. To address these limitations, we propose NormXLogit, a novel technique for assessing the significance of individual input tokens. This method operates based on the input and output representations associated with each token. First, we demonstrate that the norm of word embeddings can be utilized as a measure of token importance. Second, we reveal a significant relationship between a token’s importance and how predictive its representation is of the model’s final output. Extensive analyses indicate that our approach outperforms existing gradient-based methods in terms of faithfulness and offers competitive performance compared to leading architecture-specific techniques.
</div>

## Citation
If you found this work useful, please consider citing our paper:
```bibtex
@inproceedings{abbasi-etal-2025-normxlogit,
    title = "{N}orm{XL}ogit: The Head-on-Top Never Lies",
    author = "Abbasi, Sina  and
      Modarres, Mohammad Reza  and
      Pilehvar, Mohammad Taher",
    editor = "Christodoulopoulos, Christos  and
      Chakraborty, Tanmoy  and
      Rose, Carolyn  and
      Peng, Violet",
    booktitle = "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.emnlp-main.1769/",
    pages = "34914--34935",
    ISBN = "979-8-89176-332-6",
    abstract = "With new large language models (LLMs) emerging frequently, it is important to consider the potential value of model-agnostic approaches that can provide interpretability across a variety of architectures. While recent advances in LLM interpretability show promise, many rely on complex, model-specific methods with high computational costs. To address these limitations, we propose NormXLogit, a novel technique for assessing the significance of individual input tokens. This method operates based on the input and output representations associated with each token. First, we demonstrate that the norm of word embeddings can be utilized as a measure of token importance. Second, we reveal a significant relationship between a token{'}s importance and how predictive its representation is of the model{'}s final output. Extensive analyses indicate that our approach outperforms existing gradient-based methods in terms of faithfulness and offers competitive performance compared to leading architecture-specific techniques."
}
```
