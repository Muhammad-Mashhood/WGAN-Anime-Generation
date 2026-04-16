# WGAN Anime Generation

This repository contains an implementation of **WGAN-GP (Wasserstein GAN with Gradient Penalty)** for generating high-quality anime-style images.

## Features
- **WGAN-GP Architecture**: Utilizes Wasserstein distance with gradient penalty for improved training stability and better image quality compared to traditional GANs.
- **Deep Convolutional Structure**: Generator and Discriminator based on DCGAN architectures.
- **Support for Anime Datasets**: Specifically designed for anime face datasets.
- **PyTorch Implementation**: Efficient training leveraging GPU acceleration.

## Repository Contents
- `gans-dcgan-wgan-gp.ipynb`: Main notebook featuring the WGAN-GP implementation and training process.
- `image-to-image.ipynb`: Additional experiments with image-to-image translation models.
- `LICENSE`: MIT License.

## Prerequisites
- Python 3.x
- PyTorch
- Torchvision
- Matplotlib
- tqdm
- PIL

## Usage
1. Clone the repository.
2. Open `gans-dcgan-wgan-gp.ipynb` in a Jupyter environment (or Kaggle/Colab).
3. Ensure the dataset is correctly path-mapped.
4. Run the cells to train the model and generate images.

## Model Training
The model is trained using the **Anime Faces** dataset. The training loop includes:
- Gradient penalty calculation to enforce the Lipschitz constraint.
- Generator and Discriminator updates at different ratios (typical of WGAN).
- Real-time visualization of generated samples.

## Contributors
- Co-developed by [Muhammad Mashhood](https://github.com/Muhammad-Mashhood) and Muhammad Hassan.

## Acknowledgments
- Special thanks to **Muhammad Usama** for his invaluable guidance throughout the project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
