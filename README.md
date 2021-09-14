# Traffic-Signs-Classifier
Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d (Conv2D)              (None, 28, 28, 6)         156       
_________________________________________________________________
average_pooling2d (AveragePo (None, 14, 14, 6)         0         
_________________________________________________________________
dropout (Dropout)            (None, 14, 14, 6)         0         
_________________________________________________________________
conv2d_1 (Conv2D)            (None, 10, 10, 16)        2416      
_________________________________________________________________
average_pooling2d_1 (Average (None, 5, 5, 16)          0         
_________________________________________________________________
flatten (Flatten)            (None, 400)               0         
_________________________________________________________________
dense (Dense)                (None, 120)               48120     
_________________________________________________________________
dense_1 (Dense)              (None, 84)                10164     
_________________________________________________________________
dense_2 (Dense)              (None, 43)                3655      
=================================================================
Total params: 64,511
Trainable params: 64,511
Non-trainable params: 0

Test Accuracy: 0.7764845490455627

![image](https://user-images.githubusercontent.com/64982203/133251946-9bfb7557-e810-46af-b62d-636864ec483f.png)
![image](https://user-images.githubusercontent.com/64982203/133251995-bd55d0f4-4709-4b64-8bf3-911384afe807.png)

Confusion_matrix:
![image](https://user-images.githubusercontent.com/64982203/133251360-91324cc2-3a89-467c-ab86-ed9d1a481d3f.png)

Prediction results:
![image](https://user-images.githubusercontent.com/64982203/133251514-ae90d248-4127-41ad-b1a5-da672c8b11d1.png)
