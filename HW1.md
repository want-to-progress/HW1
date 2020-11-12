# HW1
Car brand classification
github:https://github.com/want-to-progress/HW1
## Menu

* Development Environment and Platform
* How to use the model
    * installation 
    * project directory
    * google colab
    * LoadDate.ipynb
    * HW1.ipynb
    * Pre-trained weight
____________________________

## Development Environment and Platform

* Google Colab(need to login google account)
https://colab.research.google.com/notebooks/intro.ipynb

____________________________

## How to use the model
### installation
clone the github add put all the file on to colab
### project directory
* put HW1.ipynb in (your google drive)/Colab Notebooks/HW1
* put training_labels.csv, training data folder, testing data folder, and LoadDate.ipynb in (your google drive)/Colab Notebooks/HW1/datas

(your google drive)/Colab Notebooks/HW1
--------| HW1.ipynb
--------+ datas
-------------| training_labels.csv
-------------| LoadDate.ipynb
-------------+ training data folder
-------------+ testing data folder
### google colab
if you are new to colab. please see the intro. of colab
https://colab.research.google.com/notebooks/intro.ipynb

### LoadDate.ipynb
In (your google drive)/Colab Notebooks/HW1/datas
open as a colab file add run all the cell
The program will resize the image to 128x128
<font color="#f00">*Reminder*</font>
you need to give some authority to colab in the second cell
![](https://i.imgur.com/khrA62Z.png)
It will take several minutes to run through all the cells

### HW1.ipynb
In (your google drive)/Colab Notebooks/HW1
<font color="#f00">*Reminder*</font>
you need to give some authority to colab in the second cell
* If you want to do Training, you need to run group of cells below
1. load csv and marco
2. Cnn Architure
3. All cells in training, including
    1. load training data
    2. Data Augmentation
    3. Save model
    4. Training the model
    5. Second Training
* If you want to do Testing, you need to run group of cells below
1. load csv and marco
2. Cnn Architure
3. All cells in testing, including
    1. load testing data
    2. predict
    3. save csv
### Pre-trained weight
* best_model.h5 is the Pre-trained weight. If you want to use the pre-trained weight, please put the .h5 file at (your google drive)/Colab Notebooks/HW1
* If you train the cnn model, the model will save the best weights each epochs with the file name best_model.h5.

### Get Prediction
After you run the testing part of HW1.ipynb, you will get a .csv file. The csv file contain the image id and predicted label.