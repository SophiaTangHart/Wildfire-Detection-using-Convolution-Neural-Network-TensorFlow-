# Wildfire-Detection-using-Computer-Vision

Wildfire is a davastating problem in California due to climate change. Last year, in 2021, there were 185 wildfires in California. Wildfires are usually detected by satellite and camera towel images. Human looking at these images causes fatiuge and error, so computer vision is a good application. TensorFlow is fast, so it is a suitable technology for computer vision since images have more data points than text or numbers. 

In this project, I couldn't find pre-existing dataset of fire and no-fire images from the Internet (as of April 2022), so I selected and manually downloaded each fire and no-fire picture from the Internet. I built a convolution neural network (CNN) by transfer learning with a pretrained model. After extensive research, I chose Xception for my model. My model classified if an image showed there was a wildfire or not.

The results were unsurprising and surprising at the same time. It's not completely surprising, because Xception has deep layers (~150 layers) and was trained with tons of data, so it does an excellent job. However, the fact that I could transfer this pretrained model for my model to accomplish my job was super helpful. Specifically, the pleasant surprise was that even though Xception was trained to identify objects (e.g. cats, tigers, cars), with my simple customization, it can classify fire and no-fire images -- this is awesome! My educated guess is that Xception has so many parameters (20,061,400), it can capture detailed features regardless of its shape. What do you think is the reason?

The advantage of using a pre-trained model is that it saves time and computer resources to train the model and doesn't require as much data to fine-tune it. 

One may consider wildfire a problem. However, they keep the balance of forests. I realized this after visiting Mariposa Grove at Yosemite in August 2024. The sequoias can last 4,000 years despite being exposed to fire every 5-20 years! My husband told me the seeds in the cons of sequoias only release seeds (in extreme heat) from fires. So wildfires are not that bad after all :)
