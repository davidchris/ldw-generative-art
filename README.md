# LDW Generative Art using Stable Diffusion - Art Collab

Main workflow is in `notebooks/tf-cockpunch-ai-art.ipynb`.

Install environment via 

```shell
conda env create -f environment.yaml
```

## Motivation

[The AI Art Competition Beginneth!](https://tim.blog/2022/12/16/ai-art-competition/)

## Prompts and parameters

Prompts and parameters used for generating the images can be found under `image_parameters/`.

## Process

- We are running Stable Diffusion locally on a Linux desktop (with a NVIDIA RTX 3090)
- Running the code from a jupyter notebook 
- We then iterated on the prompt and parameters inside the notebook 
- All prompts, parameters and images are saved locally
- At last, the images we liked where saved to a specific folder

## Tutorials used for this project

- <https://huggingface.co/blog/diffusers-2nd-month#image-to-image-pipeline>
- <https://huggingface.co/stabilityai/stable-diffusion-2>

