# Guava Disease Detection using CNN
Uses a image dataset from Kaggle related to Diseased and Healthy Guavas, to train and evaluate transfer learning models like MobileNet and VGG16 provided by TensorFlow.

> [Guava Image Dataset](https://www.kaggle.com/datasets/asadullahgalib/guava-disease-dataset/data)

The dataset was downloaded then splitted into train, validation and test sets. Then the models were trained using the train dataset, and during the training process validation was done using the validation dataset. Finally evaluation was done using the test dataset.

Transfer Learning Model Used:
1. MobileNet
2. ResNet101
3. VGG16
4. Hybrid - Random Forest & MobileNet

The accuracies attained by the models are:
|Models       |Accuracy Score |
|-------------|---------------|
|MobileNet    |98.95%         |
|RFC-MobileNet|92.15%         |
|VGG16        |98.43%         |
|ResNet101    |99.48%         |
