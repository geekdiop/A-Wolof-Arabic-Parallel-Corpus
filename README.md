# 🌍 Wolof-Arabic Parallel Corpus for Machine Translation

> A high-quality, sentence-aligned parallel corpus for the **Wolof** and **Arabic** language pair, developed to address the data gap for Wolof — a low-resource language — in the field of Natural Language Processing (NLP) and Machine Translation (MT).

[![License: CC BY-NC-SA](https://img.shields.io/badge/License-CC%20BY--NC--SA-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## 📖 Dataset Description

The corpus consists of **news texts** covering diverse topics such as politics, society, religion, and sports in the Senegalese context. It serves as a **"Gold Standard"** dataset, manually translated and verified to ensure high linguistic accuracy.

### 📊 Statistics

| Metric | Arabic | Wolof |
|---|---|---|
| **Sentence Pairs** | 1,312 | 1,312 |
| **Total Words** | 17,801 | 25,246 |
| **Unique Words** | 7,556 | 4,664 |

> *Note: Statistics were generated using the [Sketch Engine](https://www.sketchengine.eu/) platform.*

---

## 🔬 Methodology

### 1. Data Provenance and Collection

The source Wolof texts were obtained from the [MasakhaNER](https://github.com/masakhane-io/masakhane-ner) project. These texts were originally crawled from four major Senegalese news outlets:

- **Seneweb**
- **Jotna News**
- **YerimPost**
- **SocialNetLink**

### 2. Manual Translation

The Arabic portion of the corpus was manually translated from the Wolof source. To ensure the highest accuracy, professional tools and dictionaries were used as decision supports, including:

- **Contextual Tools:** Reverso, Google Translate, and DeepL
- **Specialized Dictionaries:** Almaany (Arabic) and CorpOrAn (Wolof-French)

### 3. Cleaning and Pre-processing

The source files were already segmented into sentences and stripped of redundant metadata (author names, dates, and titles). Further cleaning was performed to ensure each sentence was ready for alignment.

### 4. Sentence Alignment

The corpus was aligned at the sentence level (1:1) using the **InterText** editor with the **Hunalign** algorithm. This ensures that each Wolof sentence corresponds precisely to its Arabic translation.

### 5. Quality Control

The dataset underwent a dual validation process:

- **Manual Review:** A thorough proofreading to correct translation or alignment errors.
- **Quantitative Analysis:** Lexical richness and word frequency consistency were verified using Sketch Engine.

### 6. Synthetic Data

This corpus **does not** contain any synthetic data (such as unsupervised back-translation). It is composed entirely of real-world news texts translated and validated by humans.

---

## 👥 Contributors

| Name | Contact |
|---|---|
| **Mouhamed Mbaye** | [mouhamedmbaye371@gmail.com](mailto:mouhamedmbaye371@gmail.com) |

---

## 📄 License

This dataset is licensed under [**Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA)**](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to share and adapt the material for non-commercial purposes, provided appropriate credit is given.

---

## 📌 Citation

If you use this corpus in your research, please cite the original Master's thesis:

```bibtex
@mastersthesis{diop2022wolofarabic,
  author  = {Diop, Thierno},
  title   = {Towards Building a Wolof-Arabic Linguistic Corpus for Machine Translation Purposes},
  school  = {Mohammed V University in Rabat, Faculty of Letters and Human Sciences},
  year    = {2022},
  address = {Rabat, Morocco},
  note    = {Master's Thesis in Natural Language Processing}
}
```