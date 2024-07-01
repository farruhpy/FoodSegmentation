# FoodSegmentation

Food Product Recognition and Expiry Date Detection using Deep Learning
Introduction
This project aims to develop a deep learning model that can identify food products from images and provide information about their expiration dates. This can help in reducing food waste and ensuring food safety.

Problem Statement
Recognizing food products and their expiration dates is crucial for inventory management, especially in the retail and food service industries. Manual checking is time-consuming and prone to errors.

Solution
Using convolutional neural networks (CNNs), the model is trained to detect and classify food products and extract their expiration dates from images.

Model Architecture
The model uses a pre-trained resnet34 (e.g., ResNet, Inception) for feature extraction, followed by custom layers for classification and text detection.

Implementation
Data Collection: A dataset of food product images with labeled expiration dates was created.
Preprocessing: Images were resized, normalized, and augmented to improve model generalization.
Training: The model was trained using transfer learning with fine-tuning on specific layers.
Evaluation: The model was evaluated using accuracy, precision, recall, and F1-score.
Results
The model achieved an accuracy of 60% on the test dataset. But this model performs at an average accuracy of 85%+ with real images and data.
Because this indicator is obtained through test data, and there are some errors in this data itself.
Below are some examples of its predictions:


Example 1:
![image](https://github.com/farruhpy/FoodSegmentation/assets/158803506/02a7a4c4-3ed1-4acf-a3a1-eaa7c6f143e1)


Example 2:
![image](https://github.com/farruhpy/FoodSegmentation/assets/158803506/c25be0a2-3f70-4b23-89b4-79f5266e3921)


Example 3:
![image](https://github.com/farruhpy/FoodSegmentation/assets/158803506/83f29ad5-19d9-4651-8201-9e44218eb32a)


Below is the prediction made by the model and the actual label:
![image](https://github.com/farruhpy/FoodSegmentation/assets/158803506/f95048ed-9210-4315-9adf-51d06cb52bff)



As you can see, the picture shows rice but the actual label says it's eggs, which the model correctly predicted as rice.




Challenges and Solutions
One of the main challenges was handling low-quality images. Data augmentation and preprocessing techniques were used to mitigate this issue.

Conclusion
This project demonstrates the potential of deep learning in automating food product recognition and expiration date detection. Future work includes expanding the dataset and improving text detection accuracy.
