# CNN-SPP : ["Convolutional neural network with spatial pyramid pooling for hand gesture recognition"](https://link.springer.com/article/10.1007/s00521-020-05337-0)
Implementation of data augmentation (in python) and CNN-SPP (in tensorflow 1.15) in ["Convolutional neural network with spatial pyramid pooling for hand gesture recognition"](https://link.springer.com/article/10.1007/s00521-020-05337-0)

if you find this code useful for your research, please consider citing:

    @article{tan2020convolutional,
      title={Convolutional neural network with spatial pyramid pooling for hand gesture recognition},
      author={Tan, Yong Soon and Lim, Kian Ming and Tee, Connie and Lee, Chin Poo and Low, Cheng Yaw},
      journal={Neural Computing and Applications},
      pages={1--13},
      year={2020},
      publisher={Springer}
    }
    
 if GPU memory is not an issue, during testing, you can run all test images at once, just remove for loop in line 281 and line 395, and dedent the block of codes accordingly. 
 
 ## Datasets
 Only training sets without augmented data are provided, you can reproduce training sets with augmented data using Data_Aug.py file provided.
 
 For ASL NUS hand gesture dataset, only 1st fold is provided, as uploading all 5 folds (train and test) exceeds the github file size limit. You can make the remaining 4 folds by combining all images of 1st fold (train and test), and split it accordingly to make the remaining 4 folds.
 
 Data augmentation needs to be applied to the each fold of the training sets, images are not augmented in real-time during training.
