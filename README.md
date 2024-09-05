# Wildfire-Detection-using-Convolution-Neural-Network-TensorFlow-

Wildfire is a davastating problem in California due to climate change. Last year, in 2021, there were 185 wildfires in California. Wildfires are usually detected by satellite and camera towel images. Human looking at these images causes fatiuge and error, so computer vision is a better alternative. TensorFlow is fast and great for this application. 

In this project, I couldn't find pre-existing images of fire and no-fire dataset, so I had to I manually download fire and no-fire images from the internet. I built a convolution neural network (CNN) by transfer learning with a pretrained model, Xception, to classify if an image shows there is or there is no wildfire.

The results were unsurprising and surprising at the same time. It's not completely surprising, because Xception has deep layers and was trained with a large amount of data, so it does an excellent job. The pleasant surprise was that even though Xception was trained to identify objects (e.g. cats, tigers, cars), with simple customization, it can classify fire and no-fire -- this is awesome! My educated guess is that because Xception has so many parameters (20,that it can capture the detailed features regardless if it's an object or not. But I'm not completely sure. 
