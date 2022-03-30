# Lab1_Chest_Xray
Detect Pneumonia from chest X-ray images.
## Lab Objective
Step 1: You need to write your own custom DataLoader.  
Step 2: You need to classify Pneumonia with your own model.  
Step 3: You have to evaluate the performance.  

## Dataset Chest X-ray (kaggle)
training_filenames_normal: 1341  
training_filenames_pneumonia: 3875  
test_filenames_normal: 234  
test_filenames_pneumonia: 390  
![image](https://github.com/poyuwang/Lab1_Chest_Xray/blob/main/image/normal_vs_pneumonia.PNG)


## Using model
resnet50  

![image](https://github.com/poyuwang/Lab1_Chest_Xray/blob/main/image/resnet50.PNG)

densenet121  

![image](https://github.com/poyuwang/Lab1_Chest_Xray/blob/main/image/densenet121.PNG)

### best testing acuracy
resnet50: 86.54%  
![image](https://github.com/poyuwang/Lab1_Chest_Xray/blob/main/image/resnet50accuracy.PNG)

densenet121: 89.74%  
![image](https://github.com/poyuwang/Lab1_Chest_Xray/blob/main/image/densenet121accuracy.PNG)

## model code
See train.py
