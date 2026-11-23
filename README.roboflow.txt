
corrosion-classification-v2 - v1 2022-06-26 11:35pm
==============================

This dataset was exported via roboflow.com on October 21, 2022 at 11:55 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 7501 images.
Corrosion are annotated in folder format.

The following pre-processing was applied to each image:
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random brigthness adjustment of between -15 and +15 percent
* Random exposure adjustment of between -5 and +5 percent
* Random Gaussian blur of between 0 and 0.75 pixels


