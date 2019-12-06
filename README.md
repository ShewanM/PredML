In this assigment you're going to use the pretrained network SqueezeNetv1.2 (~ 5 Mb)
here we are going to use the pretrained network SqueezeNetv1.2 (~ 5 Mb)

Tasks are:

   1 -  go to https://github.com/miaow1988/SqueezeNet_v1.2 and download the 'symbol.json' and '.params' files
      (there is not a 'synset.txt' file! so don't use these lines, Hint: just comment these lines).

   2 -  Install MXNet (hint: create a new conda environmet with python 3) and Use pre-trained models as feature extractors.
   
   3 - Find the flatten output layer and create a feature extractor (hint: It should be a numpy array of 1000 elements).

   ** Download the dogs versus cats training folder from https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data 
      (Remember the number of images is 12500 for each class).

   ** Extract the array of features for different number of images (N: 100, 1000, 5000 and 12500) 
      and for each value train your favorite binary classifier (only one!!!) using GridSearch to optimize some hyperparameters. 
      Consider to use https://notebooks.csc.fi if you have computational limitations.

   Check the accuracy for each value of N.
   Note: At least for N= 5000 and 12500 it can take some time depending your computer. 
   
