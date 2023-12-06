# Real Time Face Mask Detection using PyTorch

### Dataset

**Face Mask Detection**

Masks play a crucial role in protecting the health of individuals against respiratory diseases, as is one of the few precautions available for COVID-19 in the absence of immunization. With this dataset, it is possible to create a model to detect people wearing masks, not wearing them, or wearing masks improperly.
This dataset contains 853 images belonging to the 3 classes, as well as their bounding boxes in the PASCAL VOC format.
The classes are:
   - With mask;
   - Without mask; 
   - Mask worn incorrectly.



link - > [Kaggle](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection)

### Model Building

- ResNet - Deep Residual Learning for Image Recognition 
        
The Residual Network, or ResNet for short, is a model that makes use of the residual module.There are several variants of different sizes, including Resnet18, Resnet34, Resnet50, Resnet101, and Resnet152, all of which are available from torchvision models. Here Resnet34 model is used