---
layout: single
title: "A Machine learning method to evaluate and improve sound effects synthesis model design"
collection: publications
category: firstauthor
display_order: 4
permalink: /publications/machine-learning-sound-effects-model-design/
author_profile: true
date: 2024-04-27
venue: "Audio Engineering Society (AES) 2024 International Audio for Games Conference"
external_url: "https://aes2.org/publications/elibrary-page/?id=22417"
excerpt: "Procedural audio models have great potential in sound effects production and design, they can be incredibly high quality and have high interactivity with the users. However, they also often have many free parameters that may not be specified just from an understanding of the phenomenon, making it very difficult for users to create the desired sound. Moreover, their potential and generalization ability are rarely explored fully due to their complexity. To address these problems, this work introduces a hybrid machine learning method to evaluate the overall sound matching performance of a real sound dataset. First, we train a parameter estimation network using synthesis sound samples. Through the differentiable implementation of the sound synthesis model, we use both parameter and spectral loss in this self-supervised stage. Then, we perform adversarial training by spectral loss plus adversarial loss using real sound samples. We evaluate our approach for an example of an explosion sound synthesis model. We experiment with different model designs and conduct a subjective listening test. We demonstrate that this is an effective method to evaluate the overall performance of a sound synthesis model, and its capability to speed up the sound model design process."
---

Y. Zong, N. Garcia-Sihuay and J. Reiss. *Audio Engineering Society (AES) 2024 International Audio for Games Conference*.

## Abstract

Procedural audio models have great potential in sound effects production and design, they can be incredibly high quality and have high interactivity with the users. However, they also often have many free parameters that may not be specified just from an understanding of the phenomenon, making it very difficult for users to create the desired sound. Moreover, their potential and generalization ability are rarely explored fully due to their complexity. To address these problems, this work introduces a hybrid machine learning method to evaluate the overall sound matching performance of a real sound dataset. First, we train a parameter estimation network using synthesis sound samples. Through the differentiable implementation of the sound synthesis model, we use both parameter and spectral loss in this self-supervised stage. Then, we perform adversarial training by spectral loss plus adversarial loss using real sound samples. We evaluate our approach for an example of an explosion sound synthesis model. We experiment with different model designs and conduct a subjective listening test. We demonstrate that this is an effective method to evaluate the overall performance of a sound synthesis model, and its capability to speed up the sound model design process.

[Read the paper](https://aes2.org/publications/elibrary-page/?id=22417) · [All publications]({{ '/publications/' | relative_url }})
