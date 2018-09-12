# Visually Indicated Sound Generation by Perceptually Optimized Classification
This repository includes annotated keyword datasets used by Visually Indicated Sound Generation byPerceptually Optimized Classification system (ECCV-MULA 2018)

## Introduction

**Visually Indicated Sound Generation** aims to predict visuallyconsistent  sound  from  the  video  content. Previous  methods in  [Visually Indicated Sounds](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Owens_Visually_Indicated_Sounds_CVPR_2016_paper.pdf) addressed this problem by creating a single generative model that ignores the dis-tinctive characteristics of various sound categories. Nowadays, state-of-the-art sound classification networks are available to capture semantic-level information in audio modality, which can also serve for the purposeof  visually  indicated  sound  generation.

## Framework

The framework of Visually Indicated Sound Generation byPerceptually Optimized Classification is shown below:

> here is an image.

We explore gen-erating fine-grained sound from a variety of sound classes, and leveragepre-trained sound classification networks to improve the audio generationquality. We propose a novel Perceptually Optimized Classification basedAudio generation Network (POCAN), which generates sound conditionedon the sound class predicted from visual information. Additionally, a per-ceptual loss is calculated via a pre-trained sound classification networkto align the semantic information between the generated sound and itsground truth during training.



## GHD dataset download



## VIG dataset download


## License
