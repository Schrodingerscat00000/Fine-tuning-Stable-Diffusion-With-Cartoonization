# Fine-tuning-Stable-Diffusion-With-Cartoonization

This project demonstrates a pipeline for fine-tuning a Stable Diffusion model to cartoonize images. It includes data preprocessing, model training, and a Gradio-based GUI for inference.

## Features
- **Dataset Analysis & Preprocessing:** The "Cartoonization" dataset is taken from HuggingFace.The dataset contains 5k images and their respective cartoonized version iamges. A subset of the images has been used in the training for this experiment.
- 
- **Model Fine-Tuning:** A lightweight Stable Diffusion model (CompVis/stable-diffusion-v1-4) is used for fine-tuning. Stable Diffusion’s key components including the Variational Autoencoder (VAE), UNet, and text encoder are loaded and used.
- 
- **Image-to-Image Inference:** The UNet is trained on the cartoonization dataset, using the original images as input and cartoonized images as the target. Noise is added to simulate the diffusion process.
-
- **User-Friendly Interface:** Gradio-powered GUI is built for easy interaction to produce a cartoonized version from a normal image.
