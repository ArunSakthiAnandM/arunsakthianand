---
title: "Voice-driven toy car using python deep-learning APIs"
collection: projects
permalink: /projects/toy-car
excerpt: 'In this project, we create a Toy Car which is controlled by Arduino UNO. The Arduino receives its input via bluetooth from a Deep Learning Model that can predict the voice commands from the user.'
date: 2019-11-11
paperurl: 'https://github.com/ArunSakthiAnandM/Voice_Controlled_Toy_Car'
---

In this project, we create a Toy Car which is controlled by Arduino UNO. The Arduino receives its input via bluetooth from a Deep Learning Model that can predict the voice commands from the user.

The motive is to observe and understand the functioning of Deep Learing APIs and figure out the best possible combination of Optimisers, Error Functions, Feature Extraction meathods etc.

Final Conclusions and Description:
* Data augmentation - [Zero Padding](https://www.ni.com/docs/en-US/bundle/labview/page/lvanlsconcepts/lvac_zero_padding.html)
* Feature extraction - [Mel-frequency cepstral coefficients](https://en.wikipedia.org/wiki/Mel-frequency_cepstrum)(MFCC)
* Model Used - [Long short-term memory](https://en.wikipedia.org/wiki/Long_short-term_memory)(LSTM)
* Error Function - [Categorical cross entropy](https://gombru.github.io/2018/05/23/cross_entropy_loss/)
* Optimiser - [RMSProp](https://keras.io/api/optimizers/rmsprop/)


[Source Codes here](https://github.com/ArunSakthiAnandM/Voice_Controlled_Toy_Car)