# Attention-based-Aspect-Sentiment-Analysis
Tensorflow implementation of aspect and context based attention netowrk for aspect sentiment analysis

## Getting Started
* Download Glove 840B http://nlp.stanford.edu/data/glove.840B.300d.zip and put it in data/
* run main.py for training & evaluation and epoch wise prediction on test data
* Preprocessed data is stored in data/
* model.py contains model architecture
* logs for tensorboard summary visulaization


### Prerequisites

* Tensorflow on colab
* Glove 300D word embeddings from http://nlp.stanford.edu/data/glove.840B.300d.zip and put it in data/
* spacy 

## Model Architecture 
![image](https://user-images.githubusercontent.com/23417882/73246567-f22b0800-41d4-11ea-88d9-bdad8b6b19d7.png)


### Preprocessing
Preprocessed files in data dir

## Further Work
* Replace LSTM layers with Transformers(Convert it to BERT downstream task)
* Fastext and context aware dynamic meta embeddings for out of vocab words
* External datasets from Twitter, restaurant reviews to increase model performance* 
* NASNet for model hyper parameter tunning

## Authors

* **Ankit Yadav**
