# Audio-MNIST-Classification - 

<br>
<br>

<h2><b><u>DATA - </u></b></h2>
<br>
A Large dataset of Audio MNIST, 30000 audio samples of spoken digits (0-9) of 60 different speakers.
<br>
data (audioMNIST)

![1](https://user-images.githubusercontent.com/73405735/138358629-5e4a7770-1b02-4ffc-b6a3-e39abbdad453.jpg)


* The dataset consists of 30000 audio samples of spoken digits (0-9) of 60 folders and 500      files each.

* There is one directory per speaker holding the audio recordings.
Additionally "audioMNIST_meta.txt" provides meta information such as gender or age of each speaker.

<br>
<br>

<h2><b><u>FILES IN THIS PROJECT</u></b></h2>
<br>

<b>1. <u>MNIST AUDIO PREPROCESSING.ipnb</u></b> -- 
<br>
<br>

* This Notebook contains the reading,data preprocessing,feature engineering and splitting data.

* In this project the features were extracted/constructed by using <b>Mel-Frequency Cepstral Coefficient</b> 

![imgg](https://user-images.githubusercontent.com/73405735/138358451-ebbcc28f-e1c8-4ca9-89c2-d36eba2984f2.png)

<br>
<b>2.<u>MNIST CLASSIFICATION MODELLING.ipynb</u></b> -- 
<br>
<br>

* This Notebook contains the modelling part using keras.
 
* I have used dense neural network for training and prediction.
