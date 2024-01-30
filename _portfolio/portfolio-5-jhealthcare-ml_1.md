---
title: "EEG-based Activity Recognition"
excerpt: "EEG-based Activity Recognition with Sequential Models"
collection: portfolio
tags:
  - machine learning
  - artificial intelligence
  - healthcare
  - lstm
  - hmm
  - sequential modeling
---

Electroencephalograms (EEGs) can record electricalactivity in the brain. They can be used to augment human sensory functions or control robotic devices. In order to perform these functions the Brain Computer Interface (BCI) must be able to classify EEG patterns as corresponding to a certain task and relay that
information to control the device of interest.

This project focuses on the BCI competition III Dataset V in which the goal is to classify three mental tasks online.
There are 3 tasks:
1. Imagination of repetitive self-paced left hand movements, (left, class 2),
2. Imagination of repetitive self-paced right hand movements, (right, class 3),
3. Generation of words beginning with the same random letter, (word, class 7).

BCI Competition iii Dataset V
- 32 Electrodes to collect EEG data.
- EEG: ElectroEncephaloGraphy - method to record an electrogram of the spontaneous electrical activity of the brain.
- Sampling rate is 512 Hz


Modeling Techniques used:
- SVM
- kNN
- Hidden Markov Models
- LSTM
- BiLSTM

![EEGData](/images/c3_raw.png){: .align-center width="400px"}
*EEG Data Example*

*Please refer to the powerpoint for more details*
![eeg-recognition-ppt](/images/10_P4_EEG_ActivityRecognition.pdf)
