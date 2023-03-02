# Stroke-Identification

Estimation of strokes i.e backhand or fronthand serve using videos as the dataset. 

About Code: 

1. The videos are first cut into frames and are labelled accordingly. 
2. The cleaned and workable dataset is then used to be trained in the model. 
3. The labelled data is converted to the categorical form for dividing into the training and testing dataset.
4. Finally the categorical data is fed into the LSTM model for training and testing. 
5. The model is run over 100 epochs, and if the no is no improvement in the loss for 10 continuous epochs, it stops.

About data: 

1. The data is manually constructed and uploaded to the drive ("/content/drive/MyDrive/data"). 
2. Content is fetched from the drive and used for creation of the code.
