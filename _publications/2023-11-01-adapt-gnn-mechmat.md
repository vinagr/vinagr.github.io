---
title: "Dynamic and adaptive mesh-based graph neural network framework for simulating displacement and crack fields in phase field models"
collection: publications
permalink: /publication/2023-11-01-adapt-gnn-mechmat
excerpt: 'In this work, we present a dynamic mesh-based GNN framework for emulating phase field simulations of single-edge crack propagation with AMR for different crack configurations.'
date: 2023-11-01
venue: 'Mechanics of Materials'
paperurl: 'https://doi.org/10.1016/j.mechmat.2023.104789'
citation: 'Perera R. and Agrawal V., Dynamic and adaptive mesh-based graph neural network framework for simulating displacement and crack fields in phase field models, <i>Mechanics of Materials</i> <b>186</b> (2023), 104789.'
---

Fracture is one of the main causes of failure in engineering structures. Phase field methods coupled with adaptive mesh refinement (AMR) techniques have been widely used to model crack propagation due to their ease of implementation and scalability. However, phase field methods can still be computationally demanding making them unfeasible for high-throughput design applications. Machine learning (ML) models such as Graph Neural Networks (GNNs) have shown their ability to emulate complex dynamic problems with speed-ups orders of magnitude faster compared to high-fidelity simulators. In this work, we present a dynamic mesh-based GNN framework for emulating phase field simulations of single-edge crack propagation with AMR for different crack configurations. The developed framework – ADAPTive mesh-based graph neural network (ADAPT-GNN) – exploits the benefits of both ML methods and AMR by describing the graph representation at each time step as the refined mesh itself. Using ADAPT-GNN, we predict the evolution of displacement fields and scalar damage field (or phase field) with good accuracy compared to the conventional phase-field fracture model. We also compute crack stress fields with good accuracy using the predicted displacements and phase field parameter.
