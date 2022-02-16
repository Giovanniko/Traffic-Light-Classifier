# Traffic-Light-Classifier
Pre-processes a training set of traffic lights by standardizing the image size.
The image is then converted to hsv format by cropping and applying a mask using openCV2.
The individual hsv channels are analyzed. The 'v' channel is used as the governing factor to determine the light signal (Red, Yellow or Green)
The program divides the light into 3 horizontal sectors. 
The maximum average brightness of each sector's pixels determines the classification feature using one-hot encoding.
