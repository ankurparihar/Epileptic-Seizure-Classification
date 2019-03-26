# Epileptic Seizure classification
- Dataset: [Kaggle](https://www.kaggle.com/chaditya95/epileptic-seizures-dataset)
## pulseNet
Used for transforming waves into images for classification by CNN<br>
[pulseNet](https://github.com/ankurparihar/pulseNet)<br>

## Tensorflow Image Classification CNN
CNN for multi-class image recognition in tensorflow

Forked from: https://github.com/rdcolema/tensorflow-image-classification

Notebook converted from Hvass-Labs' <a href="https://github.com/Hvass-Labs/TensorFlow-Tutorials/blob/master/02_Convolutional_Neural_Network.ipynb" >tutorial</a> in order to work with custom datasets, flexible image dimensions, 3-channel images, training over epochs, early stopping, and a deeper network.

Data format:
<pre>
	train/
		cat1/
		cat2/
		cat3/
	test/
		test/
</pre>
No need for validation data as it is internally split from train data
