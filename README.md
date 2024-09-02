# Sarcasm Detection in Marathi Tweets using Indic-BERT and BiLSTM

## Overview

This repository contains a project focused on detecting sarcasm in Marathi tweets using a combination of Indic-BERT and BiLSTM. The model leverages state-of-the-art natural language processing techniques to classify tweets into sarcastic and non-sarcastic categories.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Indic-BERT Model**: Uses a pre-trained Indic-BERT model for encoding Marathi text.
- **BiLSTM Network**: Implements a Bi-directional LSTM layer for sequential modeling.
- **Custom Preprocessing**: Includes custom text preprocessing for Marathi language.
- **Comprehensive Evaluation**: Provides detailed evaluation metrics and confusion matrix visualization.
- **Custom Predictions**: Allows for predictions on new, custom text inputs.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/sarcasm-detection-marathi.git
    cd sarcasm-detection-marathi
    ```

2. **Install required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Preprocess the Data**:
   Ensure your data is in the correct format and preprocessed as per the instructions in `data_preprocessing.py`.

2. **Train the Model**:
   Run `train.py` to start training the model on your dataset.
   ```bash
   python train.py

3. **Evaluate the Model**:
  python eval_model.py

4. **Make Predictions**:
  python predict.py --text "Your tweet here"


## Training
The model is trained using the following hyperparameters:

Batch Size: 32
Learning Rate: 2e-5
Epochs: 10
Optimizer: AdamW
To customize the training process, modify the hyperparameters in train.py.

## Evaluation
The model's performance is evaluated using the following metrics:

Accuracy
Precision
Recall
F1 Score
Confusion matrix and other evaluation metrics can be visualized using evaluation_utils.py.

## Results
The model achieved a test accuracy of 75.24% on the validation dataset.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any features, improvements, or bug fixes.

1. Fork the repository.
2. Create your feature branch: git checkout -b feature/your-feature-name
3. Commit your changes: git commit -m 'Add some feature'
4. Push to the branch: git push origin feature/your-feature-name
5. Open a pull request.
