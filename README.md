# Disclaimer
This is a group project implemented along with JayantSharma777 and sarthakdewan1601.

# Data-Augmentation-Techniques
Machine learning in today's era is influencing various different features on various different products. Still, there are many low-resource task scenarios where performance of ML based models are not good enough. Aim of this project is to analyze and compare different data augmentation techniques for a benchmark dataset and build a model that can best perform on this dataset for text classification tasks.
<br>
## Techniques Used:

1) Easy Data Augmentation :-Studied and implemented easy data augumentation technique that involves 4 major operations that are Synonym Replacement(SR),  Random Insertion(RI),  Random Deletion(RD) and Random swap(RS).  

2) Tf-idf score and word embeddings: Studied about tf-idf,bert and various pretrained word embeddinds like Word2Vec, GloVe, FastText, Sent2Vec. After studying we implemented it by initially calculating the tf idf score and replacing the words with low tf idf score with the most similar word in the embedding space and hence increased the dataset. 

3) Text Augmentation using Back Traslation via MarianMT Transformer- We used a HuggingFace model to implement back translation in 3 differenent Romance Languages that are French, Espanol and Latin. We had 3 different models and compared the accuracy of the augmented data with the original on the basis of Text Classification using Gausian Naïve Bayes.

# Accuracy Score based on Back Translation MarianMT model:
## Original vs Augmented
### Using Target Language as Spannish

![image](https://user-images.githubusercontent.com/75779183/208244492-bb80d6ca-e4c9-410b-ba11-06de671946b4.png)

### Using Target Language as Latin

![image](https://user-images.githubusercontent.com/75779183/208244551-276551b0-db61-4dde-a9f8-1da0a29d9c9b.png)


# Accuracy score based on TF-IDF and Pretrained Glove Word embeddings

![image](https://user-images.githubusercontent.com/75779183/208244659-75ffd890-accf-4a92-a811-4125937fa993.png)

# Results
The accuracies increased with the augmented datasets and hence proved our technques right.The next part of our project is to make a tool with these models trained on much larger datasets so that a better augmentation can be generated. This tool will generate a augmentation of any text we input in it which will be meaningfull as well.

