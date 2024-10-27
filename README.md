# Unstable Diffusion

**Unstable Diffusion** is an experimental implementation and research adaptation of the popular **Stable Diffusion** model, designed to explore the boundaries and intricacies of image generation using diffusion techniques. This project aims to dive deeper into the theoretical aspects of diffusion models, specifically focusing on image stability and variance during the diffusion process. Leveraging PyTorch and modern machine learning libraries, this repository provides tools and scripts for training, evaluating, and visualizing the effects of perturbations in diffusion.

This project is ideal for researchers and practitioners interested in experimenting with new methods in diffusion modeling, enhancing robustness, and exploring the impact of controlled noise on model output. We encourage contributions and discussions on issues such as model instability, potential applications in generative art, and innovative uses of diffusion models beyond traditional image generation. Explore, experiment, and contribute to pushing the diffusion research boundaries with us!

## Download weights and tokenizer files:

1. Download `vocab.json` and `merges.txt` from https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5/tree/main/tokenizer and save them in the `data` folder
2. Download `v1-5-pruned-emaonly.ckpt` from https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5/tree/main and save it in the `data` folder

## Tested fine-tuned models:

Just download the `ckpt` file from any fine-tuned SD (up to v1.5).

1. InkPunk Diffusion: https://huggingface.co/Envvi/Inkpunk-Diffusion/tree/main
2. Illustration Diffusion (Hollie Mengert): https://huggingface.co/ogkalu/Illustration-Diffusion/tree/main

Course: [Creating Stable Diffusion from Scratch in PyTorch by Umar Jamil](https://youtu.be/ZBKpAp_6TGI?si=4OQEVw46N03sbAEI)
