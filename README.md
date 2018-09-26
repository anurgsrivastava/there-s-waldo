# There's Waldo
A Machine Learning model that solves Where's Waldo puzzles by searching for the exact position of Waldo in a given image

![alt text](https://raw.githubusercontent.com/imanurg/there-s-waldo/master/docs/docs.png)

There's Waldo is a Tensorflow project that includes a model for solving Where's Waldo picture puzzles.
It uses Faster RCNN Inception model initially trained on COCO dataset and retrained for finding Waldo using transfer learning with Tensorflow Object Detection API.

## Getting Ready
1. Install latest version of Tensorflow
2. Follow [Tensorflow Object Detection Installation instructions](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md) (optional)

## Usage
```
python find_waldo.py images/1.jpg
```
The image should pop up with wally outlined 

## Requirements
- [Python 3.6+](https://www.continuum.io/download)
- [TensorFlow 1.3+](https://www.tensorflow.org/)

## Sources
- [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)
- [Training Images](https://github.com/vc1492a/Hey-Waldo)