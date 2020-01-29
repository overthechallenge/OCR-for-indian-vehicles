## Web Application for Number Plate Detection in Residential Complexes (PS Code: CB31)
### Team Name: InIt_to_winIT

<p align="center">
  <img  src="/results/result_gif.gif">
</p>

### Introduction
Automatic number-plate recognition (ANPR; see also other names below) is a technology that uses optical character recognition on images to read vehicle registration plates to create vehicle location data.

In this repository we build a web application to automatically detect and identify vehicles and vehicle owners based on their number plates. The application is built in Node.js and a MongoDB backend is used. We plan to deploy the application on Docker to make it robust to run any machine. The model is based on [YOLOv3](https://github.com/AlexeyAB/darknet) and is trained to detect number plates in a variety of scenarios including but not limited to - multiple vehicles in a single frame and videos shot in low light.

The model is built taking into consideration the highest accuracy achievable without compromising on speed. It has been trained on more than 2000 images annotated manually.

### Training
`training_yolo.ipynb` is the Jupyter notebook which contains the code used to train the model. It can be run on [Google Colab](https://colab.research.google.com/) or locally using [Anaconda](https://www.anaconda.com/).

If you don't wish to train the model from the beginning and are looking for a pretrained model (**Insert Model Name**) is the model trained by us on a variety of images. 

### Dataset
The model has been trained on more than 2000 images. About 1000 images were taken for the dataset from the paper - and more than 1000 images were scraped from Google and some images were manually captured for odd and more difficult cases.

### Testing
(**To be written**)

### Results

A insight of the results obtained on the dataset provided by MixORG:

<p align="center">
  <img  src="/results/result_dataset_gif.gif">
</p>

**Additional results of our model**:

![](/results/result1.jpg)
![](/results/result2.jpg)
![](/results/result3.jpg)
