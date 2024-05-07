# Neural Network Challenge - Employee Attrition & Department Prediction

## Introduction

This repository contains the source code and documentation for the neural network challenge aimed at predicting employee attrition and optimal department allocation. Developed as part of the Module 19 Challenge for Columbia University's AI Bootcamp, this project utilizes advanced neural network architectures to analyze employee data and predict outcomes that assist HR in strategic decision making.

## Repository Structure

- `README.md`: This file.
- `attrition.ipynb`: Jupyter notebook containing all the preprocessing, model building, training, and evaluation.

## Getting Started

### Prerequisites

- Python 3.8 or higher.
- Libraries: pandas, numpy, sklearn, tensorflow/keras.
  Install the required libraries using the following command:
  ```bash
  pip install pandas numpy sklearn tensorflow
  ```

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/neural-network-challenge-2.git
   ```
2. Navigate to the cloned directory and open the Jupyter Notebook:
   ```bash
   cd neural-network-challenge-2
   jupyter notebook
   ```

## Usage

- Open `attrition.ipynb` in Jupyter Notebook or Google Colab.
- Run the cells sequentially to preprocess the data, build the model, and evaluate the results.

## Data Description

The dataset contains various attributes of employees that are used to predict attrition and the best-suited department for each employee. The dataset includes attributes like Age, Distance from Home, Education, Job Involvement, Hourly Rate, etc.

## Model Architecture

The model architecture includes a shared input layer followed by two branches:
- One branch for predicting attrition (binary classification).
- Another for predicting the department (multi-class classification).

The model uses ReLU activations for hidden layers and softmax/sigmoid activations for output layers of department and attrition predictions, respectively.

## Training

The model is trained using the Adam optimizer, with binary crossentropy and categorical crossentropy as the loss functions for the attrition and department branches, respectively. Training involves 75 epochs with a batch size of 32.

## Evaluation

Model evaluation is done based on accuracy metrics for both outputs. The detailed results and analysis are provided in the Jupyter Notebook.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit pull requests to propose enhancements or fixes.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

- Ken Stager - kenstager@hotmail.com
- Project Link: [https://github.com/KenStager/neural-network-challenge-2](https://github.com/KenStager/neural-network-challenge-2)

## Acknowledgements

- Columbia University AI Bootcamp Staff
- TensorFlow and Keras Libraries
- sklearn for providing robust preprocessing and model evaluation tools
