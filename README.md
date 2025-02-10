# BongVQA

This repository contains the original implementation of the paper "BongVQA-Visual-Linguistic-Fusion-for-Bengali-Advancing-Image-Understanding-through-VQA"

Authors: Nirjhor Datta, Farig Sadeque

We have proposed a new large scale dataset for object recognition in an image through bengali visual question answering. This is the first bengali visual question answering research which focused on generation task instead of classification. We have evaluated with combination of different transformer based vision and language models with variable numbers of decoder layer for our task.

| **Model**          | **Decoder Layers** | **BLEU** | **METEOR** | **Exact Match** |
|--------------------|--------------------|----------|------------|-----------------|
| ViT+BanglaBERT     | 2                  | 46.71    | 0.4744     | 0.296           |
| ViT+BanglaBERT     | 4                  | 46.71    | 0.4904     | 0.3124          |
| ViT+BanglaBERT     | 6                  | 71.03    | 0.4912     | 0.309           |
| ViT+mBERT          | 2                  | 34.39    | 0.4552     | 0.2722          |
| ViT+mBERT          | 4                  | 31.61    | 0.4643     | 0.2738          |
| ViT+mBERT          | 6                  | 32.56    | 0.4697     | 0.2782          |


Codes and associated datasets will be updated soon
