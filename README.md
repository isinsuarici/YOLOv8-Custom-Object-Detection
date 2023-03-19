# Mouse and Computer Object Detection using YOLOv8
## Dataset
There are 2 classes: mouse and computer. <br>
Roboflow was used for the labeling process. A total of 93 images were used, consisting of 69 for training, 16 for validation, and 8 for testing. The labeled images were stretched to 640x640 resolution. No augmentation was utilized. You can access the labeled data from [here](https://app.roboflow.com/estu-qjt4d/laptop-and-mouse/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true).

## Requirements
```
pip install ultralytics
```
## Steps to Run Code
* To get started, create a new folder in your Drive account and upload the dataset, data.yaml, and yolov8.ipynb files into it. <br>
* In the data.yaml file, replace the train, val, and test paths with the file paths in your own Drive account. <br>
* Finally, open the yolov8.ipynb file and run it to begin the process.
