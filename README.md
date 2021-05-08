# Overview

This code repository constains the code of the PetaDroid and MalDozer systems
for Android malware detection. The systems have been elaborated in the context
of the following research papers:

_Karbab, ElMouatez Billah, and Mourad Debbabi. " PetaDroid: Adaptive Android
Malware Detection using Deep Learning." DIMVA 2021._

_Karbab, ElMouatez Billah, Mourad Debbabi, Abdelouahid Derhab, and Djedjiga
Mouheb. "MalDozer: Automatic framework for android malware detection using deep
learning." Digital Investigation 24 (2018): S48-S59._

The code is organized in form of multiple Jupyter notebooks for the different
evaulation expirements.

# Abstract

  Android malware detection is a significant problem that affects billions of
  users using millions of Android applications (apps) in existing markets. This
  paper proposes **PetaDroid**, a framework for accurate Android malware
  detection and family clustering on top of static analyses. **PetaDroid**
  automatically adapts to Android malware and benign changes over time with
  resilience to common binary obfuscation techniques. The framework employs
  novel techniques elaborated on top of natural language processing (NLP) and
  machine learning techniques to achieve accurate, adaptive, and resilient
  Android malware detection and family clustering. **PetaDroid** identifies
  malware using an ensemble of convolutional neural network (CNN) on proposed
  Inst2Vec features.  The framework clusters the detected malware samples into
  malware family groups utilizing sample feature digests generated using deep
  neural auto-encoder. For change adaptation, **PetaDroid** leverages the
  detection confidence probability during deployment to automatically collect
  extension datasets and periodically use them to build new malware detection
  models. Besides, **PetaDroid** uses code-fragment randomization during the
  training to enhance the resiliency to common obfuscation techniques. We
  extensively evaluated **PetaDroid** on multiple reference datasets.
  **PetaDroid** achieved a high detection rate (98-99\% f1-score) under
  different evaluation settings with high homogeneity in the produced clusters
  (96\%). We conducted a thorough quantitative comparison with state-of-the-art
  solutions **MaMaDroid**, **DroidAPIMiner**, **MalDozer**, in which
  **PetaDroid** outperforms them under all the evaluation settings.

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)
file for details

# Citations

_Karbab, ElMouatez Billah, and Mourad Debbabi. " PetaDroid: Adaptive Android
Malware Detection using Deep Learning." DIMVA 2021._

_Karbab, ElMouatez Billah, Mourad Debbabi, Abdelouahid Derhab, and Djedjiga
Mouheb. "MalDozer: Automatic framework for android malware detection using deep
learning." Digital Investigation 24 (2018): S48-S59._
