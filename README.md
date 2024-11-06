# CIFAR-10 Image Classification

This project implements a Convolutional Neural Network (CNN) using TensorFlow to classify images from the CIFAR-10 dataset.

## Colab Notebook

You can run the code directly in Google Colab using the following link:  
[**Colab Link**](https://colab.research.google.com/drive/1O-J79rHS7Oh-OgaSAPzNQWSaO1dWUJOU?usp=sharing)

## Requirements

- Python 3.6 (min)
- TensorFlow
- Matplotlib
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/V8V88V8V88/cnn-image-classification.git
   cd cnn-image-classification
   ```

2. Install the required packages:
   ```bash
   pip install tensorflow matplotlib numpy
   ```

## Usage

1. Load and preprocess the CIFAR-10 dataset.
2. Train the CNN model on the training set and validate it on the validation set.
3. Evaluate the model on the test set to display accuracy.
4. Visualize the training history and model predictions.

## Training

To train the model, run the following command:
```bash
python CNNImageClassification.py
```

## Results

After training, the model's accuracy on the test set will be printed. Additionally, plots of the training and validation accuracy/loss over the epochs will be displayed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
