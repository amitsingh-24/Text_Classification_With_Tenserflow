# Text_Classification_With_Tenserflow
# Text Classification with TensorFlow and TensorFlow Hub

This project demonstrates text classification using TensorFlow. The model is trained to classify sentiment in IMDB movie reviews using a pre-trained embedding layer and a simple neural network.

---

## File Structure
- **`LICENSE`**: Project license.
- **`README.md`**: Project documentation.
- **`Text_Classification_with_Tensorflow.ipynb`**: Jupyter Notebook containing the full implementation of the text classification model.

---

## Features
- **Pre-trained Embeddings**: Leverages a pre-trained text embedding from TensorFlow Hub for efficient representation of textual data.
- **Binary Sentiment Classification**: Classifies IMDB movie reviews as positive or negative.
- **Transfer Learning**: Fine-tunes a pre-trained model for text embeddings.
- **Metrics Visualization**: Displays training accuracy and loss for analysis.
- **High Accuracy**: Achieves robust accuracy on the IMDB dataset.

---

## Dataset
The IMDB movie review dataset is loaded using `tensorflow_datasets`. It includes:
- **Training Set**: 25,000 examples (split into 15,000 training and 10,000 validation samples).
- **Test Set**: 25,000 examples.

---

## Installation

### Dependencies
- TensorFlow
- TensorFlow Hub
- TensorFlow Datasets

Install the required packages:

```bash
pip install tensorflow tensorflow-hub tensorflow-datasets

