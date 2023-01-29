# Object-Detection-HOG-SVM
This project was forked repo from [post](https://github.com/saideeptalari/Object-Detector)
In this object detection uses Histogram of Gradient (HOG) + Support Vector Machine (SVM) framework for perfoming detection oject.

## About the Project

### Built With

## Getting Started

### Installation

## Usage

### Annotation
```sh
python annotate.npy -d Dataset/Jam-Dinding -a jam_dinding_annot.npy -i jam_dinding_image.npy
```
### Train
```sh
python train.py -a jam_dinding_annot.npy -i jam_dinding_image.npy -d jam_dinding_detector
```
### Test
```sh
python test.py -d jam_dinding_detector -i Dataset/Jam-Dinding/1.png -a Jam-Dinding
```