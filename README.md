# Fashion MNIST GAN Implementation

An implementation of a Generative Adversarial Network (GAN) trained on the Fashion MNIST dataset. The model is designed to generate realistic fashion images using deep learning techniques. The implementation is optimized for execution on Google Colab GPU.

## Features
- GAN model with a generator and discriminator.
- Convolutional layers with batch normalization for stable training.
- Fashion MNIST dataset preprocessing and training pipeline.
- Default training setting: 50 epochs.
- Implemented in Jupyter Notebook (.ipynb) format for seamless execution in Google Colab.

## How to Run
1. Open `train.ipynb`.
2. Install the required dependencies by running:
   ```sh
   !pip install tensorflow tensorflow-gpu matplotlib tensorflow-datasets ipywidgets
   ```
3. Execute the notebook cells sequentially to train the GAN.
4. The generated images will be displayed and saved for evaluation during training.


