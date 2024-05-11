# Traffic-Sign-Detector
This project focuses on classifying images of traffic signs using convolutional neural network (CNN) and ResNet models trained on the German Traffic Sign Benchmark dataset. The dataset comprises over 50,000 images categorized into more than 40 classes of traffic signs.

The motivation behind the project lies in the importance of accurate traffic sign classification for road safety. Traditional methods often struggle with real-world variations, prompting the use of deep learning models like CNNs and ResNets to automatically learn and extract features from images.

The methodology involves preprocessing the images by resizing them to uniform dimensions and converting them into numerical representations. For the CNN model, a pre-trained sequential model was fine-tuned with additional layers, batch normalization, and dropout to improve accuracy to 97%. For the ResNet model, a pre-trained ResNet50 architecture was fine-tuned, leading to a testing accuracy of 99.26%.

Training was conducted on the Google Colab GPU runtime with a 75:25 testing to validation split, 20 epochs, a batch size of 32, and a learning rate of 0.001.

The project aims to contribute to improving road safety by providing insights into the performance of CNN and ResNet models for traffic sign classification. The results demonstrate high accuracy and robustness, supporting the project's goal of enhancing traffic sign recognition systems to mitigate accidents caused by human error.
