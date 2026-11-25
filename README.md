# GenAI Lab

A collection of 10 generative AI practicals, provided in two notebook variants:

- **[Colab GPU Optimized](Colab%20GPU%20Optimized/)** — notebooks intended for Google Colab, with a GPU recommended or required for some experiments.
- **[Jupyter Optimized for CPU](Jupyter%20Optimized%20for%20CPU/)** — CPU-friendly demonstrations for running locally without a dedicated GPU. Some experiments use simplified demonstrations instead of running large pretrained models.

## Experiments

Both variants cover:

1. Dataset analysis and preprocessing
2. Python and TensorFlow tensor operations
3. Text generation with a pretrained transformer
4. Text-to-image generation
5. A variational autoencoder (VAE) on MNIST
6. A DCGAN trained on CelebA
7. StyleGAN concepts and style mixing
8. Music generation
9. A personalized assistant using RAG and LoRA
10. Text-to-video generation

## Getting started

### Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload a notebook from `Colab GPU Optimized`.
3. Run its cells from top to bottom.
4. For GPU-intensive experiments, select **Runtime > Change runtime type > GPU**.

### Local Jupyter

1. Install Jupyter Notebook or JupyterLab and a compatible Python environment. Python 3.10 or 3.11 is recommended.
2. Open a notebook from `Jupyter Optimized for CPU`.
3. Run its cells from top to bottom.

Notebooks install or request their own dependencies where applicable. An internet connection may be needed to download packages, datasets, or model weights.

## Notes and limitations

- The CPU notebooks prioritize demonstrations that can run without a dedicated GPU; they are not always equivalent to full pretrained-model inference.
- The CPU image-generation notebook uses a lightweight demonstration by default; Stable Diffusion is optional and can be very slow on CPU.
- The CPU music notebook defaults to a short tone demo; pretrained MusicGen is optional and computationally expensive on CPU.
- The CPU text-to-video notebook produces a prompt-labelled slideshow, not neural text-to-video output.
- The GPU text-to-video experiment may need more memory than a free Colab GPU provides.
- The StyleGAN experiments are educational, compact demonstrations, not the complete NVIDIA StyleGAN implementation.
- CelebA access or download approval may be required.
- The RAG/LoRA experiment uses example documents; meaningful fine-tuning requires a prepared dataset and training.

See the README files inside each variant folder for variant-specific instructions.
