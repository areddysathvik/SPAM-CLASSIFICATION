# Spam Classification Project

This repository contains code for a spam classification project that uses three different models (SVM, Artificial Neural Network, and Naive Bayes) and a majority voting system to predict whether an email is spam or not. The project leverages natural language processing techniques and machine learning models for accurate classification.

## Project Overview

Spam emails are a common problem, and accurately identifying them is crucial to maintain inbox cleanliness and security. This project addresses the spam classification problem by employing three separate machine learning models and combining their predictions using a majority voting system. The goal is to enhance the classification accuracy and robustness of the system.

## Models Used

1. **Support Vector Machine (SVM)**: SVM is a powerful classification algorithm known for its ability to handle high-dimensional data and complex decision boundaries.

2. **Artificial Neural Network (ANN)**: ANN is a deep learning model inspired by the human brain's neural structure, capable of learning intricate patterns from data.

3. **Naive Bayes**: Naive Bayes is a probabilistic algorithm based on Bayes' theorem and is often used for text classification tasks.

## Majority Voting System

The three individual models make predictions on a given email. These predictions are then combined using a majority voting system to arrive at a final classification decision. This ensemble approach helps to mitigate individual model biases and enhance the overall accuracy.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/areddysathvik/SPAM-CLASSIFICATION.git
   cd SPAM-CLASSIFICATION ```

    Install the required dependencies:

    bash

   ```pip install -r requirements.txt```

Run the spam classification script:

bash

    python spam_classification.py

## Usage

To use the project, provide email text as input to the spam_classification.py script, and it will output whether the email is spam or not.


## Contributing

Contributions to this project are welcome! Feel free to open issues and pull requests for bug fixes, improvements, or new features.

#License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, please reach out to Your [areddisathvik@gmail.com].
