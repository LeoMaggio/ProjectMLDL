# Open World Recognition in Image Classification - MLDL2021

While Convolutional Neural Networks have brought major advances in computer vision, modern robots are not yet ready to act in the open world. Their abilities are in fact limited to closed world scenarios, in which it is assumed that the semantic concepts a model has to recognize is limited to the number of classes seen during training. One of the main problems of artificial intelligence is precisely to break the closed world assumption and make robots capable not only of recognizing what they do not know, but also making them capable of dynamically extending their knowledge about the world.

In this work, we face the incremental learning challenges, building a model that reproduces the baselines of existing classification frameworks. In a subsequent ablation study, we experiment with the combination of different components, to understand their individual contribution and verify their effectiveness. Next, we take into account the open world recognition problem and incorporate into our model a naive rejection strategy for unknown classes. Finally, we propose our rejection strategy, based on deep ensembles, which addresses the uncertainty of the model.

---

This repository contains the code for our project "*Open World Recognition in Image Classification*", for the Machine Learning and Deep Learning course @ Politecnico di Torino, A.Y. 2020/21.

Further details are provided in our paper: [An Ensemble Approach to Open World Recognition in Image Classification](https://github.com/LeoMaggio/ProjectMLDL/blob/main/Albanese_Maggio_Nedescu.pdf).

The repository is organized in this way: 
- **baselines** folder: contains all the jupyter notebooks that implement the baselines for the Incremental Learning scenario.
- **classifiers** folder: contains all the the jupyter notebooks that implement a short ablation study on the classifiers used in iCaRL baseline.
- **losses** folder: contains all the the jupyter notebooks that implement a short ablation study on the losses used in iCaRL baseline.
- **model** folder: contains all python files that implement the different models used in this work. 
- **owr** folder: contains all the jupyter notebooks that implement an Open World scenario, with a naive rejection strategy and with *our proposal*.
- **other**: support files and libraries.

Contributors to this project are: Albanese Antonio, Maggio Leonardo and Nedescu Ionut Cosmin.
