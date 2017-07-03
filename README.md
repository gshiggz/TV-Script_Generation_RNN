# TV-Script_Generation_RNN
This network uses a Recurrent Neural Network (RNN) to generate an original TV script from a subset of data based 
of 27 seasons of "The Simpsons".

This project was made by utilizing a subset of data from 27 seasons of "The Simpsons" for the purpose of creating 
a neural network that can generate original dialog by generalizing 27 seasons of script. This was accomplished by 
converting the words into integers and tokenizing the text, it was then passed through word embedding into the RNN in
batches. The network was created using Python 3, Tensorflow 1.0 and trained on a Floydhub GPU cloud instance.
