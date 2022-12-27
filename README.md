# Sentiment Prediction through Deep Neural Network
Nowadays, people rarely have time to finish all movies, even the latest one, therefore movie reviews become a choosing standard. Having a high accuracy on 
sentiment prediction of movie reviews, people can save their time even more by not reading each single review and still can know others’ attitude on those 
movies. 

We trained a Multi-layer neural network with IMDB data imported from Keras. Even the dataset had been already processed, word embedding 
and split validation dataset from training dataset were still necessary. For increasing the accuracy of our model without overfitting, we changed parameters such as learning rate, epoch, and adding more hidden layers with proper dropout rates between them. Finally, two-hidden-layer neural network with adjusted parameters got a higher model accuracy around 95% with a higher validation accuracy around 88% before overfitting.
