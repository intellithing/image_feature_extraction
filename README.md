# image_feature_extraction
Extract features from an image by HSV

In real estate industry, swimming pool is an important factor in pricing a house. One popular approach to price a house is using a clustering algorithm to figure out mean value in certain area, then factor in other important auxiliaries to estimate a final price.

Once swimming pools can be detected from pictures a machine learning algorithm, the process of price estimation may be automated.

To train such a supervised learning model, we need to extract features from image data. Here we demonstrate how to use OpenCV and Python to implement feature extraction. Note that this step can also be done by a Deep Learning technique such as a CNN architecture during convolution.

The idea is that swimming pools are bluish, so we construct HSV masks in certain ranges and apply them to image data. We then use the filtered images as features to train a supervised learning model. This model may be used to detect swimming pools in unseen images.
