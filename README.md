# A Comprehensive Notebook on Fake News Prediction

## Table of Contents

- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Installation Instructions](#installation-instructions)
- [Resources](#resources)
- [License](#license)
- [Conclusion](#conclusion)
- [About Author](#about-author)

## Introduction

This project addresses the critical issue of fake news detection through thorough data analysis and machine learning. We perform a detailed examination of data distribution and analyze fake news labels using visualizations such as plots and word clouds. Statements are cleaned and analyzed to enhance label classification. The analysis extends to subjects, speakers, job titles, state information, party affiliations, and venues, with strategic groupings to improve label differentiation. Numeric data features are also assessed through visualizations. Multiple models are trained and evaluated, with a comprehensive comparison to identify the most effective approach. This notebook provides a robust framework for predicting fake news, combining advanced data analysis and predictive modeling.

### Fake News Label Distribution

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/d29e88a8-7f8a-4d46-bf21-f09c6c03ba3c)

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/4e20c4bd-9db5-412a-9c83-3ae0b532decb)

### Words which are in the barely-true news

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/4d9575e3-224c-4c56-8fdf-696559b8f2bb)

### Words which are in the half-true news

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/a02e6ecc-9388-4d45-a107-09b1e137a02e)

### Words which are in the mostly-true news

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/7f45fa6c-748f-4e55-8336-2b1bfc44aa37)

### Words which are in the TRUE news

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/c0f05976-65f0-4633-9077-3f7ee4bca6a4)

### Words which are in the False news

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/fcb0c501-e2e4-4495-808c-be0678aa13d6)

### Which are in the pants-fire news

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/61dfbc72-3cfd-4c04-8668-ea76944e7e02)

### Top 25 frequently words in news statement text

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/c4a2032f-97eb-4b8b-8450-96204cd62726)

### Distribution of the Subjects

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/7604bab5-a4b3-4016-95f3-5c73ea57e479)

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/67321489-ddda-48c2-81cb-7c39502755d4)

### Top 10 Speakers

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/e145ca93-36b5-4ea4-ae8a-3ee548c88324)

### Least 10 Speakers

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/9ca585fe-cbcd-4717-afff-8ac16d6af579)

### Distribution of Speaker's Job Title 

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/e1cc9ef0-05e6-40fb-a703-3b93b50d0bd9)

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/ce2d1564-8b3b-425e-83b5-db71934f6dfd)

### Top 10 states in the Data

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/d7af8af3-fd7b-451d-af3b-2c8ecf4f4a63)

### Least 10 states in Data

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/59d81f78-1cc1-46b0-8637-d3e4072cead4)

### Distribution of Party Affiliation

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/97c6f9b2-0760-45ca-8fa0-85417d4d77d9)

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/94ae2665-4d52-4f62-b01c-b7a8736a0b1d)

### Distribution of Venue

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/dbfbd6cf-7369-47a0-b00b-4d5eea7b89de)

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/50d6b11e-9057-4a6d-91bb-851737f7fc97)


## Random Forest

Average Confusion Matrix:

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/d007229e-064d-469d-bd21-c240d98b7134)

Total Average Accuracy of Random Forest Classifier is : 0.9123319970046504

## Naive Bayes

Average Confusion Matrix:

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/6001952d-d03d-4cec-a3b2-40b2e8f0d591)

Total Average Accuracy of Naive bayes is : 0.9990616141191161

## Neural Networks

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/ab75e740-225c-4932-8f88-f16d51b1a6a7)

Total Average Accuracy of Neural Network is : 0.9464310973295952

## Decision Trees

Average Confusion Matrix:

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/33b48872-564a-4eda-b617-67795ca615ec)

Total Average Accuracy of Decision Trees is : 0.8853491756214755

## Comparison of all Algorithms Results

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/22f42902-9980-431f-84d4-25495b4e3b5d)

![image](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/398fc7c3-2e98-40e9-98be-d7c751215ef3)

<img width="332" alt="image" src="https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/9175a6b0-9ebb-4392-868f-16218769d07d">


### Best Model is Naive Bayes because of accuracy and the conevrging time is also fast

<img width="344" alt="image" src="https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction/assets/149146155/7e794e2a-bff9-4c0d-b2ee-dfd5c39dbc0d">









## Environment Setup

**Prerequisites**: Ensure Python 3.6 or newer is installed on your system.

1. **Create a Virtual Environment**:
    - Install `virtualenv` if you prefer it over the built-in `venv` (optional):
        ```bash
        pip install virtualenv
        ```
    - Create the environment:
        - With `venv` (Python 3.3+):
            ```bash
            python -m venv env
            ```
        - Or, with `virtualenv`:
            ```bash
            virtualenv env
            ```
    - Activate the environment:
        - Windows: `env\Scripts\activate`
        - Unix/MacOS: `source env/bin/activate`
    - To deactivate: `deactivate`

2. **Dependencies**:
    Ensure all dependencies are listed in `requirements.txt`. Install them using:
    ```bash
    pip install -r requirements.txt
    ```

## Installation Instructions

To use this project, clone the repository and set up the environment as follows:

1. **Clone the Repository**:
    ```bash
    https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction.git
    ```
2. **Setup the Environment**:
    - Navigate to the project directory and activate the virtual environment.
    - Install the dependencies from `requirements.txt`.

## Resources

- **Kaggle Notebook**: [View Notebook](https://www.kaggle.com/code/muhammadimran112233/a-comprehensive-notebook-on-fake-news-prediction)
- **Dataset**: [View Dataset](https://www.kaggle.com/datasets/muhammadimran112233/liar-twitter-dataset)

## License

This project is made available under the MIT License.

## Conclusion

In this project, we have measured the progress of research under machine learning techniques and intelligent methods using LIAR data to detect fake news. We have looked into different datasets to find better data sets for experiments. Previous research showed more research on the LIAR dataset. So our experience also agreed that the LIAR dataset is the best, most accurate, and most reliable data source. After finalizing data sets and keeping in view our goal, we have implemented intelligent machine learning techniques and mentioned results in figures and tables. We found different results by using general data set. According to our sole purpose we have achieved maximum accuracy by using the homogenous nature of the classifier known as Random Forest, Neural Network, Decision Tree, and Naïve Bayes. We used the k-fold cross validation approach to make parts in k-fold 1, k-fold 2, k-fold 3, k-fold 4, and k-fold 5. All these algorithms are used for each k-fold and also calculate the running time for each. In the end, concluded that the Naïve Bayes algorithm outperforms as compared to the other algorithms due to its high evaluation measure values and convergence time.

## About Author

- **Name**: Muhammad Imran Zaman
- **Email**: [imranzaman.ml@gmail.com](mailto:imranzaman.ml@gmail.com)
- **Professional Links**:
    - Kaggle: [Profile](https://www.kaggle.com/muhammadimran112233)
    - LinkedIn: [Profile](linkedin.com/in/muhammad-imran-zaman)
    - Google Scholar: [Profile](https://scholar.google.com/citations?user=ulVFpy8AAAAJ&hl=en)
    - YouTube: [Channel](https://www.youtube.com/@consolioo)
- **Project Repository**: [GitHub Repo](https://github.com/Imran-ml/A-Comprehensive-Notebook-on-Fake-News-Prediction.git)
