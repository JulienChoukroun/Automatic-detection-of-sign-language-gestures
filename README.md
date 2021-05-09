This project is carried out as part of the engineering cycle training (second year) of the Polytechnic School of the Université Côte d'Azur.
***
# Automatic detection of sign language gestures

## Présentation
This project was carried out with the Python language.

### Purpose:
* Detect letters and words of sign language in real time.
* Use machine and deep learning techniques such as boosting, neural networks (multilayer perceptron), deep neural network (convolutionnal neural network) and transfer learning.
* There are 9 tasks: 
⋅⋅* 1st task: Face detection simple (Create a real time video stream, Load the cascade classifier, Format and color transformation, Detect the face in the image, Draw rectangle around face, Detect eyes in the sub-region of face and draw rectangles)

Example of result:

We observe that the CNN is more efficient than the MLP, but the CNN is slightly slower than the MLP.
For the MLP, the execution time for 100 images is 34.51 seconds and the accuracy is 0.8.
For the CNN, the execution time for 100 images is 45.68 seconds and the accuracy is 1.0.

![alt text](https://github.com/JulienChoukroun/Automatic-detection-of-sign-language-gestures/blob/main/Images/PredictionA.png "Prediction for the letter A")

![alt text](https://github.com/JulienChoukroun/Automatic-detection-of-sign-language-gestures/blob/main/Images/PredictionB.png "Prediction for the letter B")

![alt text](https://github.com/JulienChoukroun/Automatic-detection-of-sign-language-gestures/blob/main/Images/PredictionC.png "Prediction for the letter C")

With the transfer learning:
We observe that the Transfer learning is very accurate (same as the CNN and more accurate than the MLP). But the execution time here is greater than the execution time for the MLP or for the CNN. Indeed, the scores are:
The execution time for 100 images is 92.53 seconds and the accuracy is 1.0.
