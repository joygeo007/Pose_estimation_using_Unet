# Animal Part Localization Using Deep Learning

This project involves training a deep learning model to predict the locations of various parts of animals. The model is trained using a UNet network architecture, which is particularly effective for image segmentation tasks.

## Dataset

The dataset used for this project is the COCO dataset, which is a large-scale object detection, segmentation, and captioning dataset. The dataset is modified to perform data augmentation, a common technique used to train a network to be robust to certain kinds of perturbations by adding random perturbations to the training data.

## Model

The model is a UNet network, which is a type of convolutional neural network that was originally developed for biomedical image segmentation. The UNet architecture is symmetric, with an encoding path to capture context and a decoding path to enable precise localization.

In this project, the UNet network is trained to predict the positions of 17 parts on a fruit fly. This involves feeding the network images of fruit flies and their corresponding labels, which indicate the locations of the 17 parts.

## Data Augmentation

Data augmentation is performed by adding random perturbations to the training data. This is done to make the model more robust to variations in the input data that it might encounter during inference.

The mmpose toolkit is used for data augmentation. This toolkit provides a variety of data transforms that are relevant for pose tracking, such as random scaling, cropping, and flipping of the input images.

## Future Work

This project serves as a foundation for further research and development in the field of animal part localization using deep learning. Future work could involve expanding the model to other datasets, improving the model's performance, and exploring other network architectures.

## Conclusion

This project demonstrates the effectiveness of deep learning for the task of animal part localization. By training a UNet network on a modified version of the COCO dataset, we are able to accurately predict the locations of 17 parts on a fruit fly. This work has potential applications in a variety of fields, including biology, medicine, and computer vision.
