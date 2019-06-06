# Deep-Neural-Network--Road-Extraction--Remote-sensing-images


This tutorial will show how to implement Deep Neural Network for road extraction from orthophoto images  using keras package in
Anaconda3-5.3.0 Python 3.6 under Windows 10.

keras is a popular Python package for deep neural networks with multiple backends, including TensorFlow, Microsoft Cognitive Toolkit (CNTK), 
and Theano.
The keras package is able to provide a flexible and feature-rich API and can run both CPU and GUP version of TensorFlow in both Windows 
and Linux. If you want to run this tutorial with GUP version of TensorFlow you need following prerequisites in your system:

#Visual Studio v2013 or 2015.

#NVIDIA GUP: First, you must make sure weather your computer is running with NVIDIAÂ® GPU or not. 

#CUDA Toolkit v10.0.130: If you have an NVIDIAÂ® GPU in your system, you need to download and install CUDA Toolkit v9.0. 

#cuDNN v7.0: The download the zip file version cuDNN v7.0 for your CUDA Toolkitv10.0.130. You need to extract the zip file and add the
location where you extracted it to your system PATH. 

For applying the method, first, we will split the data into a training set and validation (70% of the data),  and a test set (30%) data.
The validation data set will be used to optimize the model parameters during training process.
The model's performance will be tested with the data set and then we will classfiy images into road and non-road parts.
Finally, use opening trivial nad closing operation for binary image and removing noises. 
