# Transfer-Learning-for-Fashion-MNIST

This project applies transfer learning using a pre-trained VGG16 model (from torchvision) fine-tuned on the Fashion-MNIST dataset for image classification.

## Key Features
- Base: VGG16 with modified classifier (output: 10 classes).
- Dataset: Fashion-MNIST (60k train images, 28x28 grayscale).
- Fine-tuned on GPU with Adam optimizer.
- Achieves ~92.86% accuracy on test set.

## Setup
1. Install dependencies: `pip install torch torchvision pandas matplotlib`.
2. Load Fashion-MNIST CSV and preprocess (normalize, reshape to 3-channel for VGG).
3. Train for 10 epochs (or more for better results).

## Results
- Test accuracy: 92.86%.
- Leverages pre-trained ImageNet weights for better generalization.
