# Classify Traffic Sign   

I build a CNN with Keras to classify the traffic signs   
It seems the accuracy is not bad, however the test on real images was totally a failure   
Anyway it's for practice...   
And the framework is still Udacity's self driving car nanodegree [project](https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project)
and I simplified a lot
     
## Environment
* Python 3.5
* Keras 2.0.4
* Tensorflow 1.3.0   
     
## The Model
* 3 Convolution layers with units 16, 32, 64 respectively and kernel size 3 x 3
* 2 Dense layers with units 1024, dropout rate 0.5
