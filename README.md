# ART_GENERATION_USING_NST
An implementation of Neural Style Transfer (NST) using TensorFlow and VGG19 to create artistic images by combining the content of one image with the style of another
# Neural Style Transfer (NST)

This repository contains a Python implementation of Neural Style Transfer (NST) using TensorFlow and the VGG19 model. NST is a technique that blends the content of one image with the artistic style of another to generate a new, unique image.

## Features
- Uses a pre-trained VGG19 model for feature extraction.
- Computes content and style losses for image blending.
- Supports iterative optimization to generate stylized images.
- Includes adjustable hyperparameters for controlling content-style tradeoff.

## Requirements
- Python 3.7 or later
- TensorFlow 2.x
- NumPy
- Pillow
- Matplotlib
- SciPy

Install dependencies using:
```bash
pip install -r requirements.txt

## Key Features

Pre-trained VGG19: Extracts content and style features.
Customizable Blending: Adjust weights for content and style.
Iterative Optimization: Minimizes total loss for artistic results.
Real-Time Visualization: View progress during optimization.
Flexible Inputs: Works with any content and style images.


## Components Used
VGG19 Model: For feature extraction.
TensorFlow: Framework for implementation.
Content & Style Images: Input images for blending.
Loss Functions: Content, style, and total loss.
Visualization: Matplotlib and Pillow for image handling.
Optimization: Gradient descent to refine outputs.

## How It Works
1. Clone the repository: git clone https://github.com/yourusername/nst-tensorflow.gitcd nst-tensorflow
2. Run the notebook Art_generation_using_NST.ipynb:

Provide paths to your content and style images.
Adjust hyperparameters like alpha (content weight) and beta (style weight) as needed.
Generate and save the stylized image.
Content and Style Images: Provide two input images—one for content and one for style.
VGG19 Feature Extraction: The VGG19 model is used to extract features for computing content and style representations.
Loss Computation:
Content Loss: Ensures the generated image retains the structure of the content image.
Style Loss: Matches the texture and style from the style image.
Optimization: Combines content and style losses into a total loss and minimizes it using gradient descent.


## SCREENSHOTS :
CONTENT IMAGE :
<img width="367" alt="image" src="https://github.com/user-attachments/assets/49d377c0-94fc-4110-b52d-c58a4d1e2ceb" />
STYLE IMAGE :
<img width="344" alt="image" src="https://github.com/user-attachments/assets/b6a887ee-e769-475e-9443-30166fff568b" />
GENERATED IMAGE :
<img width="796" alt="image" src="https://github.com/user-attachments/assets/40868d87-9b8a-429c-a281-e4769176c5d3" />

