# Capstone Project: Fake News Detector

![Fake News Detector](https://github.com/yourusername/yourrepository/blob/main/images/fake_news_detector.png)

## Overview

This project focuses on building a fake news detector using machine learning techniques. It leverages Amazon SageMaker for data exploration, model building, training, and deployment. The dataset used for this project is sourced from Kaggle and consists of both real and fake news articles.

## Dataset

The dataset used in this project can be found on Kaggle: [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

The `data` folder contains the downloaded data files from Kaggle.

## Project Steps

### Step 1: Data Exploration and Visualization

In the "Data Exploration and Visualization" Notebook, we perform exploratory data analysis and data cleaning. The cleaned data is then saved to an S3 bucket for further processing.

### Step 2: Model Building, Training, and Deployment

In the "Model Building, Training, and Deployment" Notebook, we initially attempted to use the Naive Bayes method for classification. However, this approach resulted in a failed accuracy score.

### Step 3: Text Generation for RNN and Training

In the "Text Generation for RNN and Training" Notebook, we utilize tokenized articles to train a Bidirectional LSTM model. The LSTM model yields promising results with a test accuracy score of 98%.

## Important Files and Folders

- `source_train` folder: Contains training scripts for Naive Bayes and LSTM methods.
- `helper.py` file: Contains several useful functions utilized throughout the project.
- `tokenizer.pkl` file: Contains a pickled version of the fitted Keras tokenizer used to preprocess data for the LSTM model.

## Usage

To replicate the project or experiment with different approaches, follow these steps:

1. Clone the repository.
2. Install the required dependencies specified in the `requirements.txt` file.
3. Navigate to each notebook and follow the instructions provided within.
4. Modify or extend the codebase as needed for your experimentation.

## Contributors

- Okunta Braide (https://github.com/yourusername)


## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, or distribute the code for your purposes.

## Acknowledgements

Special thanks to Kaggle for providing the dataset and to the creators of the libraries and frameworks used in this project.
