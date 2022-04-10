# Monitor fitness exercises
Monitor fitness exercises with machine learning. Ensure that, id you're doing the exercise correctly with Tensorflow, a webcam and OpenCV Python real-time computer vision libraries

## How does this work?
Machine learning packages available for Python 3
- Scikit-learn - open source Python machine learning library supporting supervised learning & weightings
- Tensorflow Keras - high-level API to build and train models 
- OpenCV - library of programming functions for real-time computer vision

## Training
Training images
We have given training images that are good and bad exercising images. These images are required as input to train supervised learning algoritm. There is also capture mode where custom models can be trained with the camers. In capture mode a sample image is captured every second and saved in a training folder.  Run the capture mode whilst moving a bit in space to give a variety amongst the images.

## Train
Now we have a variety of images represnting both "good" and "bad" fitness exercises. We have trained the model already. You can also train the model with the custom captured images. Now train the model. This should only take a few minutes. The more images captured will takle longer to train, but should be more accurate.

## Live Video with Sound
With the model trained we can test the classification by running a live video feed from the webcam into the model. The classification and predication confidence is overlaind onto the image. A voice will be played if you're doing the exercise "bad".
