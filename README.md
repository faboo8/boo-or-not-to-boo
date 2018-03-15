# Too boo or not to boo -- that is the question

Small project to explore some ML algorithms for classification.

Task at hand: from certain (made-up) features (bone_length, rotting_flesh, hair_length, has_soul, color) I want to determine the type of the creature (Goblin, Ghost, Ghoul). 


## Classic Classifier
 
 Random forests, Naive Bayes, SVM all deliver around 70% accuracy. A grid search for SVM delivered an accuracy of aroud 77%. 
 Thus, these classifiers don't perform very well on the data set.
 
## Building a neural network
 
 I use tensorflow to build a simple neural network with 1 hidden layer.

