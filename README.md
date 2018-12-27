# There's Waldo
A Machine Learning model that attempts to solve Where's Waldo picture puzzles by searching for the exact position of Waldo in the given image

![alt text](https://raw.githubusercontent.com/imanurg/there-s-waldo/master/docs/docs.png)

'There's Waldo' is a Tensorflow project that includes a model for solving Where's Waldo picture puzzles.
It uses a Faster RCNN Inception model initially trained on COCO dataset and retrained for finding Waldo using transfer learning with Tensorflow Object Detection API. The link for the API and the training set is mentioned below.

## Getting Ready
1. Install the latest version of Tensorflow
2. Follow [Tensorflow Object Detection Installation Instructions](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md) (Optional)

## Usage
```
python3 find_waldo.py images/1.jpg
```
The queried image should pop up with Waldo outlined in a box.

## Requirements
- [Python 3.6+](https://www.continuum.io/download)
- [TensorFlow 1.10+](https://www.tensorflow.org/)

## Sources
- [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)
- [Training Images](https://github.com/vc1492a/Hey-Waldo)
