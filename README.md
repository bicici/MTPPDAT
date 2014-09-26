MTPPDAT
=======

MTPPDAT: Machine Translation Performance Prediction Dataset for SMT Prediction

We provide document and sentence translation prediction dataset together with the prediction results for benchmarking and research in performance prediction or quality estimation models as in WMT’14 (www.statmt.org/wmt14/quality-estimation-task.html). Translations are from English (en) to German (de) and SMT systems are built using Moses (www.statmt.org/moses/). MTPPDAT can be downloaded from:

https://drive.google.com/folderview?id=0B6Jae6trZb1aLWZMc1NnSUJGS0U&usp=sharing

We are interested whether new, task, or domain specific prediction models or better feature modeling can improve the prediction performance. MTPP model [1] is a state-of-the-art (SoA) and top performing machine translation performance predictor, which uses machine learning models over features measuring how well the test set matches the training set to predict the quality of a translation without using a reference translation. Our SoA results with MTPP model on MTPPDAT are under review and are planned to be made available later. The corpora are lowercased and tokenized. Referential Translation Machines [2] achieve top results in MTPP or quality estimation of translation.

Work using MTPPDAT:
-------------------

ADAP dataset is used in [3].


References
----------

Ergun Biçici, Declan Groves, and Josef van Genabith. Predicting Sentence Translation Quality Using Extrinsic and Language Independent Features. Machine Translation, 2013. [Abstract][bibtex-entry]
Ergun Biçici and Andy Way. Referential Translation Machines for Predicting Translation Quality. In Proceedings of the Ninth Workshop on Statistical Machine Translation, Baltimore, USA, June 2014. Association for Computational Linguistics. [PDF ] [Abstract] [bibtex-entry]
Ergun Biçici. Domain Adaptation for Machine Translation with Instance Selection. The Prague Bulletin of Mathematical Linguistics, 103, 2014. [bibtex-entry]

