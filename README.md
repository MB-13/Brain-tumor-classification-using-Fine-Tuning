# Brain-tumor-classification-using-Fine-Tuning
I have used VGG16 as a base model and used optuna for finding the best hyperparameter like number of unfreezed layers, learning_rate, number of layers and units in fc layer.<br>
The accuracy can be increased by adding more unique data for training other then augmented data<br>
It got an accuracy of maximum 83% which can be increased with good resources and good load of labelled data.
<br><br>
Then in brain-tumor-2 I have retrained the same dataset but this time by creating same architecture with functional api rather than using keras Sequential model. And it had increased the accuracy to around 92%.
<br><br>
authour :- Mahavir Bharadwa
