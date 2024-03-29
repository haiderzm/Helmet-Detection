# Helmet-Detection and Tracking
### Task :- Train object detection and tracking model to identify and count helmets from video.


## Steps Involved :-
#### 1. Data gathering
#### 2. Data Labelling
#### 3. Model/Algorithm Selection
#### 4. Fine-Tunning the model for helmet detection
#### 5. Testing on the given videos


## Data gathering

#### The images for training the deeplearning model are gathered from github repository (0816-Radhu/helmet_detection_using_machine_learning) and some random images of traffic containing bikers from websites like wired.com, bbc.com and youtube.com


## Data Labelling

#### To label the images an open-source tool labelImg is used (https://github.com/tzutalin/labelImg) in the format of yolo. 
#### Link to my labelled data (https://drive.google.com/drive/u/1/folders/1azB-EBLXyyAJRi4XGcF3aEemr2xjNfM6)


## Model/Algorithm Selection(Object-Detection)

#### Model used for the task is ultralytics implementation of yolo-v5 model in PyTorch (https://github.com/ultralytics/yolov5) 
#### YOLOv5 🚀 is a family of object detection architectures and models pretrained on the COCO dataset, and represents Ultralytics open-source research into future vision AI methods, incorporating lessons learned and best practices evolved over thousands of hours of research and development.

## Model/Algorithm Selection(Object-Tracking)

#### Model used for tracking is DeepSort on yolo v5 base detection, Repository used (https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch)

## Fine-Tunning the model for helmet detection

#### Model is trained/fine-tuned using the free-gpu provided by google colaboratory on the custom helmet detection dataset for 350 epochs. The library used is PyTorch.
#### Link to the model :- (https://drive.google.com/file/d/1M5MAgENH1y7DgzISWVKkx_QklMGfB3-l/view)


## Testing on videos
#### The model was tested on 2 youtube videos link to the original videos are :- 
####  https://www.youtube.com/watch?v=9WNzIDEcNP4 (Bike racing | royalty free video | no copyright | use in your project #racing #bikes - YouTube)
####  https://www.youtube.com/watch?v=iEIk3RpV6RA (CRAZY INDIAN TRAFFIC CONGESTION - YouTube)
#### Link to the results of detection :-
#### https://drive.google.com/file/d/1mK9z8aOzBd-aISPf4i_q-xwbbNxsLLwV/view?usp=sharing (Detection of Bike racing)
#### https://drive.google.com/file/d/1WwKe5I9-J4RdzTq6Y79gpYUWhSz4Lj7U/view?usp=sharing (Detection of Crazy Indian Traffic)
