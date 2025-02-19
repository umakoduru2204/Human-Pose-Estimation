## Human-Pose-Estimation
## 1. Introduction

In this project we present our approach to human pose estimation using a machine learning model trained on a dataset comprising 5081 images annotated with landmarks describing human poses.


## 2. Dataset

https://drive.google.com/drive/folders/1oF1OB3Fgd-9MVarUTB4sJYMg1alPZWpt?usp=drive_link

Open this link and go back to the folder.

OCHuman Folder should be added to the shortcut in google drive.
This will allow us to link between Dataset and Google Colab.


## 3. Why this Dataset?
This dataset consists of 5081 high quality images.

It also uses annotations from json files to access the images.


## 4. How to Use?
There are two google colab files in the Github.

Human_Pose_Detection_Resnet.ipynb https://github.com/gaddamphanideepak/Human-Pose-Estimation/blob/main/Human_Pose_Estimate(Resnet_Model).ipynb

Human_Pose_Detection.ipynb https://github.com/gaddamphanideepak/Human-Pose-Estimation/blob/main/Human_Pose_Estimation(Pose_Estimator_Model).ipynb

Each of the notebook files must be open using google colab and they should be run independently after adding the shortcut of provided dataset in the google drive.
https://drive.google.com/drive/folders/1oF1OB3Fgd-9MVarUTB4sJYMg1alPZWpt?usp=drive_link


## 5. Results
We can find the Batch Loss and MSE Loss in the notebooks. This helps us to understand differences between Resnet and PoseDetector Model.
