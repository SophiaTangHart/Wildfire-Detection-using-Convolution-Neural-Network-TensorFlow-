# Wildfire-Detection-using-Convolution-Neural-Network-TensorFlow-

Wildfire is a davastating problem in California due to climate change. Last year, in 2021, there were 185 wildfires in California. Wildfires are usually detected by satellite and camera towel images. Human looking at these images causes fatiuge and error, so computer vision is a better alternative. TensorFlow is fast and great for this application. 

In this project, I couldn't find pre-existing images of fire and no-fire dataset, so I had to I manually download fire and no-fire images from the internet. I built a convolution neural network (CNN) by transfer learning with a pretrained model, Xception, to classify if an image shows there is or there is no wildfire.

The results were nonsurprisingly good and surprising at the same time. Xception has  Even though the pretrained model was trained for objects (cats, tigers, cars, etc). With a simple customization, it can classify fire vs. no-fire as well -- which is awesome! 
