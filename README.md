# Monkey Image Classification
This notebook presents the code for classifying images of monkeys using the Tensorflow library. Through the use of convolutional neural networks (CNN), it was possible to reach a precision (accuracy) of 100% in the image classification.

## Dataset
The dataset used in this project is "Monkeys", available on Kaggle. It consists of 5 monkey species with a total of 500 images.

## Preprocessing
Before using the images to train CNN, it was necessary to perform some pre-processing steps, including:

Resizing: The images were resized to 160x160 pixels so they were all the same size.
Normalization: the pixel intensities of the images were normalized to vary between 0 and 1, which is important to facilitate CNN training.

## Test
After training, the model was evaluated using the test image set. An accuracy of 100% was achieved in classifying the images, which indicates that the model is able to distinguish between different species of monkeys with high precision.

## Conclusion
This project demonstrated how it is possible to use the Tensorflow library to classify images of monkeys with high precision. Through the use of convolutional neural networks and image pre-processing techniques, it was possible to obtain 100% accuracy in image classification. This project can be applied in several areas, including identification of animals in the wild and conservation of species.

## References
Kaggle dataset: https://www.kaggle.com/datasets/sarasnchez/monkeys

## Contribution
Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request. the pull request.
