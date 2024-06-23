---
title: "A generalized machine learning framework for brittle crack problems using transfer learning and graph neural networks"
collection: publications
permalink: /publication/2023-06-01-accurate-mechmat
excerpt: 'In this work, we use transfer learning to develop a generalized ML framework called ACCURATE to study multiple crack propagtion under mixed mode loading.'
date: 2023-06-01
venue: 'Mechanics of Materials'
paperurl: 'https://doi.org/10.1016/j.mechmat.2023.104639'
citation: 'Perera R. and Agrawal V., A generalized machine learning framework for brittle crack problems using transfer learning and graph neural networks, <i>Mechanics of Materials</i> <b>181</b> (2023), 104639'
---

Despite their recent success, machine learning (ML) models such as graph neural networks (GNNs), suffer from drawbacks such as the need for large training datasets and poor performance for unseen cases. In this work, we use transfer learning (TL) approaches to circumvent the need for retraining with large datasets. We apply TL to an existing ML framework, trained to predict multiple crack propagation and stress evolution in brittle materials under Mode I loading. The new framework, ACCelerated Universal fRAcTure Emulator (ACCURATE), is generalized to a variety of crack problems by using a sequence of TL update steps including (i) arbitrary crack lengths, (ii) arbitrary crack orientations, (iii) square domains, (iv) horizontal domains, and (v) shear loadings. We show that using small training datasets of 20 simulations for each TL update step, ACCURATE achieved high prediction accuracy in Mode-I and Mode-II stress intensity factors, and crack paths for these problems. We demonstrate ACCURATE’s ability to predict crack growth and stress evolution with high accuracy for unseen cases involving the combination of new boundary dimensions with arbitrary crack lengths and crack orientations in both tensile and shear loading. We also demonstrate significantly accelerated simulation times of up to 2 orders of magnitude faster (200x) compared to an XFEM-based fracture model. The ACCURATE framework provides a universal computational fracture mechanics model that can be easily modified or extended in future work.
