# Breast cancer histopathology image classification using CNN

The breast cancer is one of the wide spread diseases
around the world. Cancer develops in a milk duct and then
spreads to the surrounding breast tissues. This initial stage of
progression is called invasive ductal carcinomas (IDC). Almost
80% of all breast cancers are invasive ductal carcinomas. If
IDC is detected at early stages, the patient can be treated and
will have a high survival rate, whereas undetected cancer may
spread into other parts of the body, as well as surrounding
breast tissues. In this work, the dataset that contains breast
cancer histopathology images was used. The objective of this
work is to implement a convolutional neural network (CNN)
model for accurate IDC classification, by balancing the dataset
and tuning hyperparameters. The proposed model achieves an
accuracy of 92% for the classification of histopathological images,
and outperforms the baseline CancerNet model with accuracy
of 86%. Furthermore, our experimental results demonstrate the
superiority of our approach over the pre-trained networks, such
as VGG16, DenseNet and ResNet18.

# Dataset

The dataset used in this project can be found here: https://drive.google.com/drive/folders/11R9KP832C3DvY0DkbW_-O2wJGabNKPMJ?usp=sharing

# Conclusion

In the presented work we implemented a CNN model for
breast cancer recognition based on the IDC dataset (with
histopathological images of invasive ductal carcinoma). Ini-
tially, we did a literature review of relevant work among
the most common subtypes of all breast cancers, as well
as available datasets. As a result, we chose the CancerNet
network as the baseline approach, also trained multiple CNN
networks from PyTorch library, to compare them with our
solution. We were able to obtain acceptable results with all
CNN models, however the presented CNN architecture was su-
perior. One of the main reasons for such results is the properly
balanced dataset used for training and testing. To conclude, we
discovered that modern CNN models can be effectively used to
detect breast cancer tissues from histopathology scan images,
by this saving someone’s life.
