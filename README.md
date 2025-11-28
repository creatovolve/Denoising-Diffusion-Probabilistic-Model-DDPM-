This repository implements a Denoising Diffusion Probabilistic Model (DDPM) to generate high-quality butterfly images from the Butterfly dataset. The implementation is educational yet production-minded: clean code, configurable training, reproducible sampling, and evaluation utilities (FID / visualizations). The model follows the DDPM formulation (Ho et al., 2020) and uses a U-Net backbone with attention blocks for multi-scale conditioning.

Repository contains code for:

Train a DDPM on the Butterfly dataset to learn the data distribution.

Provide training, sampling, and evaluation scripts with easy-to-follow configs.
