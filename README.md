# Voice-Recognition  
Your company accepts payments over the phone for its services and is now in the process of automating this task. As the sole data scientist on your team, your task is to build and train a voice recognition algorithm to record the customer's credit card number.  (Voice Recognition of 0-9)  
  
    
    
*   Model 1(75.72%): use tf.audio.decode_wav to decode the audio file 
  
*   Model 2(78.70%): Include 6 classifiers. `Classifier 1` is to distinguish [0], [9];<br> `Classifier 2` is to distinguish [1], [8]; <br>
`Classifier 3` is to distinguish [2], [7];  
`Classifier 4` is to distinguish [3], [6];  
`Classifier 5` is to distinguish [4], [5];  
then, transfer all the models information into `Classifier 6`, it could recognize [0]~[9]
  
*   Model 3(90.60%): Use the decision tree architecture and convert waveforms to spectrograms
