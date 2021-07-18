# Music-Genre-Classification
Model for classifying genre of the audio.
Data_preparation_py.py generates a json file which has the following data:
Mappings, labels & MFCC's. The file can be used for extracting mfcc's from the audio in the format .wav. Used Librosa for the purpose of extracting the MFCC's from the audio data. 
The MFCC's are then fed to the model.
Used a Convolutional Neural Network for the classification task.
The visualization of the graph is as follows:(For a single batch from train_loader)
![Music_Genre_Classifier](https://user-images.githubusercontent.com/64744264/126068273-b648ad8c-4bf1-4f64-969b-3967cb7cc302.png)

Used Libraries = pytorch, librosa, numpy, json, pandas, matplotlib
