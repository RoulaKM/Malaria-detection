# Malaria Detection
##Background
Malaria infection has been detrimental to human health outcomes, especially in African counties. Therefore, we decided to automate Malaria detection in human microscopic blood cell images. We investigated the data structure and properties to reach our goal and discussed using a convolutional neural network algorithm to configure the model. Later, we built, trained, and tested 14 models using different techniques. Comparing the 14 models, we decided that the first model was the best-performing model. Lastly, we provided suggestions for future improvements and policymakers.
## Methods and Procedures
We followed multiple steps to determine the best-performing model. First, we built two models from scratch using different numbers of convolutional layers and activation functions. Second, we manipulated the images to increase the variation by implementing an image data generator. This step included training our second model eight times using one technique at a time, then all of them at once. Lastly, we used the transfer learning process by borrowing the convolutional layers from a pre-trained VGG16 model and building a fully connected layer on top of it. The lastly mentioned model was trained using different learning rates and batch sizes.
## Conclusion
With the help of methodology and a multi-step process, we reached a model that correctly predicted 99% of our testing images. We can confidently say that clinicians can use our model to diagnose patients with Malaria. However, we strongly suggest reviewing the uninfected classified images by a specialist to avoid delaying the patient’s treatment.
## Author
Roula Krayem <br>
Roula.Krayem@outlook.com
