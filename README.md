# Pytorch-Fine-Tune-BERT-for-Text-Classification
Download and import the Quora Insincere Questions dataset.
Classify the dataset into neutral and hostile questions, considering only questions with a sentence length of fewer than 64 tokens.
Initially, download the pre-trained "bert-base-uncased" model.
Use the Weights & Biases (wandb) platform to perform the training.
This is an excellent practice for learners who want to understand how large language models (LLMs) are trained.
Code: https://github.com/Moore-Z/Pytorch-Fine-Tune-BERT-for-Text-Classification/blob/main/BERTPytorch.ipynb

# Dataset Quora Insincere Questions dataset 
(0 means neutral quesiton, 1 means hotile question) 
![image](https://github.com/user-attachments/assets/6b4f8bf9-93ac-4ea0-bc11-a980ad085a53)



# Result
I found it perform really good if the number of training set get increased. If you want to run the code one free Colab version, 
You change the batch size the learning rate. It can bring good result as well. Current setting could bring 98% accurate rate for 
validation data. 
![image](https://github.com/user-attachments/assets/f9600b22-ac34-4854-b225-f9fd3428d45a)

