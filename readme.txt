                                          CLASSIFYING RADIO SIGNALS USING CONVOLUTIONAL NEURAL NETWORKS
                                       
The dataset for radio signal is captured at ALLAN TELESCOPE, SETI. SETI stands for Search for Extraterrestrial Intelligence is a collective term for scientific searchesfor intelligent extraterrestrial life, for example, monitoring electromagnetic radiation for signs of transmissions from civilizations on other planets.

The signals captures are generally time series signal. Here proposed a Deep learning approach to classify radio signals into one of the 7 given categories. We first analyze the SETI dataset and visualize these radio signals by using 2D Spectrograms. The major goal of the project is to find a robust signal classification algorithmthat could further assist the E.T. radio communication

OBJECTIVES:
        1) Understanding the Radio-Signal Simulation Data or SETI Data
        2) Loading & Preprocessing the dataset to get data visualisations
        3) Visualizing the signal data using 2D spectrograms
        4) Creating a CNN model
        5) Classifying the SETI signals into various categories.
        6) Evaluating the CNN model 
        7) Implementing the Transfer Learning using EfficientNet
        8) Evaluating and comparing the  the results

RESULTs:
1) Created a CNN classfier from scratch using Keras API in Tensorflow 2.0
       no of epoch=50
      train accuracy = 61.95%
      test accuracy= 63.57%

2) Utilised state of the art pretrained model "EfficientNet v2" using transfer learning approach.
        no of epoch=5
     model parameter nontrainable
                        Train accuracy= 73.45% 
                        Test accuracy= 69.23%
     model parameter trainable              
                        Train accuracy= 87.77% 
                        Test accuracy= 80.43%
        
