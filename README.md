# Plain Language Summarization of Clinical Trials

This repository contains CARES (Clinical Abstractive Result Extraction and Simplification) the dataset described in the paper:

> **Plain Language Summarization of Clinical Trials** 
> [[Paper]](https://aclanthology.org/2024.determit-1.6.pdf) [[ACL Anthology]](https://aclanthology.org/2024.determit-1.6/)  <br>
> Polydoros Giannouris, Theodoros Myridis, Tatiana Passali, and Grigorios Tsoumakas <be>

---
### Structure of this repo

```bash
├── plain_language_summaries: complete plain language summaries, organized by subsections
├── raw_sources: raw texts of source documents
    ├── study_protocols: Study Protocol texts
    └── synopses: Clinical Synopses texts
└── train_test_splits: data for training and testing
```

---
### Citation
If you find this repository helpful, please consider citing our paper: 

```bibtex
@inproceedings{giannouris2024plain,
  title={Plain Language Summarization of Clinical Trials},
  author={Giannouris, Polydoros and Myridis, Theodoros and Passali, Tatiana and Tsoumakas, Grigorios},
  booktitle={Proceedings of the Workshop on DeTermIt! Evaluating Text Difficulty in a Multilingual Context @ LREC-COLING 2024},
  pages={60--67},
  year={2024}
}
```
