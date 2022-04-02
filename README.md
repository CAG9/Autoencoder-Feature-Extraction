# Autoencoder Feature Extraction


## Results:
Accuracy LogisticRegression Simple: 0.8939 <br>
Accuracy LogisticRegression With Autoencoder: 0.9242

![Loss](https://github.com/CAG9/Autoencoder-Feature-Extraction/blob/main/Autoencoderloss.png)

## Author: 
- Cesar Arcos-Gonzalez: cesar99ag@gmail.com

## License : 
MIT License

## Introduction:
An autoencoder is a type of artificial neural network used to learn efficient codings of unlabeled data. The encoding is validated and refined by attempting to regenerate the input from the encoding. The autoencoder learns a representation for a set of data, typically for dimensionality reduction, by training the network to ignore insignificant data (“noise”). 
<br>
The encoder can then be used as a data preparation technique to perform feature extraction on raw data that can be used to train a different machine learning model.

## Model: 
![Autoencoder](https://github.com/CAG9/Autoencoder-Feature-Extraction/blob/main/autoencoder_compress.png)

## Tools:
- Python
- Tensorflow 2
- Keras
- Scikit-learn
- Matplotlib


## Dataset:
- sklearn.datasets make_classification
