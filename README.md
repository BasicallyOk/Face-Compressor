# CISC452-Project
Autoencoder for compressing and decompressing faces

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