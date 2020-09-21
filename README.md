CNN-from-scrath. 
Populer Mnist dataset has been used.

I have tried to create CNN from scratch with the help of KODLUYORUZ Applied Data Science 102 bootcamp instructor

This notebook includes the followings:
1)Creating Dataset, DataLoader, loss func, activation func, accuracy, forward propagation, backward propagation, pooling from strach, stride from scratch, filter from strach etc.
2)Feeding the model with the raw training set and getting result.- Feeding the model with the only dataset edge detected and getting result. Then- Feeding the model with the both of the train set in a concatenate format and getting result. 
3) Normalization for all of the models. (trn_x-mean_train)/std.  (valid_x-mean_train)/std
There is an exception for the model with the concatenated dataset when we normalize; (trn_x[:,0:784]-trn_x[:0:784].mean())/trn_x[:,0:784].std()   ...
