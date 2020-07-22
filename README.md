# Fist and Palm detector
#### Detects if a person is showing a palm or a fist in real-time.


This is a simple image classification model made using Google's Teachable Machine and deployed with javascript to run in the browser.

[Try it live!](https://kushanksriraj.github.io/fist-palm-detector)

### Working
The model is run on the frames captured from the web camera. Then the model predicts the probability for each image that it has been trained on.  
If the probability of an image is higher than 65%, it classifies it as that image type (here, an image of a fist or a palm).


### Further development
Of course this is a simple model but the concept can be used to implement real world use cases like detecting lung infections from   
x-ray images of lungs, detecting a poacher in a reserved forest. Imagination is the limit!
