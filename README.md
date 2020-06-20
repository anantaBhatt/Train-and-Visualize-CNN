# Train-and-Visualize-CNN

Software:
Kaggle- To create the documents and share the documents;
Anaconda: 3-5.2.0 - Windows-x86_64;
Tensorflow, Keras- 2.2.4
Solution:
Part 1: Train and Visualize CNN
Step 1: Import the CIfar10 dataset
Step 2: Store the training and testing dataset.(x_train, y_train), (x_test, y_test)
Step 3: Create placeholders for x,y with same size as the input [None,32,32,3]) and 
[None,1]) respectively. Reshape x into 4 dimension [-1,32,32,3].
Step 4: Creating 3 layers- convolution layers: relu layer, pool layer. For layer1, we set [3,3,3,64] whereas for layer 2 and 3 we set [3,3,64,64].
Step 5: Print relu layer 
Step 6: Create flatten layer, reshape with dimension [-1,8*8*64], output layer. We use AdamOptimizer(0.0001) to train the network.
Step 7: Print the loss and accuracy for 10 epochs.
Step 8: Visualising the filter:
-Set figure size to figsize=(20,20)
-Print 10 filters. Reshape the image to [3,3,3]
Step 9: Visualising the feature Map:
-Map session run with relu layer and x_train
-Set figure size to figsize=(20,20)
-Print 10 feature map. Reshape the image to [32,32]
