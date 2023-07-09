
# Medical Abstract Segmentation

<div style='float:left;'>
  <img href='' src='https://img.shields.io/badge/Maintained%3F-Yes-brightgreen.svg' style='margin-right:10px;'>
  <img href='https://www.python.org/' src='https://img.shields.io/badge/Made with-Python-blue' style='margin-right:10px;'>
  <img href='https://choosealicense.com/licenses/mit/' src='https://img.shields.io/badge/LICENSE-MIT-green' style='margin-right:10px'>
  <img href='https://github.com/MatthewJansen/Medical-Abstract-Segmentation' src='https://img.shields.io/github/stars/MatthewJansen/Medical-Abstract-Segmentation?style=social' style='margin-right:10px'>
  <img href='https://github.com/MatthewJansen/Medical-Abstract-Segmentation/fork' src='https://img.shields.io/github/forks/MatthewJansen/Medical-Abstract-Segmentation?style=social' style='margin-right:10px'>
  <img href='https://github.com/MatthewJansen/Medical-Abstract-Segmentation' src='https://img.shields.io/github/watchers/MatthewJansen/Medical-Abstract-Segmentation?style=social' style='margin-right:10px'>  
</div>


<center>
    <img src="https://i.postimg.cc/BZmFrknh/Medical-Abstract-Segmentation.png" 
         alt ="Medical-Abstract-Segmentation" 
         style='width: 50%;'>
</center>

## Overview
Abstracts from medical research papers can be challenging to read at a glance as they contain complex wording, densely represented in a single paragraph. What if there was a way to segment these abstracts so that they become optimized for speed reading (skimmable)?

The purpose of this notebook is to explore building a Natural Language Processing (NLP) model with TensorFlow to segment text lines of abstracts from medical research papers in order to improve the readability of these said abstracts while maintaining a compute efficiency & implementation complexity constraint (CPU-only and simple implementation).

The dataset used to train the NLP model is based on a paper titled **"PubMed 20k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts"**, published in October 2017. 

The NLP model architecture used in this notebook is inspired by this paper titled **"Neural Networks for Joint Sentence Classification in Medical Paper Abstracts"** (also mentioned in the dataset paper), published in December 2016. Note that the model implemented in this notebook aims to reproduce similar results as seen in the aforementioned paper.

> - *Dataset paper*: [PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts](https://arxiv.org/abs/1710.06071)
> - *Model architecture paper*: [Neural Networks for Joint Sentence Classification in Medical Paper Abstracts](https://arxiv.org/abs/1612.05251)


## Requirements

- **Recommended python version:** Python +3.8.10 64-bit

[Note: This section will be updated in due course.]

## Project Structure

```
.
├── LICENSE
├── README.md
└── nlp_medical_abstract_segmentation.ipynb
```

- **LICENSE** | project license (MIT)
- **README.md** | project readme file
- **nlp_medical_abstract_segmentation.ipynb** | project notebook


## Usage
`See nlp_medical_abstract_segmentation.ipynb`

## License
This project is licensed under the terms and conditions of the [MIT license](https://choosealicense.com/licenses/mit/).
