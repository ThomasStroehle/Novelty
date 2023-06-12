# AI-based novelty detection in crowdsourced idea spaces

In the following project, we applied different language embeddings (SBert, Ada002, Doc2Vec, SimCSE) to an idea contest to identify novel ideas. For novel detection, we used different unsupervised methods such as local outlier factor and kNN distance and compared our results with human evaluations. All computations and evaluations can be found in the following [notebook](https://github.com/ThomasStroehle/Novelty/blob/main/novelty.ipynb). You can find the article via [https://doi.org/10.1080/14479338.2023.2215740](https://doi.org/10.1080/14479338.2023.2215740).

If you used our code and found it useful, please cite us as follows:

```
@article{doi:10.1080/14479338.2023.2215740,
author = {Julian Just and Thomas Ströhle and Johann Füller and Katja Hutter},
title = {AI-based novelty detection in crowdsourced idea spaces},
journal = {Innovation},
volume = {0},
number = {0},
pages = {1-28},
year  = {2023},
publisher = {Routledge},
doi = {10.1080/14479338.2023.2215740},
URL = {https://doi.org/10.1080/14479338.2023.2215740},
eprint = {https://doi.org/10.1080/14479338.2023.2215740}
}
```

## Abstract 

Processing large and heterogeneous numbers of ideas submitted to crowdsourcing contests is a regular challenge for idea evaluators. The aim of this study is to investigate a potential use case for AI-based innovation management and to extend the knowledge of using automated novelty detection in idea evaluation processes. AI-based language models can automatically allocate short texts according to their semantic similarity in an embedded space. We represent the semantic content of crowdsourced ideas with the three contemporary text embeddings – Doc2Vec, SBERT, and GPT-3-based Ada Similarity – and compute their semantic distance to different reference sets using different novelty detection algorithms. We then compare the algorithm-generated scores with human novelty assessments to validate them. While selected novelty scores based on text embeddings correlate with humans, our results show that scores based on SBERT embeddings best match human novelty assessments. We also find that AI-based novelty detection approaches perform better for ideas below the median word count and when compared to a set of existing solutions, suggesting that the chosen language model is not the only factor influencing the applicability of the proposed approach. Furthermore, the study highlights important features and limitations of automatically generated novelty scores that need to be considered when complementing evaluators searching for new ideas in crowdsourcing contests and beyond.
