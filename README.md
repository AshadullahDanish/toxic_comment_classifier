# Toxic Comment Classifier 💬🤖

## Introduction 🌐📢

Online forums and social media platforms provide individuals with a platform to express their thoughts, opinions, and engage in discussions. However, this freedom of expression sometimes leads to the presence of explicit and offensive language in comments, which can be harmful and offensive. This project focuses on building a multi-headed model capable of detecting different types of toxicity, including threats, obscenity, insults, and identity-based hate.

## Problem Statement ❓💡

The goal is to develop a robust machine learning model that can automatically classify comments into various categories of toxicity. This classification helps in identifying and filtering out offensive language, protecting internet users from online harassment and cyberbullying.

## Workflow 🔄🛠️

1. **Data Acquisition:** The dataset for this project is obtained from the Toxic Comment Classifier competition hosted on Kaggle by Jigsaw/Conversation AI. It includes both the training and test sets.

2. **Data Pre-Processing:** Cleaning and preparing the data for model consumption. This involves handling missing values, text cleaning, and exploring efficient methods for cleaning textual data.

3. **Feature Engineering:** Extracting relevant features from the text data, enhancing the model's ability to understand and classify toxic comments.

4. **Model Building:** Utilizing two different deep learning models, including traditional LSTM and a hybrid LSTM-RNN model. Leveraging fastText's pre-trained word embeddings for transfer learning.

5. **Model Evaluation:** Evaluating the performance of the models during the training phase and comparing the results obtained from the competition website.

## Conclusion 🏁📊

The project concludes that the traditional LSTM model outperforms the hybrid LSTM-CNN model for the Toxic Comment Classification use-case. The next steps involve deploying the LSTM model as the backend for a web application that assesses the toxicity of user-provided comments.

## Key Learnings 🧠🚀

- Working with different deep learning models: RNN, LSTM, and LSTM-RNN hybrid model.
- Implementing models on a Natural Language Processing use-case.
- Efficient methods for cleaning textual data.
- Understanding word embedding concepts and the advantages of pre-trained word embeddings.

## Next Steps 🚀🔧

The next phase of this project involves deploying the LSTM model on GCP, serving as the backend for a web application. Part II of this blog provides a detailed walkthrough of the deployment process.

Feel free to explore and contribute to this project!

## How to Use 🚀🔍

1. Clone the repository:

   ```bash
   git clone https://github.com/AshadullahDanish/toxic_comment_classifier.git
   cd toxic_comment_classifier
   ```


2. Explore the Jupyter notebooks for data processing, model building, and evaluation.

3. Contribute to the project and share your insights!

Thank you for checking out the Toxic Comment Classifier project. For any questions or feedback, please contact cloud.data.danish@gmail.com .

**Happy coding!** 🚀👩‍💻
