---
title: "An Empirical Approach for Human Locomotion and Transportation Recognition from Radio Data"
collection: publications
category: conferences
permalink: "https://dl.acm.org/doi/10.1145/3460418.3479384"
excerpt: 'P. Saha, M. M. Alam, M. I. Tapotee, **S. B. Baray**, and M. A. R. Ahad, "An Empirical Approach for Human Locomotion and Transportation Recognition from Radio Data," in Adjunct Proceedings of the 2021 ACM International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of the 2021 ACM International Symposium on Wearable Computers (UbiComp/ISWC 21 Adjunct), 2021, pp. 390–395, doi: 10.1145/3460418.3479384.'
date: 2021-09-24
venue: 'UbiComp/ISWC 2021 Adjunct: Adjunct Proceedings of the 2021 ACM International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of the 2021 ACM International Symposium on Wearable Computers'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://dl.acm.org/doi/10.1145/3460418.3479384'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Sussex-Huawei Locomotion-Transportation (SHL) recognition challenge, the fourth edition of the challenge provides an opportunity to recognize 8 modes of locomotion and transportation (activities) from radio data, including GPS reception, GPS location, WiFi reception, and GSM cell tower scans in a user-independent manner. Though the dataset has provided good location data, the main challenge has been how to use the variable number of data from satellite, WiFi, and cell tower information. We, team “Guerrilla”, have used the location data to extract different features like distance, velocity, acceleration, and hand-picked certain information from the satellite, WiFi, and cell tower data. Various features have been extracted from the frequency and time domain and diverse windowing techniques have been implemented. Using 1350 features, different models like Extra Trees Classifier, Random Forest Classifier, XGBoost Classifier, etc. have been trained among which the XGBoost Classifier model has performed the best. And finally, the top 250 features have been selected for the XGBoost Classifier to build an efficient model that has given accuracy and f1 score of 79.11% and 79.39% respectively on the validation dataset.

Read the article at: [An Empirical Approach for Human Locomotion and Transportation Recognition from Radio Data](https://dl.acm.org/doi/10.1145/3460418.3479384)