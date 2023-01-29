# Object-Detection-HOG-SVM
This project was forked repo from [post](https://github.com/saideeptalari/Object-Detector)
In this object detection uses Histogram of Gradient (HOG) + Support Vector Machine (SVM) framework for perfoming detection oject.

## About the Project
This project use HOG-SVM for object detection. For use this project, the step that you need to follows:
- Annotate the dataset

![Alt text](annotate.png?raw=true "Before annotation")
![Alt text](annotate-1.png?raw=true "After annotation")

- Traing the model

![Alt text](extracted-hog.png?raw=true "Extracted HOG")

- Test the model

![Alt text](test-result.png?raw=true "Test result")

### Built With
```sh
python test.py -d detector -i image -a annotation
```
## Getting Started

### Installation
Install the requirements
```sh
pip install -r requirements.txt
```

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
### Test-Realtime
```sh
python test.py -d jam_dinding_detector -i Dataset/Jam-Dinding/1.png -a Jam-Dinding
```