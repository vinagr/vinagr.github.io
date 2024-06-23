---
title: "Graph neural networks for simulating crack coalescence and propagation in brittle materials"
collection: publications
permalink: /publication/2022-05-15-microcrack-gnn-cmame
excerpt: 'This work develops a Graph Neural Network (GNN) based framework to simulate fracture and stress evolution in brittle materials due to multiple microcracks’ interaction.'
date: 2022-05-15
venue: 'Computer Methods in Applied Mechanics and Engineering'
paperurl: 'https://doi.org/10.1016/j.cma.2022.115021'
citation: 'Perera R., Guzzeti D. and Agrawal V., Graph neural networks for emulating crack coalescence and propagation in brittle materials, <i>Computer Methods in Applied Mechanics and Engineering</i>, <b>395</b> (2022), 115021.'
---

High-fidelity fracture mechanics simulations of multiple microcracks interaction via physics-based models can become computationally demanding as the number of microcracks increases. This work develops a Graph Neural Network (GNN) based framework to simulate fracture and stress evolution in brittle materials due to multiple microcracks’ interaction. The GNN framework is trained on the dataset generated by XFEM-based fracture simulator. Our framework achieves high prediction accuracy on the test set (compared to an XFEM-based fracture simulator) by engineering a sequence of GNN-based predictions. The first prediction stage determines Mode-I and Mode-II stress intensity factors (which can be used to compute the stress evolution by LEFM), the second prediction stage determines which microcracks will propagate, and the final stage actually propagates crack-tip positions for the selected microcracks to the next time instant. The trained GNN framework is capable of simulating crack propagation, coalescence and corresponding stress distribution for a wide range of initial microcrack configurations (from 5 to 19 microcracks) without any additional modification. Lastly, the framework’s simulation time shows speed-ups 6x–25x faster compared to an XFEM-based simulator. These characteristics, make our GNN framework an attractive approach for simulating microcrack propagation and stress evolution in brittle materials with multiple initial microcracks.