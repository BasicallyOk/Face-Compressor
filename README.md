# CISC452-Project
Investigating deep learning methods for compressing and decompressing faces

# Results
Refer to the [paper](https://docs.google.com/document/d/1AIiq580SGVutih1R2eXlf_lk4IIEy8pPtDl6SzSJS_o/edit) for more details.

Reconstructed Images by the Deep Convolutional Generative Adversarial Network
![Reconstructed Images by the DCGAN and the originals](/visualization/dcgan.png)

Reconstructed Images by the Convolutinal Variatinoal Autoencoder
![Reconstructed Images by the DCGAN and the originals](/visualization/cvae.png)

# Instructions
### Environment Setup
Skip 2 and 3 if you're lazy/a maniac. 
1. Go to project root
2. Set up environment by running `python -m venv .venv` or `python3 -m venv .venv`
3. Run `source .venv/bin/activate` on Linux and MacOS, `./venv/Script/activate` on Windows. 
4. Run `pip install -r requirements.txt`
### Dataset
1. Download the [celebA dataset](https://drive.google.com/drive/folders/0B7EVK8r0v71pbWNEUjJKdDQ3dGc?resourcekey=0-B5NA6Xcog-KfbFaNG5rUuQ&usp=drive_link)
2. Extract dataset to project root (optional, but will make your life easier)
3. Rename the dataset folder to `dataset` (also optional, but the skeleton code assumes it's called dataset)
4. Ensure there are no subfolders. The `dataset` folder should only contain images of faces.
