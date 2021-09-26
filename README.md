# Dog Breed Classifier
![dbc](https://miro.medium.com/max/1200/0*ey6drJha0Jol63fM)
[blogpost](https://adelabuhashim.medium.com/dog-breed-classifier-3fc658e05282)

 This project uses Convolutional Neural Networks (CNNs)! In this project.  

## Acknowledgement
- Udacity DLND and DSND.

## Motivation
I will build a pipeline to process real-world, user-supplied images. Given an image of a dog, My algorithm will identify an estimate of the canine’s breed. If an image of a human is supplied, the code will identify the resembling dog breed.



## Project Parts
   -  Import Datasets
   - Detect Humans
   - Detect Dogs
   - Create a CNN to Classify Dog Breeds (from Scratch)
   - Create a CNN to Classify Dog Breeds (using Transfer Learning)
   - Write My Algorithm
   - Test My Algorithm

 
## Libraries
- numpy
- glob
- cv2                
- matplotlib
- tqdm
- torch
- torchvision
- PIL 
- os
- re

## Results 
### Human Model (CV)
- human_files have 98% of human face 
- dog_files have 17% of human face
### Dog classifier Model (CNN ResNET50)
- human_files have 0% of dog face
- dog_files have 93% of dog face
- Test Loss: 0.516951
- Test Accuracy: 85% (714/836)
