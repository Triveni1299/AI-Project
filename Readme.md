# Project 
The project will develop a real-time forest fire detection and monitoring system using UAV technology and advanced image processing techniques. By leveraging drones to capture aerial images of large forest areas, we aim to implement algorithms that can effectively detect smoke and flames. The goal is to provide early warnings to forestry management, enabling prompt action to prevent significant economic losses caused by forest fires. Ultimately, we seek to enhance the safety and efficiency of forest fire prevention and control efforts.
# Execution process
# transfer.ipynb file:
initial file implementation with transfer learning using the VGG19 model
The accuracy on the training set was 65% and on the testing set, it was only 58%.

# First1-rmsprop. ipynb file:
RMSprop optimizer was used to train the custom Convolutional Neural Network (CNN) model for wildfire detection. We used the rmsprop optimizer during the compilation phase to set up the model. This helped adjust the learning rate during training, ensuring the model’s weights were updated effectively. The model was trained on augmented images using ImageDataGenerator, and the optimizer helped improve the model's performance by reducing the training loss. We also used callbacks like Model Checkpoint and EarlyStopping to save the best model and prevent overfitting. Overall, RMSprop was key in achieving good training results for the wildfire detection task.
# First1-adadelta. ipynb
The Adam optimizer was a key component in the training process of the models used for wildfire detection. It was chosen for its efficiency and ability to handle large datasets with minimal tuning. In this project, Adam was applied during the model compilation phase, where the loss function was set to binary_crossentropy to classify images into two categories: wildfire or no-wildfire. 
 the model was able to converge efficiently, achieving a final testing accuracy of 93.18% and a training loss of 0.18.
