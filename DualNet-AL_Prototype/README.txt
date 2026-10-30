# DualNet-AL Concept Prototype

## What this is
A standalone, browser-based interactive demonstrator based on the Phase-I report:
**DualNet-AL: Bi-Network Meta-Learning Framework for Multi-Class Active Learning**

It illustrates:
- a Task Network concept (predicted class and uncertainty fields),
- a Query Network concept (transparent uncertainty + class-balance scoring),
- iterative sample selection from an unlabelled pool,
- an evolving labelled-pool class distribution.

## Run
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. Press **Run active-learning round** to select five samples.
4. Press **Reset simulation** to restart.

No installation or internet connection is required.

## Important limitation
This is a concept-level simulation using synthetic sample records and illustrative scoring rules. It does **not** contain a trained CNN, a trainable meta-learning Query Network, CIFAR dataset experiments, or measured model performance. The displayed scores are prototype ranking scores, not accuracy results. These remain future implementation milestones.
