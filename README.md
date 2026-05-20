# IMAGE-CLASSIFICATION-MODEL

"COMPANY": CODTECH IT SOLUTIONS

"NAME": Buchipalli Subhash

"INTERN ID": CTIS9355

"DOMAIN": Machine Learning

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTOSH

# DESCRIPTION OF TASK  : IMAGE CLASSIFICATION MODEL USING CNN

The objective of this project is to build an Image Classification Model using a Convolutional Neural Network (CNN) with the help of TensorFlow and Deep Learning techniques. Image classification is one of the most important applications of Artificial Intelligence and Computer Vision. The purpose of this project is to train a machine learning model that can recognize and classify handwritten digit images correctly.

In this project, the MNIST Handwritten Digits Dataset was used for training and testing the CNN model. The MNIST dataset is one of the most popular datasets used for image classification tasks. It contains thousands of grayscale images of handwritten digits from 0 to 9. Each image is of size 28 × 28 pixels. The dataset is divided into training images and testing images. The training dataset is used to teach the model, while the testing dataset is used to evaluate the model performance.

The project was implemented using Python programming language along with TensorFlow, Keras, and Matplotlib libraries. TensorFlow and Keras were used for building and training the Convolutional Neural Network model, while Matplotlib was used for visualizing the predicted images and outputs.

The first step in the project was loading the MNIST dataset from TensorFlow datasets. After loading the dataset, preprocessing was performed on the images. The pixel values of images were normalized by dividing them by 255. This normalization process converts pixel values into a range between 0 and 1, which helps the model learn more efficiently and improves the training performance.

After preprocessing, the image data was reshaped into a format suitable for CNN input. Since Convolutional Neural Networks require image dimensions including channels, the dataset was reshaped into 28 × 28 × 1 format. Here, “1” represents the grayscale color channel.

The CNN model was then created using different layers. The first layer used in the model was the Convolutional Layer (Conv2D). This layer extracts important features from images such as edges, curves, shapes, and patterns. After the convolution layer, MaxPooling layers were used to reduce the image dimensions and decrease computational complexity. Pooling also helps in extracting the most important features from the images.

After feature extraction, the Flatten layer was used to convert multidimensional image data into one-dimensional form. Dense layers were then added for classification purposes. The final Dense layer used the Softmax activation function to classify images into one of the ten digit categories ranging from 0 to 9.

The model was compiled using the Adam optimizer and sparse categorical crossentropy loss function. Accuracy was used as the evaluation metric. The model was trained for multiple epochs using the training dataset. During training, the CNN model learned patterns from thousands of handwritten digit images and improved its prediction accuracy gradually.

After training, the model was evaluated using the testing dataset. The project achieved a very high test accuracy of approximately 99%, which indicates that the model can classify handwritten digits with excellent performance. Predictions were also generated for test images, and the predicted digit label was displayed along with the corresponding image.

For example, when an image of handwritten digit “7” was given to the model, the CNN correctly predicted the label as “7”. This demonstrates that the model successfully learned image features and patterns from the dataset.

This project provides practical knowledge about Deep Learning, Image Processing, and Computer Vision concepts. It demonstrates how Convolutional Neural Networks can be used for image classification tasks efficiently. The project also helps in understanding model training, preprocessing, feature extraction, prediction, and performance evaluation.

Overall, the Image Classification Model was successfully implemented using TensorFlow and CNN architecture. The model achieved high accuracy on the MNIST dataset and demonstrated the real-world application of Deep Learning techniques in image recognition systems.

# Output

<img width="1553" height="481" alt="Image" src="https://github.com/user-attachments/assets/4b7ce3b7-d7d7-403d-9c25-dede03144ff7" />

<img width="894" height="673" alt="Image" src="https://github.com/user-attachments/assets/c72e2cab-1110-4390-b67b-a85f38cc4f97" />

<img width="1066" height="125" alt="Image" src="https://github.com/user-attachments/assets/a0afd95a-878a-4ab7-96d8-f627d1c02007" />
