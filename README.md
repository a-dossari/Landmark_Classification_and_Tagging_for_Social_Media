# Landmark Classification & Tagging for Social Media

### Project Overview

Photo sharing and photo storage services like to have location data for each photo that is uploaded. With the location data, these services can build advanced features, such as the automatic suggestion of relevant tags or automatic photo organization, which help provide a compelling user experience. Although a photo's location can often be obtained by looking at the photo's metadata, many photos uploaded to these services will not have location metadata available. This can happen when, for example, the camera capturing the picture does not have GPS or if a photo's metadata is scrubbed due to privacy concerns.

If no location metadata for an image is available, one way to infer the location is to detect and classify a discernible landmark in the image. Given the large number of landmarks across the world and the immense volume of images that are uploaded to photo-sharing services, using human judgment to classify these landmarks would not be feasible.

In this project, you will take the first steps towards addressing this problem by building models to automatically predict the location of the image based on any landmarks depicted in the image. You will go through the machine learning design process end-to-end: performing data preprocessing, designing and training CNNs, comparing the accuracy of different CNNs, and using your own images to heuristically evaluate your best CNN.

![alt text](https://video.udacity-data.com/topher/2021/February/602dac82_landmarks-example/landmarks-example.png) 
<p align="center">
    Examples from the landmarks dataset - a road in Death Valley, the Brooklyn Bridge, and the Eiffel Tower
</p>

### The Data
This dataset is called [Landmark Classification dataset](https://udacity-dlnfd.s3-us-west-1.amazonaws.com/datasets/landmark_images.zip), and contains images of over 50 landmarks.

### Project Steps
**1. Create a CNN to Classify Landmarks (from Scratch)**

> We'll visualize the dataset, process it for training, and then build a convolutional neural network from scratch to classify the landmarks.

**2. Create a CNN to Classify Landmarks (using Transfer Learning)**

> Next, we'll investigate different pre-trained models and decide on one to use for this classification task. Along with training and testing this transfer-learned network.

**3. Write Landmark Prediction Algorithm**

> Finally, we'll use the best model to create a simple interface for others to be able to use the model to find the most likely landmarks depicted in an image. You'll also test out the model and reflect on the strengths and weaknesses of the model.
