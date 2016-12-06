# TorTracker
Track websites visited anonymously using Tor.

This program uses machine learning to Track websites visited using Tor. 

Although the data is encrypted, there are feature engineering techniques that can help in looking for patterns in the packets transmitted.

The code gives around 44% accuracy on the test dataset. (in predicting 10 different websites)

ToDo: We can use Recurrent Neural Networks with LSTM (and other deep learning techniques) to improve the accuracy, which automatically engineer the features. (Will upload this part next week)

Build_Tor_Data.ipynb : Script for creating the data by using Wireshark for sniffing the packets.

Train_data.ipynb : Trains a model with Support Vector Machine (Gaussian Kernel).

Please unzip traindatator.zip if you want to start the training right away without sniffing packets.
