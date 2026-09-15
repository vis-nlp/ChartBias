# ChartBias

Official repository for the paper:

## From Charts to Fair Narratives: Uncovering and Mitigating Geo-Economic Biases in Chart-to-Text

[![EMNLP 2025](https://img.shields.io/badge/EMNLP-2025-b31b1b.svg)](https://aclanthology.org/2025.emnlp-main.1472/)
[![Paper](https://img.shields.io/badge/Paper-ACL%20Anthology-blue.svg)](https://aclanthology.org/2025.emnlp-main.1472/)

This paper investigates **geo-economic biases in vision-language models (VLMs) for chart-to-text generation**. We study whether VLMs generate different interpretations of the same chart when the associated country is changed, and examine how these responses vary across countries with different economic statuses.

We construct a benchmark of **100 country-agnostic charts paired with 60 countries**, resulting in **6,000 chart-country pairs**, and evaluate six proprietary and open-source VLMs. We also explore an inference-time prompt-based approach for mitigating observed biases.

## Dataset

The benchmark is constructed from the **VisText** dataset. We select 100 diverse charts and remove country references from chart titles and axes to make them country-agnostic. The charts cover four trend types:

- Positive
- Negative
- Neutral
- Volatile

Each chart is paired with 60 countries spanning high-, middle-, and low-income groups, resulting in 6,000 chart-country pairs.


## Citation

```bibtex
@inproceedings{mahbub-etal-2025-charts,
    title = "From Charts to Fair Narratives: Uncovering and Mitigating Geo-Economic Biases in Chart-to-Text",
    author = "Mahbub, Ridwan and
      Islam, Mohammed Saidul and
      Nayeem, Mir Tafseer and
      Laskar, Md Tahmid Rahman and
      Rahman, Mizanur and
      Joty, Shafiq and
      Hoque, Enamul",
    editor = "Christodoulopoulos, Christos and
      Chakraborty, Tanmoy and
      Rose, Carolyn and
      Peng, Violet",
    booktitle = "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    pages = "28929--28947",
    doi = "10.18653/v1/2025.emnlp-main.1472",
    url = "https://aclanthology.org/2025.emnlp-main.1472/"
}
