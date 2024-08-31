# lstm-sentiment-classifier

## Table of Contents

- [Dependencies](#dependencies)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
  - [Running the Project](#running-the-project)
  - [Example Usage](#example-usage)
- [Features](#features)
- [Configuration](#configuration)

## Dependencies

The following Python libraries are required for the project:

- `numpy`: For numerical computations.
- `pandas`: For data manipulation and analysis.
- `keras`: For building and training deep learning models.
- `tensorflow`: Backend for Keras and other deep learning tasks.
- `emoji`: For converting text to emojis.
- `matplotlib`: For plotting results and visualizations.
- `sklearn`: For data preprocessing and evaluation metrics.

## Installation Instructions

To run this project on your local machine, you will need to install the necessary dependencies and set up your environment. Follow the steps below to get started:

1. **Clone the Repository**: Begin by cloning this repository to your local machine.

   ```bash
   git clone https://github.com/justinliu23/emojifier.git
   cd emojifier
   ```

2. **Install Prerequisites**: Make sure you have Python 3.6 or higher installed on your machine. If not, download and install it from the [official Python website](https://www.python.org/downloads/).

3. **Create a Virtual Environment** (Recommended): It is recommended to use a virtual environment to avoid any potential conflicts with other Python packages.

   ```bash
   python -m venv emojify-env
   source emojify-env/bin/activate  # On Windows, use `emojify-env\Scripts\activate`
   ```

4. **Install Required Libraries**: Use the following command to install all required libraries:
   ```bash
   pip install numpy pandas keras tensorflow emoji matplotlib scikit-learn
   ```

## Usage

### Running the Project

1. **Launch Jupyter Notebook**: After installing the dependencies, launch the Jupyter Notebook server:

   ```bash
   jupyter notebook
   ```

2. **Open the Notebook**: Navigate to the directory containing the Jupyter notebook file (`Emojify.ipynb`) and open it in your browser.

3. **Execute the Cells**: Run the cells sequentially to execute the code and see the output.

### Example Usage

After setting up the environment and running the notebook, you can perform the following:

- **Load the Dataset**: The dataset `EMOJISET` will be used to train and evaluate the Emojifier models.

- **Train the Baseline Model (Emojifier-V1)**: Train a baseline model using word embeddings to map sentences to corresponding emojis.

- **Build a More Sophisticated Model (Emojifier-V2)**: Implement a more advanced model using LSTM (Long Short-Term Memory) networks for improved emoji prediction.

- **Evaluate Model Performance**: Compare the performance of both models on a test dataset and visualize the results.

## Features

- **Baseline Model (Emojifier-V1)**: A simple model using word embeddings for emoji prediction.
- **Advanced Model (Emojifier-V2)**: A deep learning model using LSTM networks for enhanced performance.
- **Visualization Tools**: Matplotlib plots to visualize model performance and results.

## Configuration

To modify the configuration of the project, you can adjust the following:

- **Training Parameters**: Change the parameters like learning rate, number of epochs, and batch size in the respective cells of the Jupyter notebook.
- **Model Architecture**: Modify the model architecture in the `Emojifier-V2` section to experiment with different LSTM layers or add other neural network components.
- **Dataset**: You can replace `EMOJISET` with your own dataset for training and evaluation. Ensure that the dataset is formatted similarly to `EMOJISET`.
