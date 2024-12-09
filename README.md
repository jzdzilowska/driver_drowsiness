# Driver_Drowsiness


# Drowsy Driver Original Video Dataset:
  ## https://www.kaggle.com/datasets/rishab260/uta-reallife-drowsiness-dataset

# Drowsy Driver Downloaded Images:
  ## https://kaggle.com/datasets/3559143cb4c4bbedfe39f4dabf50f5ce8dd067b4e8dacc8bf6c7dfdda53ddcd2

#Blog Post:
 ## https://medium.com/@thliu_78532/building-a-drowsiness-driving-monitor-cf6402c6543d


Figure 1. Network Architecture
Each bar represents a singular layer in the network. Underneath the bar graph, the label for each of the different colors can be found. Bars of the same length vertically have the same number of input neurons and bars of the same thickness horizontally have the same number of output neurons. The figure was generated in the section of the code labled: Network Architecture.

Figure 2. Training and Testing Accuracy of the Model
The green line represents training accuracy, which refers to the model’s performance on the training data. As expected, it improved as the number of epochs increased. On the other hand, the red line represents testing accuracy, which refers to the model’s predictions on data that wasn’t in the original dataset used for training. As expected, it also improved as the number of epochs increased, even reaching a peak of 97.33% at 4 epochs, indicating an excellent performance. The figure was generated in the section of the code labled: Performance Evaluation and is the first of two graphs.

Figure 3. Training and Testing Loss of the Model
The green line represents training loss, which, like training accuracy, is an indicator of the model’s performance on the training data. As expected, it decreased as the number of epochs and the training accuracy viewed in Figure 2 increased. On the other hand, the red line represents testing loss, which also refers to the model’s predictions on data that wasn’t in the original dataset used for training. As expected, it was also reduced as the test accuracy, viewed in Figure 2, and the number of epochs increased. Both had values of less than .5 at epoch #4. The figure was generated in the section of the code labled: Performance Evaluation and is the second of two graphs.

Figure 4. Confusion Matrix for Drowsiness Detection
The left hand side represents the true classification label for each image and the bottom shows the predicted label. The right hand color bar goes from light blue to dark blue as the number of images increases. The Matrix shows that there was a high accuracy because the left to right diagonal has darker blues in comparison to the lighter blues in the remaining spaces. For example, the true classification for not drowsy had 404 predictions of being not drowsy in comparison to the 4 incorrect predictions of neutral and drowsy. The figure was generated in the section of the code labled: Confustion Matrix




