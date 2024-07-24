# ChatWithMe

This repository contains a chatbot implemented in a Jupyter Notebook using TensorFlow and NLTK.

## Table of Contents

- Installation
- Usage
- Model Training
- File Descriptions
- Contributing
- License

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ChatWithMe.git
    cd ChatWithMe
    ```

2. Open the Jupyter Notebook:
    ```bash
    jupyter notebook ChatWithMe.ipynb
    ```

## Usage

1. Mount your Google Drive:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```

2. Set the data root path:
    ```python
    data_root='/content/drive/My Drive/ChatBot'
    ```

3. Run the cells in the notebook to train the model and interact with the chatbot.

## Model Training

The model is trained using the following steps:

1. **Data Reading and Cleaning**:
    - Read the `intents.json` file and preprocess the data.
    - Tokenize and lemmatize the text.

2. **Feature Engineering**:
    - Create a bag of words representation for the input text.

3. **Model Training**:
    - Train a neural network using TensorFlow.

## File Descriptions

- `ChatWithMe.ipynb`: The main Jupyter Notebook file containing the chatbot implementation.
- `intents.json`: The dataset containing the intents and responses for the chatbot.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
