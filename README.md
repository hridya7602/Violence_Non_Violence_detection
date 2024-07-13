# Violence_Non_Violence_detection
Violence and Non-Violence Detection System
This repository contains a Jupyter notebook implementing a violence and non-violence detection system using a MoBiLSTM (Modified Bidirectional Long Short-Term Memory) model. The model is trained on a small dataset and aims to classify sequences as violent or non-violent.

Table of Contents
Introduction
Dataset
Model Architecture
Installation
Usage
Results
Contributing
License
Introduction
The goal of this project is to build a system capable of detecting violent and non-violent sequences in video or other sequential data. The MoBiLSTM model is used due to its effectiveness in capturing temporal dependencies in sequential data. This repository provides the implementation details, training process, and evaluation of the model.

Dataset
The dataset used for training and evaluation consists of labeled sequences categorized as violent or non-violent. Due to the small size of the dataset, the model may require further training on a larger dataset for improved performance. The dataset should be preprocessed into a suitable format for input into the MoBiLSTM model.

Model Architecture
The MoBiLSTM model is a variation of the traditional BiLSTM, modified to enhance its performance on the specific task of violence detection. The architecture includes:

Embedding Layer: Converts input sequences into dense vectors.
Bidirectional LSTM Layers: Captures temporal dependencies in both forward and backward directions.
Fully Connected Layers: For classification based on the learned features.
Softmax Layer: Outputs probability scores for the violent and non-violent classes.
Installation
To run the notebook and train the model, you'll need to set up your Python environment with the necessary dependencies. Follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/violence-detection.git
cd violence-detection
Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
To use the notebook for training and evaluating the model, follow these steps:

Open the Jupyter notebook:

bash
Copy code
jupyter notebook
Open the MoBiLSTM_model.ipynb notebook.

Follow the instructions in the notebook to load the dataset, preprocess the data, train the model, and evaluate its performance.

Modify the parameters and experiment with different configurations to improve the model's accuracy.

Results
The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Given the small dataset, the results may vary and are subject to improvement with a larger and more diverse dataset. The final section of the notebook provides detailed evaluation results.

Contributing
Contributions to improve the model and dataset are welcome. Feel free to open issues or submit pull requests with improvements or new features.

License
This project is licensed under the MIT License. See the LICENSE file for details.
