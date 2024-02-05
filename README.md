# README
Code repository for Exercise1 of NLP class, Master's in Theoretical and Applied Linguistics, Pompeu Fabra University.

Code created by Alba Prados Moya, Daniel J Casas, and Yutong Zhang.

*** 
### Exercise goal
Proving whether Zipf’s Law of Abbreviation holds for a particular genre of text in English that is not a novel and the same genre in a different language than English.

In our case, we opted for books within the genre of Religion in both English and Finnish, which we outsourced from Project Gutenberg Website.

English:
  * Title: Curiosities of Superstition, and Sketches of Some Unrevealed Religions
  * Author: W. H. Davenport Adams
  * Genre: Religion
  * URL: https://www.gutenberg.org/cache/epub/41566/pg41566.txt

Finnish:
  * Title: Title: Suomalaisten runojen uskonto (The religion of Finnish poems)
  * Author: Kaarle Krohn
  * Genre: Religion
  * URL: https://www.gutenberg.org/cache/epub/49028/pg49028.txt


*** 
### Requirements
The code is written in python 3

Packages required:
  * urllib
  * spacy
  * pandas
  * matplotlib
  * seaborn
  
Pretrained models used from spaCy:
  * English: en_core_web_sm 
  * Finnish: fi_core_news_sm

***

### Data
The scripts expect the symbolic and visual data to be placed in appropriate `mutual-exclusivity/data`-(sub)folders

  * For example, the data for symbolic experiments using the transcriptions of CHILDES used in Frank et al. (2009) may be placed in `data/frank2009/all_words`;
  * and the pre-processed bounding boxes of Flickr30K objects in `data/flickr`


***

### References

Some snippets of code are from this source by Thomas Brochhagen.(https://colab.research.google.com/github/brochhagen/nlpupf/blob/main/material/2024q2/session01/session0102.ipynb#scrollTo=11eaae8b)
