
# **Sentiment Analysis in Malayalam using Deep Learning**

## **Project Overview**

This project aims to perform sentiment analysis on social media comments written in Malayalam. Due to the limited availability of resources for Malayalam sentiment datasets, the primary focus was on the meticulous collection and labeling of data, which formed the foundation for developing robust Machine Learning (ML) and Deep Learning (DL) models.

## **Motivation**

Understanding sentiment in regional languages like Malayalam is essential for local businesses, social media platforms, and various other applications. However, the scarcity of pre-labeled datasets in Malayalam posed a significant challenge, making this project crucial for advancing sentiment analysis in this language.

## **Key Project Highlights**

- **Dataset Collection**: The most significant step in this project involved gathering a diverse set of social media comments in Malayalam. This included manual collection from various online platforms and ensuring a wide representation of different sentiment types.
- **Data Labeling**: With the help of native Malayalam speakers, each comment was manually labeled into sentiment categories such as positive, negative, and neutral. This step was critical in creating a high-quality dataset for training the models.
- **Model Development**: Implemented and compared various ML and DL models to classify sentiments, including:
  - **Traditional ML Models**: Logistic Regression, SVM
  - **Deep Learning Models**: LSTM, BERT
- **Evaluation and Tuning**: After training, the models were rigorously evaluated and fine-tuned to achieve optimal performance.

## **Technologies Used**

- **Programming Language**: Python
- **Machine Learning Libraries**: scikit-learn, Pandas, NumPy
- **Deep Learning Libraries**: TensorFlow, Keras, PyTorch
- **NLP Tools**: NLTK
- **Visualization**: Matplotlib

## **Results**

- The BERT model achieved the highest accuracy of XX% on the test dataset, outperforming other models in understanding the context of Malayalam language comments.
- The project demonstrated the effectiveness of DL models in handling regional languages, particularly in sentiment classification tasks.

## **Challenges and Future Work**

- **Dataset Challenges**: The lack of existing datasets required significant manual effort in collecting and labeling data, which was both time-consuming and challenging.
- **Expand Dataset**: Future work will focus on expanding the dataset and including more nuanced sentiment categories.
- **Improved Fine-tuning**: Further fine-tuning of models, especially BERT, to enhance accuracy and generalization.
