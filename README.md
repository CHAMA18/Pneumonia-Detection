<p align="center">
  <img width="420" alt="pneumonia-detection-logo" src="https://user-images.githubusercontent.com/76659596/105877774-9de18080-6000-11eb-985a-64591f7aac86.png">
</p>


## Motivation
The Pneumonia disease is a lung infection (🫁) that inflames the air sacs in one or both lungs. This infection arises when the air sacs get filled with fluid or pus (purulent material). It can be bacterial or viral infection. The main symptoms are - cough with phlegm or pus, fever, chills, and difficulty in breathing. 

This disease is responsible for over 15% of all deaths of children under 5 years old worldwide. This proves the severity of this disease and the need of accurate detection. 

The most commonly used method to diagnose pneumonia is through chest radiograph or chest X-ray which depicts the infection as an increased opacity in certain area(s) of the lungs.

To increase the efficacy and reach of the diagnosis procedure, we can use machine learning alogorithms to identify abnormalities in the chest X-ray images. In this model, a large number of chest X-ray images (both normal and pneumonia) are fed to build `Convolutional Neural Network (CNN)` model for fulfilling the purpose. 


## Requirements

- Python 3.7.x
- Tensorflow 2.4.1+
- Keras 2.4.3+
- scikit-learn 0.24.1+
- matplotlib 3.3.3+

## Dataset

The dataset can be downloaded from [kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/). Use the underlying download link to diwnload the dataset.

### Instructions to follow

* Extract the archive
* You will find several directories in it
* Copy the `chest-xray` directory contents (`train`, `test` and `val` subdirectories) to the `data` folder

The number of images belonging to both classes (`Normal` and `Pneumonia`) in the `train`, `test` and `val` datasets are -

<img width="326" alt="Screenshot 2021-02-07 at 16 40 00" src="https://user-images.githubusercontent.com/76659596/107151515-4083f280-6963-11eb-84c7-f2a23cc24134.png">


## Installation

* Clone the repository 

`git clone https://github.com/baishalidutta/Pneumonia-Detection.git`

* Install the required libraries

`pip3 install -r requirements.txt`

## Usage

Enter into the `source` directory to execute the following source codes.

* To generate the model on your own, run

`python3 cnn_training_model.py` 

* To evaluate any dataset using the pre-trained model (in the `model` directory), run

`python3 cnn_model_evaluation.py`

Note that, for evaluation, `cnn_model_evaluation.py` will use all the images contained inside both `test` and `val` subdirectories (inside `data` directory).

Alternatively, you can find the whole analysis in the notebook inside the `notebook` directory. To open the notebook, use eithr `jupyter notebook` or `google collab` or any other IDE that supports notebook feature such as `PyCharm Professional`.

## Evaluation 
This model 


## Web Application

## Developer

## Contribution

## License


