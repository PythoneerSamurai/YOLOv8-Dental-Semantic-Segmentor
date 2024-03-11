
# Dental Semantic Segmentor

A Semantic Segmentation Model trained in YOLOv8, that segments tooth images into four main categories:

['Background', 'Caries', 'Cavity', 'Crack', 'Tooth']


## Installation

You can either clone my repository by running the following command in your terminal (remember to open the terminal in the folder you want this project in)

```bash
 https://github.com/PythoneerSamurai/YOLOv8-Dental-Semantic-Segmentor.git
```
![App Screenshot](https://github.com/PythoneerSamurai/YOLOv8-American-Sign-Language-Detector/assets/112153865/b420f226-bec0-4fa7-8ba7-4194d1ca397a)

Otherwise, you can just download this project in the form of a ZIP file, by clicking the 'green code button' and then clicking the 'download ZIP' button.

![App Screenshot](https://github.com/PythoneerSamurai/YOLOv8-American-Sign-Language-Detector/assets/112153865/e6628a47-60fa-4762-b99e-e5e082c04cf3)

## Usage

The usage of the model is fairly simple, you need to have python installed. In addition to that you need a python library called 'ultralytics', you can install it by running the following command in your terminal

```javascript
pip install ultralytics
```

Afterwards, just open the 'main.py' file in the IDE or text editor of your choice, and specifiy the absolute path to the model file (a portion of the path is already written in the main.py file, so that you don't get confused)

![App Screenshot](https://github.com/PythoneerSamurai/YOLOv8-American-Sign-Language-Detector/assets/112153865/b708ef6b-b2d3-411e-9d98-407d930ed53c)

Then you need to specify the source, it can be any one of the options available in the list of inference sources on the following website:

https://docs.ultralytics.com/modes/predict/#inference-sources

Also, you can choose the inference source to be you webcam, source=0



## Acknowledgements

 - [Dataset from Roboflow Universe](https://universe.roboflow.com/reza-ohnxn/dental2-ztmiq/dataset/3)
 - [COCO JSON to YOLO txt segmentation annotations convertor](https://github.com/z00bean/coco2yolo-seg)
 - [Website for making nice GitHub readme files](https://readme.so/)



## License

No License.

