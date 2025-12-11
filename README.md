Title: Variational Autoencoders: Probabilistic Representation Learning and Generative Modelling

This repository accompanies a tutorial on Variational Autoencoders (VAEs), focusing on their theoretical foundations, mathematical formulation, and practical behaviour when trained on the MNIST dataset. It includes the full written tutorial, a Jupyter notebook that reproduces all figures, and supporting documentation.

Repository Structure

Nayak_Ml.ipynb

Machine-Learning

The repository contains:

A Jupyter notebook with all experiments.

A PDF tutorial explaining theory, implementation, results, and interpretation.

A folder containing all generated figures used in the tutorial.

A licence file.

This README.

Project Overview

The tutorial explains how VAEs combine neural networks with probabilistic modelling through variational inference. It covers the ELBO objective, reconstruction loss, KL divergence regularisation, latent variable modelling, and sampling from learned distributions. Experiments demonstrate reconstruction quality, latent space organisation, generative sampling, and training dynamics.

Instructions for Running the Notebook

Ensure Python and a deep-learning framework (PyTorch) are installed.

Open the experiment notebook included in the repository.

Run all cells sequentially to:

Train the VAE

Compute loss metrics

Generate reconstructions

Visualise the latent space

Produce synthetic samples

Export all figures to the figures directory

All outputs in the tutorial were generated directly from this notebook.

Dataset Information

The experiments use the MNIST handwritten digit dataset.
It contains 70,000 grayscale images of size 28×28 across ten classes (0–9).
The dataset is widely used for benchmarking generative models because of its simplicity, balanced class distribution, and clear structure that facilitates latent space interpretation.

Accessibility Considerations

All figures follow colour-blind-friendly palettes.

High-contrast styles are used for clarity.

Alternative text descriptions for images are included in the tutorial.

Hierarchical headings support assistive reading technologies.

No information is conveyed through colour alone.

Licence

This repository is released under the MIT Licence, allowing reuse, modification, and distribution with attribution.
