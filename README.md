#  Face Emotion Recognition

![Image_sample11](https://user-images.githubusercontent.com/99022806/236693692-a6cdbc06-f943-4720-9eed-7a73afdf40fb.png)

# Project Description
Build a deep learning model which detects the real time emotions of students through a webcam and gives the real time aggregated feedback to the instructor about the class so that instructor can understand if the students are able to grasp the topic according to students expression or emotions using CNN model.
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.
The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 7,178 examples.

# Model Structure
## CNN 
![download cnn2](https://user-images.githubusercontent.com/99022806/236639918-e061640e-d9cf-4dee-8637-e9ee446b8ecc.png)
![model cnn](https://user-images.githubusercontent.com/99022806/236639951-9ed5c936-e592-466a-a561-4e250e2813a3.png)  

# Output 
1. model.h5 - Model contains information about the emotions of the train set, such as the Happy, Angry and so on.
2. Video and pics - which contains the output of detecting emotions through live webcam.

# Conclusion
1. There are seven facial expression (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 7,178 examples.
2. The CNN model was chosen because it had the highest accuracy 73.40 perent and Resnet model's accuracy was around 63.
3. As a result, we save CNN model and use it to predict facial expressions.
4. Since, the emotion counts of disgust and surprise images are less therefore on local webcam it hardly detect those emotions.
5. Our model can successfully detect face and predict emotion on live feed as well as on Video.
