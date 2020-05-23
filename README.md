                        Abusive-Language-Detection-of-tweets-in-Urdu
                              ===========================

                                August 1st October, 2019
                                
    Maaz Amjad, Grigori Sidorov, Alisa Zhila, Helena Gómez-Adorno, Alexander Gelbukh, Ilia Voronkov

                       Natural Language and Text Processing Laboratory
                       Center for Computing Research (CIC)
                       Instituto Politécnico Nacional (IPN)
                       Ciudad de México (Mexico City), Mexico  
---
## CONTENTS
 1. Introduction
 2. Data Annotation
 3. Feedback
 4. Citation Info
 5. Acknowledgments
---

## About this data
Here we provide our dataset for multi-label hate speech and abusive language detection in the Indonesian Twitter. The main dataset can be seen at **re_dataset** with labels information as follows:

For each label, `1` means `yes` (tweets including that label), `0` mean `no` (tweets are not included in that label). 

Due to the Twitter's Terms of Service, we do not provide the tweet ID. All username and URL in this dataset are changed into USER and URL. 

For text normalization in our experiment, we built typo and slang words dictionaries named **---**, that contain two columns (first columns are the typo and slang words, and the second one is the formal words). Here the examples of mapping:


Furthermore, we also built abusive lexicon list named **abusive.csv** that can be used for feature extraction.

## More detail
If you want to know how this dataset was build (include the explanation of crawling and annotation technique) and how we did our experiment in multi-label hate speech and abusive language detection in Urdu language using this dataset, you can read our paper in he

---

## 3. Feedback
If you want to know how this dataset was build (include the explanation of crawling and annotation technique) and how we did our experiments for Fake News detection in Urdu language using this dataset, you can read our paper in here:

*For further questions or inquiries about this dataset, you can contact Maaz Amjad (maazamjad@phystech.edu)* 

---


## How to cite us
This dataset and the other resource can be used for free, but if you want to publish paper/publication using this dataset, please cite this publication:

@article{MaazUrdufake2020,
author = { Maaz Amjad, Numan Ahsref, Grigori Sidorov, Alisa Zhila, Hamza Imam Amjad, Ilia Voronkov},
title = {Automatic Abusive Language Detection in Urdu},
year = {2020}
}
```
---
