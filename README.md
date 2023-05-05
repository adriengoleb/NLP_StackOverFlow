# StackOverflow classification

The aim of this project is to develop a method for identifying which questions on the Stack Overflow website should be closed. To solve this problem, we propose using deep learning and neural network models to identify good candidates for closing.

The basis of our work is an article from Levi Franklin titled "Predicting Closed Stack Overflow Questions" : http://cs224d.stanford.edu/reports/lefrankl.pdf


To understand the elements we obtained, please follow the following steps:


1. Go to [https://drive.google.com/drive/folders/1jt8oipcC_61dJbt5d4YUEeZXsqGOk0OL?usp=sharing](https://drive.google.com/drive/folder /1jt8oipcC_61dJbt5d4YUEeZXsqGOk0OL?usp=sharing), to access to the exploited data for our study. They are also available from the hugging face website: https://huggingface.co/datasets/so_stacksample

2. [preprocessing_numeric_features.ipynb.ipynb](preprocessing_numeric_features.ipynb.ipynb) allows you to do the features engineering task and add additional numerical data.

3. [so_numeric_final.ipynb](so_numeric_final.ipynb.ipynb) allows to launch the learning tasks, test several word embeddings approaches, tune the parameters of our models and obtain results.

4. [graphs.ipynb](graphs.ipynb) shows the training and validation performances of each model we trained

