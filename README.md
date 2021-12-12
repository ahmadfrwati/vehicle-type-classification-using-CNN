# vehicle-type-classification-using-CNN


To run this model, do the following:
1- Pip install -r requirements.txt
2- Run prepare_data.py to customize both dataset and class-names
3- The outputs from step2 are numby arrays for (train and test splits) and they will exist in your current path.
4- Run model.py to get a model.h5 file
5- Convert .h5 file to frozen graph file .pb by using keras_to_frozengraph.py
6- Run vehicle_count.py by calling your input video and frozen-graph .pb file
7- Using cuda support by employing cuda toolkit (Nvidia) as suitable for your device
8- The module will recognize different pre-trained types of vehicles and count them frame-by-frame.

In this link below, you will find :
https://drive.google.com/drive/folders/1ItUQPzWFGqM4UJXOqChQE7zVROggjTWe?usp=sharing
-Datasets
-Input video as a sample
-Pre-trained models




The training plot:
![train-test](https://user-images.githubusercontent.com/77532350/145727210-96b53650-6384-4da7-b0d7-b28fa1d7d2a7.png)
