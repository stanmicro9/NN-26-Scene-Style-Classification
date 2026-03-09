# NN 26 Scene Style Classification

The goal of this project is to train deep learning models capable of classifying indoor scenes into different design styles based on their visual characteristics, for the NN 26 Scene Style Classification Kaggle competition.

The repository includes separate Jupyter Notebooks for training, evaluating, and generating predictions using various state-of-the-art computer vision models:

* **ResNet** (`resnet.ipynb`)
* **Vision Transformer (ViT)** (`vit.ipynb`)
* **ConvNeXt Base** (`convnext-base.ipynb`)
* **DINOv3** (`dinov3.ipynb`)

## Setup and requirements
1. Make sure you have Python installed. It is recommended to use a virtual environment.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Downloading the dataset
Ensure that you have set up your Kaggle API key (a `kaggle.json` file placed in your `~/.kaggle/` directory).

Run the following Kaggle CLI command at the root directory of this project to download the competition dataset:
   ```bash
   kaggle competitions download -c nn-26-scene-style-classification
   ```
Once the download finishes, unzip the file within the same root directory. The directory structure will extract naturally into the current directory.
