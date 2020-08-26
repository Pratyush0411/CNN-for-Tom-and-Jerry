# Emotion detector for Tom and Jerry video
*Dataset used from Hackerearth competition*
## Dataset: 
Train Tom and jerry.mp4 - video to train the model. Test Tom and jerry.mp4 - test video from competition
## Image extraction:
frame_extract.py extracts images from video at a fps = 5
## Model:
All python code including the model is stored in one Image classification.ipynb notebook. Please note there are  five categories of emotions - happy, sad, angry, surprised and unknown. Model was trained on 238 images and is a custom-built model without any transfer learniing
## Improvements:
Further improvements can be made to increase the train dataset by using *data augmentation* and *transfer learning* like VGG19 architeccture 
