GENAI PRACTICALS - CPU-FRIENDLY JUPYTER EDITION

Designed for a college PC with Intel i7 CPU and no dedicated GPU.

HOW TO USE
1. Extract the ZIP.
2. Open Jupyter Notebook or JupyterLab.
3. Open an experiment .ipynb file.
4. Run cells from top to bottom (Shift+Enter).
5. Use Python 3.10 or 3.11 if possible. Internet is required for package/model downloads.

IMPORTANT HONEST LIMITATIONS
- Experiments 1, 2, 3, 5 and 9 are designed to run on CPU (model downloads may take time).
- Experiment 6 is a tiny DCGAN demonstration with a small CelebA sample; it will still train slowly.
- Experiment 7 is a compact StyleGAN-inspired teaching demo, not the full NVIDIA StyleGAN.
- Experiment 4's default cell is a CPU-safe prompt/image demonstration. The actual Stable Diffusion code is optional and commented out because CPU inference is extremely slow.
- Experiment 8's default cell creates a short playable tone demo. Actual pretrained MusicGen is optional and commented out due to CPU inference cost.
- Experiment 10's default cell creates a prompt-labelled MP4 slideshow. It is NOT actual neural text-to-video generation; pretrained video models generally require a GPU.
- If your examiner requires actual pretrained image/music/video generation, use Google Colab or a GPU computer for those experiments.
- CelebA may require dataset access approval or download setup through TensorFlow Datasets.
