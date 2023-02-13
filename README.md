# Deep_Learning_Seq2Seq
Sequence to Sequence (often abbreviated to seq2seq) models is a special class of Recurrent Neural Network architectures that we typically use (but not restricted) to solve complex Language problems like Machine Translation, Question Answering, creating Chatbots, Text Summarization, etc.

Seq2Seq is a type of Encoder-Decoder model using RNN. It can be used as a model for machine interaction and machine translation.
- By learning a large number of sequence pairs, this model generates one from the other.

## About:

Automatic text translation (ATT) has become very popular among researchers. Natural Language Processing and Machine Learning are critical applications of ATT. Translations are classified into two types based on how they are generated: extractive and abstractive. In this project, we have implemented the Hindi text translation. 

Neural networks like RNN, LSTM, GRU that works on a sequence as inputs like a sequence of English sentence in our case. So Seq2Seq model is a representation of these special neural networks. The Seq2Seq model has two parts one is called an encoder and the other is called a decoder and as the name suggests encoder encodes our input English sentence and decoder decodes these encoded English sentence into Hindi sentence.

<img width="1320" alt="Screenshot 2023-02-13 at 11 38 42 AM" src="https://user-images.githubusercontent.com/118846871/218383565-415974fe-acd5-4f36-9a4b-1b3ec182c468.png">


### Model performance:

The performance of the model is good as compared to the amount of data used to train the seq2seq model I have got the accuracy of 74.88% for a model trained on hin.txt dataset for 100 epochs.
The limitation of the simple seq2seq model is that it is not able to translate a lengthy sentence that efficiently.
